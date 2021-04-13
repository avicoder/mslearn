---
    layout: post
    title: Maintain a secure repository by using GitHub best practices 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/maintain-secure-repository-github/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/github/maintain-secure-repository-github.svg">
####  1. What is the best way to make sure you're integrating the most secure versions of your project dependencies?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure your package files to always use the latest versions of dependencies.

<i class='far fa-square'></i> &nbsp;&nbsp;Check each project's security details closely before adding it to your dependencies by confirming its version status across multiple advisory sites.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Enable Dependabot for your repository.
<br />
<br />
<br />

####  2. Suppose one of your source projects relies on secrets kept in a folder called .secrets. You would like to make sure that the files kept in this folder on development machines are not inadvertently committed to the repository. Which of these files will best help enforce this policy?


<i class='far fa-square'></i> &nbsp;&nbsp;SECURITY.md

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;.gitignore

<i class='far fa-square'></i> &nbsp;&nbsp;CONTRIBUTING.md
<br />
<br />
<br />

####  3. Suppose someone has inadvertently committed a sensitive API key stored in the .secrets folder. What is the correct way to scrub that information from GitHub?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use git to remove the unwanted commit and update historical references. Then contact GitHub support to run garbage collection and invalidate the Git cache.

<i class='far fa-square'></i> &nbsp;&nbsp;Delete the sensitive file from GitHub. Then commit an empty file to the same location to overwrite it.

<i class='far fa-square'></i> &nbsp;&nbsp;This is a trick question. Once you commit something to GitHub, it lives forever. That's why globally unique hashes are used to identify everything.
<br />
<br />
<br />
