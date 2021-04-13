---
    layout: post
    title: Enhance the user interface of your Windows 10 app - Summary and knowledge check
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/enhance-ui-of-windows-10-app/4-summary-and-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/windows-ui-navigation-media.svg">
####  1. What's the easiest way to pass information between pages in a Windows app?


<i class='far fa-square'></i> &nbsp;&nbsp;Record the information in the app's code before you leave the first page, and read it from the same location when you load the second page.

<i class='far fa-square'></i> &nbsp;&nbsp;Information can't be passed between pages in an app.

<i class='far fa-square'></i> &nbsp;&nbsp;You must use specific navigation methods to pass data between pages.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can pass additional information into the Frame.Navigate method, and the information will be passed to the target page.
<br />
<br />
<br />

####  2. How does the Navigate method of a WebView or WebBrowser control work?


<i class='far fa-square'></i> &nbsp;&nbsp;Navigate directs the control to a web page to display.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Navigate tells the control where to find valid HTML content, and the control displays the content.

<i class='far fa-square'></i> &nbsp;&nbsp;Navigate tells the control where to find valid HTML content, but not to display it.

<i class='far fa-square'></i> &nbsp;&nbsp;Navigate controls backward and forward movement in the control.
<br />
<br />
<br />

####  3. In UWP, the MediaElement control has a CurrentStateChanged event that doesn't exist in WPF. What does this event let you do?


<i class='far fa-square'></i> &nbsp;&nbsp;CurrentStateChanged lets you track the status of your MediaElement control.

<i class='far fa-square'></i> &nbsp;&nbsp;CurrentStateChanged enables you to use transport controls like streaming and timeline.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;CurrentStateChanged lets you consolidate all the code about your MediaElement's status into a single event handler.

<i class='far fa-square'></i> &nbsp;&nbsp;CurrentStateChanged enables you to react to buffering events.
<br />
<br />
<br />
