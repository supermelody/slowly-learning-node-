<h2> Notes on learning Node through an OSX Terminal</h2>
<h3>Objectives</h3>

1. Understand the Patchwork Sourcecode enough to make useful changes
1. Create a basic NodeJS Project to share and update on Github

1. Run your application with your very own Scuttlebot server.

<h4>Ingredients</h4>

* Terminal
* Github
* Vim or Atom or Brackets
* NodeJS
* NPM
* NVM
* Hackmd

<h3>1. Patchwork </h3> 

To download patchwork to your computer you can use this line in the terminal  
<code> git clone https://github.com/ssbc/patchwork </code>
or get the zip from the [repo.](https://github.com/ssbc/patchwork)  

After navigating to the /patchwork forder run 
`npm install`
This will scan the folder and install all dependant packages hence the name 'node package manager'



<h3> 2. Creating a Node Project on Github </h3>

Github is used to store, update, collaborate and discuss growing projects which are refered to as repositories or repos. Git keeps a log of all 'pushed' changes and improvements so all co-developers or just users can be updated. 

Github files can be accessed via the website or github desktop but the coolest way is directly through the terminal. `git init`


Node projects come as collections of files which connect with one another but there are also external files they depend on which need to be installed  thats where NPM comes in. 

When you [install node](https://nodejs.org/en/) it will come with npm but to avoid admin issues also [install NVM](https://github.com/creationix/nvm) 

Create a readme.md in a markdown viewer like [hackMD](hackMD.io) 
Its a document filled with special formatting so it looks good on the github repo page and is filled with vital info like how to install. This will be the first file in your project folder.




<h4>A growing list of helpful Commands for navigating your machine with the terminal:</h4>

|||
|---|---|
|`PWD` | Present working directory|
|`cd ~` |return home |
|`ls` | list the items in the folder |
|`cd docs` | current directory change to docs |
|`cd ..` | move one folder up (note the space two dots)|
|`mkdir album` | make directory / folder called 'album'|
|`touch` | make a file |








