---
    layout: post
    title: Automate GitHub by using GitHub Script 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/automate-github-using-github-script/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/github/automate-github-using-github-script.svg">
####  1. What is GitHub Script?


<i class='far fa-square'></i> &nbsp;&nbsp;A programming language that compiles to JavaScript.

<i class='far fa-square'></i> &nbsp;&nbsp;An automation syntax for GitHub Shell.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A workflow action that enables GitHub API access from GitHub Actions.
<br />
<br />
<br />

####  2. What is the difference between GitHub Script and GitHub Actions?


<i class='far fa-square'></i> &nbsp;&nbsp;GitHub Actions is for automating build and release pipelines. It was written in the GitHub Script programming language.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;GitHub Actions is a workflow engine that automates the execution of actions. GitHub Script is one of the actions available for use in a workflow.

<i class='far fa-square'></i> &nbsp;&nbsp;GitHub Actions automates workflows that run inside GitHub. GitHub Script automates workflows that run outside of GitHub.
<br />
<br />
<br />

####  3. Why would someone use the following YAML in a GitHub Script action: if: contains(github.event.issue.labels.*.name, 'bug')?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To ensure that the script only runs when the target issue has been labeled as a bug.

<i class='far fa-square'></i> &nbsp;&nbsp;To make sure that new issue names do not violate the bug reporting policy when created.

<i class='far fa-square'></i> &nbsp;&nbsp;To automatically flag any commits containing code matching the github.event.issue.labels.*.name namespace pattern as a bug.
<br />
<br />
<br />
