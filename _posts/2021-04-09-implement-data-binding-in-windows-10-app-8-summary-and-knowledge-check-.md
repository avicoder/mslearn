---
    layout: post
    title: Implement data binding in your Windows 10 application - Summary and knowledge check
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-data-binding-in-windows-10-app/8-summary-and-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/windows-10-ui-and-data.svg">
####  1. What is data binding?


<i class='far fa-square'></i> &nbsp;&nbsp;A method of connecting your app to a database.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A way to transfer data between the UI and the application's code.

<i class='far fa-square'></i> &nbsp;&nbsp;Making sure that data does not change.
<br />
<br />
<br />

####  2. Which interface do you have to implement to reflect the change of a C# property on the UI?


<i class='far fa-square'></i> &nbsp;&nbsp;System.Collections.Specialized.INotifyCollectionChanged

<i class='far fa-square'></i> &nbsp;&nbsp;System.ComponentModel.IReflectPropertyChanges

<i class='far fa-square'></i> &nbsp;&nbsp;NotifyPropertyChanged

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;System.ComponentModel.INotifyPropertyChanged
<br />
<br />
<br />

####  3. What do you have to do to transfer text entered in a text box to a C# string property through data binding?


<i class='far fa-square'></i> &nbsp;&nbsp;Define the binding in XAML with Mode=OneWay.

<i class='far fa-square'></i> &nbsp;&nbsp;Define the binding in XAML with Mode=OneWay, and implement INotifyPropertyChanged in code.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Define the binding in XAML with Mode=TwoWay.

<i class='far fa-square'></i> &nbsp;&nbsp;Define the binding in XAML with Mode=TwoWay, and implement INotifyPropertyChanged in code.
<br />
<br />
<br />

####  4. What do you need to do to display the objects stored in an IEnumerable collection in a list box?


<i class='far fa-square'></i> &nbsp;&nbsp;implement the System.Collections.Specialized.INotifyCollectionChanged interface, and bind the ItemsSource of the ListBox to the collection.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Bind the ItemsSource of the ListBox to the collection.

<i class='far fa-square'></i> &nbsp;&nbsp;Implement the System.ComponentModel.INotifyPropertyChanged interface, and bind the ItemsSource of the ListBox to the collection.
<br />
<br />
<br />

####  5. You're adding items to your collection while the app is running. How do you make the UI reflect these changes?


<i class='far fa-square'></i> &nbsp;&nbsp;Implement the System.ComponentModel.INotifyPropertyChanged interface, and raise the PropertyChanged event every time a new item has beed added to the collection.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the System.Collections.ObjectModel.ObservableCollection<T> class to store the collection of items.

<i class='far fa-square'></i> &nbsp;&nbsp;Implement the System.Collections.Specialized.INotifyCollectionChanged interface in your logic class, and raise the CollectionChanged event every time a new item has beed added to the collection.
<br />
<br />
<br />
