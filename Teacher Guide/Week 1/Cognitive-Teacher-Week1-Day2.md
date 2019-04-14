# Cognitive Hackathon: Week 1 - Teacher's Guide
## Day 2

## Overview
Azure Notebooks is the next topic. This is where students will be working during this course.

## Objectives
Get your students hands-on with the coding environment they'll be using for this course: Azure Notebooks. This online implementation of the open source development environment called Jupyter lets the student create projects in Python, debug, and run them without downloading any software: cloud-based software development. The lab will include the creation of a project and files, editing of markdown, and running of code.

## Teacher Demos: Azure Notebooks (30 mins)
Open source development requires a place to work, a code editor that lets you run and debug your apps. Jupyter is a popular editor and we'll be using it, but not the usual way, downloaded onto your PC. We'll use it in the cloud, with Azure Notebooks. Azure Notebooks combines Jupyter with a project organizer that lets you create, edit, and maintain all your projects and files. We'll be using this workstation in the cloud.

Walk through the basics of Azure Notebooks for the class: (details below)

* Create a free Microsoft Account and sign in on the Azure Notebooks website
* Create a new Project
* Create a new Notebook
* Notebook Cells
* Code Cells

Let's begin with creating a free account:

### Teacher Demo: Create a Free Microsoft account and Sign in to Azure Notebooks

Open your browser and head to https://notebooks.azure.com/.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureNotebookStart.png?raw=true "New Project")

Click on "Try It Now" to navigate to Microsoft Azure Notebooks Projects page.

In the upper right-hand corner, click the "Sign In" link, which brings us to the Microsoft login. Use your existing login or "Create one!". This brings you back to the Projects page and you're logged in.

Click on the My Projects link at the top left.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureMyProjects.png?raw=true "New Project")

You'll now be looking at your project list titled "My Projects", which should be empty.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureMyProjectsPage.png?raw=true "New Project")

Note the three greyed-out links, Run, Download and Delete. We'll get to those later.

In the upper-right are Search Projects, Terminal, New Project, and Upload GitHub Repo.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureMyProjectsRight.png?raw=true "New Project")

Now let's create our first project!

### Teacher Demo: Create a new Project

Click on the New Project button in the upper right. This gives you a popup where you can set up your new project.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureCreateNewProject.png?raw=true "New Project")

Give your project a name and an id, a string used for sharing your project. If you want the project to be private then uncheck Public. Click create and your new project will be created.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureMyNewProject.png?raw=true "Create Project")

Within a project, you can create any number of things using the "+" button on the right.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureCreateNotebook.png?raw=true "Add Something")

### Teacher Demo: Create a New Notebook

Click on the "+" button on the upper right menu bar and a popup asks you for the name and programming language an version.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureCreateNotebook2.png?raw=true "Add Notebook")

This creates a new notebook in your project list.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureCreateNotebook3.png?raw=true "Add Notebook to My Project List")

Click on the new Notebook in your project list and a container will be created with an editor and compiler for you to work in, an online workstation.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureCreateContainer.png?raw=true "Edit Notebook")

Here you can edit your notebook, working with cells and editing markdown and Python code.

### Teacher Demo: Notebook Cells

Notebooks are made up of cells.  Cells in this course can contain code and markdown. Headings are specified in markdown cells using one or more number signs, "#",  before your text. Specify what you want in your cells using the 'code' dropdown on the right end of the menu bar.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureNotebookCodeDropdown.png?raw=true "Cell Type Dropdown")

First choose Markdown in the dropdown. This makes the current cell a markdown cell. Enter some markdown: ## My Notebook

You should see "My Notebook" in a larger font, a Title 2.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureNotebookCodeDropdown.png?raw=true "Title 2")

Remove one of the "#" symbols and the text becomes larger, a Title 1.

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/AzureNotebookMarkdown2.png?raw=true "Title 1")

If you type a line without "#" symbols, it will format simply as normal text.


#### Additional Resource
See online markdown guides for explanations of all of the things you can do with markdown, like this one: 
    https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


### Teacher Demo: Code Cells

Change the current cell to a code cell by selecting "code" in the dropdown above. Then type a print statement in Python:

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/HelloEarth1.png?raw=true "Hello Earth")

There are two primary ways to execute your code cell. The first is to click the "Run" button with the play icon in it. The second way is to CTRL+Enter. Run your cell either way and see your output at the bottom of your code cell.

*Specify for a Windows vs Mac vs Chromebook for the shortcut*

![alt text](https://github.com/danhermes/cognitive-hackathon/blob/master/images/Week%201/HelloEarth2.png?raw=true "Hello Earth")

That's how you use Azure Notebooks! Now you can create your own Python projects without downloading or installing software on your computer.


## Student Lab: Azure Notebooks (30 mins)
The students should now do the Azure Notebooks Lab to mirror the demo you just presented.

## Summary 
Today's workshop covered the following topics:
* Create a free Azure Notebooks account
* Create a new Project
* Create a new Notebook
* Notebook Cells
* Code Cells


## Additional Teacher Resources

Here is documentation on Azure Notebooks:
https://docs.microsoft.com/en-us/azure/notebooks/create-clone-jupyter-notebooks