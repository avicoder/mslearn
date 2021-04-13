---
    layout: post
    title: Design an MVVM viewmodel for Xamarin.Forms - Use commands in a viewmodel
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/design-a-mvvm-viewmodel-for-xamarin-forms/5-use-commands-in-a-viewmodel/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/xamarin/design-a-mvvm-viewmodel-for-xamarin-forms-badge.svg">
####  1. In Xamarin.Forms, which of the following techniques to handle a button click is best for the testability of your code?


<i class='far fa-square'></i> &nbsp;&nbsp;Subscribe to the Click event and place your handler in your .xaml.cs code-behind file.

<i class='far fa-square'></i> &nbsp;&nbsp;Inherit from the Button and override the OnClick method.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a property of type EventHandler to your viewmodel, and bind it to the button's Click event.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add a property of type ICommand to your viewmodel, and bind it to the button's Command property.
<br />
<br />
<br />

####  2. Say you're using Xamarin.Forms to write an app that calculates a 15 percent tip on a restaurant bill. You want to use the MVVM design pattern. Your UI contains an Entry for the user to type in the bill amount and a Button to click to do the calculation. You want to put the logic into your viewmodel, so you decide to use a Command to implement the behavior of the app. How should your viewmodel get the bill amount into the calculation when the command is executed?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a publish-subscribe system like Xamarin.Form's MessagingCenter.

<i class='far fa-square'></i> &nbsp;&nbsp;Add an x:Name value to the Entry and have your ICommand implementation access the Entry's Text property directly.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The amount should be data-bound to another property in the same viewmodel where the Command implementation is located. Then the command can access the property value right in the viewmodel.

<i class='far fa-square'></i> &nbsp;&nbsp;Wire up the Click event in code behind and pass the text to a public method of the viewmodel.
<br />
<br />
<br />
