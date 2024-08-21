# D-Lab Copilot Assisted Coding Workshop

[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab Copilot Assisted Coding Workshop. 

### Prerequisites

Though GitHub Copilot is language agnostic, our examples will be in R. Therefore, we recommend attending D-Lab's [R
Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals) series
prior to this workshop. If you use a language that is not R, you are still welcome to attend. Many of the examples will have analogs in other languages, such as Python.

Check D-Lab's [Learning Pathways](https://dlab-berkeley.github.io/dlab-workshops/python_path.html) to figure out which of our workshops to take!

## Workshop Goals

This workshop provides an introduction to coding with GitHub Copilot. First, we’ll cover how to install and set-up Visual Studio Code, a free code editor through which we will use GitHub Copilot. Then, we will go through the different features of GitHub Copilot and how to use them to help us code in R. 

## Learning Objectives

After this workshop, you will be able to:

1.  Set-up and navigate Visual Studio Code.
   
2.  Take advantage of the main functionalities of GitHub Copilot for coding.
   
3.  Understand some of the strengths and weaknesses of AI coding assistants.

**⚠️ You must have an active subscription to GitHub Copilot to follow the material in this workshop** (you still may attend even if you do not). If you are a student or teacher, you can apply for free Github Copilot (see information [here](copilot_and_vscode_setup.md)); the application is easy, however **it can take a few days to process (GitHub warns it can even take up to two weeks &mdash; though we have found it generally takes 2-3 days)**. Otherwise, you will have to pay for a subscription which starts at $10/month (plans available [here](https://github.com/features/copilot/plans)). If this is your first time using Copilot, you can also start a 30 day free trial.

⚠️ At the start of the workshop we will install R, Visual Studio Code, and the workshop materials from this repository. If you want to do that yourself beforehand, please follow the instructions below.

## Installation Instructions

We will use Visual Studio Code, GitHub Copilot, and R to go through the workshop materials. We will walk through installing and setting up Visual Studio Code during the workshop, but you must have an existing subscription to GitHub Co-pilot and have R installed. 

### Before the workshop:

Follow the instructions [here](copilot_and_vscode_setup.md) to subscribe to GitHub Copilot and [here](https://github.com/dlab-berkeley/R-Fundamentals#installation-instructions) to install R. These instructions also describe setting up GitHub Copilot in Visual Studio Code, but you do not need to complete these steps before the workshop.

### During the workshop (or optionally before):

1.  [Download R](https://www.r-project.org/): Follow the links according
    to the operating system that you are running. Download the package,
    and install R onto your compute. You should install the most recent
    version (at least version 4.3).

2.  [Download Visual Studio Code](https://code.visualstudio.com/): Follow
    the links according to the operating system that you are running. Do this after you have
    already installed R.
   
3. Download these workshop materials:
    * Click the green "Code" button in the top right of the repository information.
    * Click "Download Zip".
    * Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

Detailed installation instructions (including troubleshooting steps) can be found [here](copilot_and_vscode_setup.md). 

## Is Visual Studio Code not Working on Your Computer?

If you do not have Visual Studio Code installed and the materials loaded on your
workshop by the time it starts, we *strongly* recommend using our GitHub codespace to run the materials for these lessons. 

You can create a codespace for this repository:
1. Click the green "Code" button in the top right of the repository information.
   
2. Click "Open with Codespaces".
   
3. Wait for the codespace to load. This may take a few minutes.

The codespace uploads this repository, along with any necessary packages, and
allows you to run the materials in the cloud in a virtual Visual Studio Code that will look basically like what is on your computer.
No installation is necessary from your end, you only need an internet browser. To save your work, the easiest way is to copy and paste
the markdown files into a local file on your computer. If you are comfortable with Git, you can also fork this repository and commit your changes to your fork (instructions [here](https://docs.github.com/en/codespaces/getting-started/understanding-the-codespace-lifecycle#saving-changes-in-a-codespace)). 

**Even if you are using our codespace you must have your own GitHub Copilot subscription; the codespace is linked to your GitHub account.** If you are using a free GitHub account, you automatically get [120 free codespace core-hours per month](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces). This 2 hour workshop should only use 4 core-hours.

## Run the Code

Now that you have all the required software and materials, you need to open the code.

1.  Open Visual Studio Code.
   
2.  Click "Open Folder" in the Visual Studio Code welcome window.
   
3.  Use the file navigator to find the GitHub-Copilot folder you downloaded from Github and click "Open".
   
4.  Open up the `workshop.Rmd` file in the `lessons` folder via the Files panel in Visual Studio Code (left-hand side).
   
5.  The `solutions` folder contains the solutions to the challenge problems.
   
6.  You will need to install the R extension in Visual Studio Code to run any R code and the Copilot extension to use Copilot, which we will walk through in the workshop. If you would like to install them beforehand check out the instructions [here](copilot_and_vscode_setup.md).

# Additional Resources

Check out the following resources to learn more about Visual Studio Code and GitHub Copilot:

* [Overview of Visual Studio Code](https://code.visualstudio.com/docs)
* [Overview of GitHub Copilot in Visual Studio Code](https://code.visualstudio.com/docs/copilot/overview)


# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Contributors

[Anusha Bishop](https://anushapb.github.io/)

*This repository was created with material from the [codespacer](https://github.com/AnushaPB/codespacer/tree/main) GitHub template created by Anusha Bishop*
