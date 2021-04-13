---
    layout: post
    title: Create custom controls with Xamarin.Forms renderers - Send notifications between a renderer and an element
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-custom-controls-with-forms-renderers/7-send-notifications-between-renderer-element/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/xamarin/create-custom-controls-in-xamarin-forms-with-renderers-badge.svg">
####  1. When coding a custom renderer in Xamarin.Forms, which renderer method should be overridden to do initialization like creating the native control, setting native properties, and so on?


<i class='far fa-square'></i> &nbsp;&nbsp;OnElementPropertyChanged

<i class='far fa-square'></i> &nbsp;&nbsp;OnCreate

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;OnElementChanged
<br />
<br />
<br />

####  2. What's the most common way to pass data between a Xamarin.Forms View and a custom renderer that requires data passed from the View?


<i class='far fa-square'></i> &nbsp;&nbsp;Standard CLR properties

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Bindable properties

<i class='far fa-square'></i> &nbsp;&nbsp;Public fields
<br />
<br />
<br />

####  3. The Xamarin.Forms renderer has access to both the Xamarin.Forms view and the native view. What's the name of the property in the renderer that provides access to the Xamarin.Forms view?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Element

<i class='far fa-square'></i> &nbsp;&nbsp;Control

<i class='far fa-square'></i> &nbsp;&nbsp;View
<br />
<br />
<br />

####  4. When coding a custom Xamarin.Forms View and custom renderer that require notifications between each other, what's the advantage of using the messaging service?


<i class='far fa-square'></i> &nbsp;&nbsp;More efficient than a direct method call.

<i class='far fa-square'></i> &nbsp;&nbsp;Requires no cleanup code.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Loose coupling between the View and the renderer.
<br />
<br />
<br />
