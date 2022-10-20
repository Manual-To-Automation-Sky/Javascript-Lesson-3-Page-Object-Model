# Manual to Automation @ <a href="https://sky.co.uk/"><img src="https://logos-world.net/wp-content/uploads/2021/02/Sky-Logo.png" alt="playwright" height="27" /></a> - Lesson 2 - Exercise Solution

## Introduction

This example code shows a Cypress test running on BrowserStack that fills in a contact form on https://automationexercise.com

## Necessary Tools

There are a few things that you will need before you can get started.

* Cypress - Use [this](https://docs.cypress.io/guides/getting-started/installing-cypress#What-you-ll-learn) multiplatform guide to installing Cypress and [this](https://www.toolsqa.com/cypress/install-cypress/) guide to how to use Cypress and set up projects.
* Git for pulling down the code - follow [this](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) guide for installing Git on all platforms. There are other useful guides on the website mentioned previously. Start [here](https://github.com/git-guides) anad follow through to the various links to learn more about Git. It will be very useful on your automation journey. If you have any issues with tokens or user credentials, let me know as this can trip a lot of people up.
* Visual Studio Code which can be downloaded from [here](https://code.visualstudio.com/download)
* An active BrowserStack account

## Installation

To get the project ready to run on your machine, follow the steps below:

* Open a terminal. (Terminal on Mac, Command Prompt on Windows)
* Go to the directory where you want to place the code using [cd](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cd) for Windows, and it functions mostly the same for Mac. You just use "cd" but the folder structure on Mac is different (/Users/username/Documents instead of C:/Users/username/Documents)
* Copy the following command into the terminal, (remember, you must have [Git](https://git-scm.com/downloads) installed)
```sh
git clone https://github.com/Manual-To-Automation-Sky/Javascript-Lesson-2-Exercise.git.
```
* Move into the directory that you just cloned by typing
```sh
cd Javascript-Lesson-2-Exercise
```
* Run the scripts for single and parallel tests
```sh
npm run single-test
```

```sh
npm run parallel-test
```