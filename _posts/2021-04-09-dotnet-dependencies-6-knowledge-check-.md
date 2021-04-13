---
    layout: post
    title: Create a new .NET project and work with dependencies 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/dotnet-dependencies/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/dotnet-dependencies.svg">
####  1. How would you install a framework like Humanizer?


<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet add Humanizer

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run dotnet add package Humanizer

<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet install Humanizer

<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet download package Humanizer
<br />
<br />
<br />

####  2. What version change would signify a minor version when a package uses semantic versioning?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;1.1.1 changes to 1.2.0

<i class='far fa-square'></i> &nbsp;&nbsp;1.0.1 changes to 1.0.2

<i class='far fa-square'></i> &nbsp;&nbsp;1.0.0 changes to 2.0.0
<br />
<br />
<br />

####  3. How do you configure a project file so that you get only patch (bug fix) updates?


<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in the project file and set the entry to look like this one: <PackageReference Include="<package>" Version="*"/>

<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in the project file and set the entry to look like this one: <PackageReference Include="<package>" Version="2.*"/>

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Locate the entry in the project file and set the entry to look like this one: <PackageReference Include="<package>" Version="2.7.*"/>

<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in the project file and set the entry to look like this one: <PackageReference Include="<package>" Version="[6,7)"/>
<br />
<br />
<br />

####  4. How would you check if a new version of a framework is available?


<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet list outdated

<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet list package outdated

<i class='far fa-square'></i> &nbsp;&nbsp;Run dotnet list --outdated

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run dotnet list package --outdated
<br />
<br />
<br />
