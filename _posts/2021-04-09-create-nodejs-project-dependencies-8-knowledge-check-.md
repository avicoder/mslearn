---
    layout: post
    title: Create a new Node.js project and work with dependencies 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-nodejs-project-dependencies/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/create-nodejs-project-dependencies.svg">
####  1. How would you install a test framework like Jest?


<i class='far fa-square'></i> &nbsp;&nbsp;Run npm install jest

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run npm install jest --save-dev

<i class='far fa-square'></i> &nbsp;&nbsp;Run npm install jest --save

<i class='far fa-square'></i> &nbsp;&nbsp;Run npm download jest --save-dev
<br />
<br />
<br />

####  2. What is the main reason to use npx?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The dependency is downloaded directly into the Node.js process and is removed after the command is run. This tool is great for when you want to run commands infrequently.

<i class='far fa-square'></i> &nbsp;&nbsp;Installing dependencies by using npx is more secure than installing them globally.

<i class='far fa-square'></i> &nbsp;&nbsp;Installing dependencies by using npx is faster than installing them globally.

<i class='far fa-square'></i> &nbsp;&nbsp;You don't have to use sudo before running it as you would for a global installation.
<br />
<br />
<br />

####  3. How do you configure a package.json file so that you get only patch (bug fix) updates?


<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in dependencies or devDependencies. Set the entry to look like this one: "<library>": "*"

<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in dependencies or devDependencies. Set the entry to look like this one: "<library>": "1.x.0"

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Locate the entry in dependencies or devDependencies. Set the entry to look like this one: "<library>": "1.0.x"

<i class='far fa-square'></i> &nbsp;&nbsp;Locate the entry in dependencies or devDependencies. Set the entry to look like this one: "<library>": "^1.0.x"
<br />
<br />
<br />

####  4. What are some recommended scripts to set up in a package.json at the start of a project?


<i class='far fa-square'></i> &nbsp;&nbsp;start, test, build

<i class='far fa-square'></i> &nbsp;&nbsp;start, test

<i class='far fa-square'></i> &nbsp;&nbsp;start

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;start, test, lint, build
<br />
<br />
<br />
