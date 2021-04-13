---
    layout: post
    title: Use a Docker container as a development environment with Visual Studio Code 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/use-docker-container-dev-env-vs-code/10-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/use-docker-container-dev-env-vs-code.svg">
####  1. When you add a dev container configuration to a project, how do you open that project in the container?


<i class='far fa-square'></i> &nbsp;&nbsp;The project automatically opens in the container.

<i class='far fa-square'></i> &nbsp;&nbsp;Select Add Development Configuration Files from the Command Palette.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the Reopen in Container option in Visual Studio Code.

<i class='far fa-square'></i> &nbsp;&nbsp;Start the project from the terminal.
<br />
<br />
<br />

####  2. When you start a web project in a container, how do you access it from the browser?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the port forwarding feature of dev containers.

<i class='far fa-square'></i> &nbsp;&nbsp;Open a browser instance in the container.

<i class='far fa-square'></i> &nbsp;&nbsp;Access it the same way as you would any other web project or URL.

<i class='far fa-square'></i> &nbsp;&nbsp;Expose the port in the Dockerfile.
<br />
<br />
<br />

####  3. How would you install additional software in a container so that it's saved as part of the configuration?


<i class='far fa-square'></i> &nbsp;&nbsp;Use an apt-get command in the devcontainer.json file's postSetupCommand option.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the apt-get command in the Dockerfile's postSetupCommand option.

<i class='far fa-square'></i> &nbsp;&nbsp;Install the software after the container loads via the terminal.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add a RUN apt-get command in the Dockerfile.
<br />
<br />
<br />
