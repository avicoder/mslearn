---
    layout: post
    title: Prepare to publish your Xamarin app - Publish your application
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/prepare-to-publish-your-xamarin-application/6-publish-your-application/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/xamarin/prepare-to-publish-your-xamarin-application-badge.svg">
####  1. The Mono.Cecil Linker used with Android and iOS apps can be aggressive when linking an assembly. What should you use to specify methods, properties, and types that need to be preserved?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Code attributes like Preserve.

<i class='far fa-square'></i> &nbsp;&nbsp;Build flags passed to the Linker through your .csproj file.

<i class='far fa-square'></i> &nbsp;&nbsp;XML comments added to your source code.
<br />
<br />
<br />

####  2. To use PreserveAttribute in a .NET Standard library, you need to:


<i class='far fa-square'></i> &nbsp;&nbsp;Just apply it to your code. It's available automatically.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a reference to the Xamarin.Core assembly to get access to the type.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a custom type named PreserveAttribute that derives from System.Attribute.
<br />
<br />
<br />

####  3. After you build a distribution package, publishing a Xamarin.iOS, Xamarin.Android, or UWP app is vendor-specific and performed through the vendor's tools and website.


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;True

<i class='far fa-square'></i> &nbsp;&nbsp;False
<br />
<br />
<br />
