---
    layout: post
    title: Build dual-screen Xamarin.Forms apps by using TwoPaneView - Detect and respond to spanning/unspanning the app
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/xamarin-forms-dual-screen/4-span-unspan/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/xamarin/xamarin-forms-dual-screen-badge.svg">
####  1. The DualScreenInfo PropertyChanged event will be called:


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When the device is rotated, folded/unfolded, or the app is spanned or unspanned.

<i class='far fa-square'></i> &nbsp;&nbsp;Only when the device is rotated so that the app's orientation is changed.

<i class='far fa-square'></i> &nbsp;&nbsp;Only when app is moved from one to two screens (or vice versa), such as when folded/unfolded or spanned/unspanned.
<br />
<br />
<br />

####  2. What control should you use to show content side by side on a dual-screen device?


<i class='far fa-square'></i> &nbsp;&nbsp;Only TwoPaneView can properly render your layouts across two screens.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can use DualScreenInfo to detect the hinge and screen coordinates and adjust any layout for two screens.
<br />
<br />
<br />
