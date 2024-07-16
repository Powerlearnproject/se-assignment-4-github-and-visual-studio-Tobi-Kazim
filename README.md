[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15357892&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
ANSWER

Github is a developer platform that allows developers to create, store, manage and share their code.

It is commonly used to host open source software development projects.

History:
This platform existed as of 2007 but started in February, 2007 and was developed by Chris Wanstrath, P.J.Hyett and Tom Preston-Werner. The company is located in San Francisco.

What are its primary function?
a) Hosting and sharing your code with others.

b) Tracking and assigning issues to maintain an organized workflow.

c) Managing pull requests to review and incorporate changes into your project.

d) Creating your own website using Github Pages; a static site hosting service.

e) Collaborating with others on projects, making it an excellent tool for open-source contributions.

what are it features?
a) Create a repository

b) Create a branch

c) Make changes to a file

d) Stage changes

e) Commit changes

f) Push changes to a remote repository

g) Merge changes

h) Revert changes

i) Delete a branch

How it supports collaborative software development?
a) Forking a Repository: Creating a copy of a project under your Github account, to be enabled to freely make changes without affecting the original repository.

b) Cloning a Repository: Creating a local copy on your machine, allowing you to work on the codebase. One uses the following command "git clone <repository-url>".

c) Making changes and Creating Branches: This is done after cloning the repository. Then to create a new branch for each new feature or bug fix. To create a branch "git checkout -b <branch-name>".

d) Pushing Changes and Making a Pull Request: Once you have committed your changes, it's time to push them to your forked repository on GitHub. This allows others to review and collaborate on your changes. One uses the following command "git push origin <branch-name>".

e) Resolving Conflicts: It requires careful attention and coordination. You resolve conflicts by editing the conflicting files. Once, resolved, commit the changes locally, then push the changes to your branch on GitHub.

f) Reviewing and Merging Pull Requests: You consider the following:
- Read the description and understand the proposed changes.

- Review teh code changes and ensure they align with project standards.

- Test the changes locally, if applicable.

- Provide constructive feedback and suggestions for improvement.

- Once satisfied, click on the Merge pull request button to merge the changes into the main repository.

In conclusion, GitHub offers an exceptional platform for collaborative software development.


Citation: 

https://en.wikipedia.org/wiki/GitHub

https://www.freecodecamp.org/news/guide-to-git-github-for-beginners-and-experienced-devs/

https://dev.to/pratik_kale/collaborating-with-others-on-github-3260


Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

ANSWERS

A GitHub Repository is a place where you can store your code, your files, and each file's revision history. It can have multiple collaborators and can be either public or private.

To create a new repository for the web UI:

a) Go to the upper-right corner of any page, select "+", then click "New repository".

b) Use the Owner dropdown menu to select the account you want to own the repository.

c) Type a name for your repository,and an optional description.

d) Choose a repository visibility.

e) Click Create repository.

The essential elements that should be included in it:

- Creating a README file

- Creating a ".gitignore" file

- Choose to add a software license for your project

Citation:
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

ANSWERS

Version control is a piece of software used to track revisions, solve integration conflicts in code, and manage different artifacts involved in software projects (e.g. design, data, images).

It also enables frictionless communication, change,and reproducibility between developers and other team members.

It enables one to track and merge branches, audit changes, and enable concurrent work to accelerate software delivery.

Git has the adaptability, speek, and stability required to thrive in fast-paced markets. Hence, developers and software development teams use Git for version control. 

Git's ability to store a complete history of a project locally is a benefit, because Git branches are lightweight and the protocol is fast, so contributors can be anywhere, even with poor/bad connections and still sync a local copy with any other team member.

Some of the benefits of Giot and a distributed version control system:

a) Workflow flexibility: Here, teams can work together using various branching strategies that are not as possible in other version control systems. Some of the most popular Git workflows include "centralized", "feature branching", "trunk-based development", and "Gitflow".

b) Speed: It is fast. Users have a local repository on their machine with a full history, so there's no lag in communicating with a server, which is an experience that users of centralized systems, such as CVS, Subversion, and Perforce, often encounter.

c) Reliability: Here, Git inherently has multiple backups, because each user has a local repository. If there's a crash, a copy could replace the main server.

d) Colllaboration: Here, Git makes collaborative development easy with its branching model. People on your team can create a branch, experiment, and merge the code to the main branch if it works well.

How does GitHub enhance version control for developer?

It enhances version control for developers by:

a) Collaboration
b) History Tracking
c) Code Backup
d) Code Reusability

Citation: 
https://about.gitlab.com/topics/version-control/what-is-git-version-control/

https://dev.to/saloman_james/a-comprehensive-guide-to-version-control-with-git-and-github-3m0n


Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

ANSWER

Branches in GitHub are a feature that allows you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

It is used to isolate development work without affecting other branches in the repository. You can then work on this new branch in isolation from changes that other people are making to the repository. A branch you create to build a feature is commonly referred to as a feature branch or topic branch. 

GitHub creates the repository with a single branch. This first branch in the repository is the default branch. The default branch is also the initial branch that Git checks out locally when someone clones the repository. By default, GitHub names the default branch "main" in any new repository.

The Process of creating a branch:

To create a new branch based on the current HEAD,

- use the command "git checkout -b new-branch-name" with "new-branch-name" been your desired branch name

To create a new branch based on an Existing branch,

- Switch to the existing branch

- Create the new branch using "git checkout -b new-branch-name" with "new-branch-name" been your desired branch name

To create a new branch from a specific commit,

- Create the new branch using "git checkout -b new-branch-name commit-hash" with "new-branch-name" been your desired branch name

To create a new branch from a specific tag,

- Create the new branch using "git checkout -b new-branch-name tag name" with "new-branch-name" been your desired branch name

To create a new branch from a remote branch,

- Firstly, fetch the remote branch using the command "git fetch origin"

- Create the new branch using "git checkout -b new-branch-name origin/remote-branch-name" with "new-branch-name" been your desired branch name and "remote-branch-name" the name of the remote branch.

To create a new branch in a remote repository,

- After creating a new branch locally, you push it to the remote repository to share it with others. You use the command "git push origin new-branch-name" with "new-branch-name" been your desired branch name.

How to merge a Branch:

We have the emergency-fix ready, and so let's merge the main and emergency-fix branches using the command "git merge emergency-fix".

Example:

EXERCISE 1:

<!DOCTYPE html>
<html>
<head>
<title>Hello World!</title>
<link rel="stylesheet" href="bluestyle.css">
</head>
<body>

<h1>Hello world!</h1>
<div><img src="img_hello_world.jpg" alt="Hello World from Space" style="width:100%;max-width:960px"></div>
<p>This is the first file in my new Git Repo.</p>
<<<<<<< HEAD
<p>This line is here to show how merging works.</p>
=======
<p>A new line in our file!</p>
<div><img src="img_hello_git.jpg" alt="Hello Git" style="width:100%;max-width:640px"></div>
>>>>>>> hello-world-images

</body>
</html>

EXERCISE 2:

<!DOCTYPE html>
<html>
<head>
<title>Hello World!</title>
<link rel="stylesheet" href="bluestyle.css">
</head>
<body>

<h1>Hello world!</h1>
<div><img src="img_hello_world.jpg" alt="Hello World from Space" style="width:100%;max-width:960px"></div>
<p>This is the first file in my new Git Repo.</p>
<p>This line is here to show how merging works.</p>
<div><img src="img_hello_git.jpg" alt="Hello Git" style="width:100%;max-width:640px"></div>

</body>
</html>

SOLUTION:

git add index.html
git status
On branch master/main,
All conflicts fixled but you are still merging.
    (use "git commit" to conclude merge)

Changes to be committed:
    new file: img_hello_git.jpg
    new file: img_hello_world.jpg
    modified: index.html



Citation: 
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

https://www.geeksforgeeks.org/how-to-create-a-new-branch-in-git/

https://www.w3schools.com/git/git_branch_merge.asp

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

ANSWER

A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes in the main codebase.

You can create pull requests on GitHub.com, with GitHub Desktop, in GitHub Codespaces, on GitHub Mobile, and when using GitHub CLI.

Collaborating on repositories with code quality features

Workflow quality features like statuses, protected branches, and required status checks help collaborators make contributions that meet conditions set by organization and repository administrators.

In the shared repository model, collaborators are granted push access to a single shared repository and topic branches are created when changes need to be made.

Pull requests are useful in this model as they initiate code review and general discussion about a set of changes before the changes are merged into the main development branch. This model is more prevalent with small teams and organizations collaborating on private projects.

Steps to create a pull request:

1) Create a new git branch to work locally using the following command "git -b BRANCH_NAME"

2) Implement changes and push them frequently (so that they do not get lost) using the following command 
"git add NAME_OF_THE_FILE"
"git commit -m "DESCRIBE YOUR RECENT CHANGES"

3) After you have finished the implementation and committed your changes locally, you should get the latest changes from the shared repository to ensure there are no conflicting changes. 

You can get the latest changes using the following command "git pull origin BRANCH_NAME"

4) Push your changes to the remote repository using the following command "git push --set-upstream-to origin REMOTE_BRANCH_NAME"


Citation:
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models

https://developer.nvidia.com/blog/benefits-of-using-pull-requests-for-collaboration-and-code-review/

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

ANSWER

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.

You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

How the GitHub Actions can be used to automate workflows:

You can configure a GitHub Actions workflow to be triggered when an event occurs in your repository, such as a pull request being opened, to deploy your application every time a release is created or an issue being created. 

Workflows are a configurable automated process that will run one or more jobs. They are defined in the ".github/workflows" directory in a repository, and a repository can have multiple workflows, each of which can perform a different set of tasks.

A Job is a set of steps in a workflow that is executed on the same runner. Each step is either a shell script that will be executed, or an action that will be run.

GitHub Actions uses YAML syntax to define the workflow. Each workflow is stored as a separate YAML file in your code repository, in a directory named ".github/workflows".

A Simple CI/CD pipeline using GitHub Actions:

A) Create the directory that has the YAML-formatted files:
    mkdir -p .github/workflows
    cd .github/workflows

B) Create a workflow to run our tests whenwe open a new pull request:
    touch test.yml

C) Add Actions configuration to the file:
    
    yaml
name: Animal Farm NodeJS CI
on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - name: Checkout repository
      uses: actions/checkout@v2
    - name: Use Node.js
      uses: actions/setup-node@v1
      with:
        node-version: '18.x'
    - name: Run Yarn 
      run: yarn
    - name: Run tests
      run: yarn test

D) Define when the workflow runs:
    It is done in the "on" block.


Citation:
https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions

https://medium.com/@michaelekpang/creating-a-ci-cd-pipeline-using-github-actions-b65bb248edfe

https://github.com/readme/guides/sothebys-github-actions

Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

ANSWER

Visual Studio is an integrated development environment (IDE) developed by Microsoft. It is used to develop computer programs including websites, web apps, web services and mobile apps.

It includes a code editor supporting IntelliSense (the code completion component) as well as code refactoring.

It was first released in 1997 by Microsoft.

Video Studio supports 36 different programming languages and allows the code editor and debugger to support (to varying degrees) nearly any programming language, provided a language-specific service exists.

It's key features include:

a) A Code Editor: It supports syntax highlighting and code completion using IntelliSense for variables, functions, methods, loops, and LINQ queries.

b) A Debugger: It works both as a source-level debugger and as a machine-level debugger.

c) Tesing tools: It aids in the development of applications. These include Unit testing, IntelliTest, Live Unit Testing, Test Explorer, CodeLens test indicators, code coverage analysis, Fakes.


How Visual Studio differs from Visual Studio code?

Visual Studio Code is an open-source and lightweight text editor available on Windows, Mac, and Linux.

Citation:
Visual Studio. (2024, July 10). In Wikipedia. https://en.wikipedia.org/wiki/Visual_Studio

https://www.freecodecamp.org/news/visual-studio-vs-visual-studio-code/


Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

ANSWER

Step 1: Open Visual Studio

Step 2: Open the account settings
Go to File > Account Settings

Step 3: Add an account and Select GitHub

Step 4: Sign in with your GitHub credentials

Step 5: After the password authorization, the below message will be visible

Step 6: Now, we can see the linked GitHub account in Visual Studio in account settings.

From here we can create, clone, and push to the repository in GitHub. We can manage repositories, branches, commits and sync changes.

The integration enhances the development workflow with the aid of GitHub Actions by integrating CI/CD workflows.

Citation:
https://www.geeksforgeeks.org/how-to-link-github-with-visual-studio/


Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

ANSWER

Here are some key debugging tools available in Visual Studio, along with how developers can use them:

1. Breakpoints
Breakpoints allow you to pause the execution of your code at specific lines. This lets you inspect the state of your application at that point.

Setting Breakpoints: Click in the margin next to a line of code or press F9.
Conditional Breakpoints: Right-click on a breakpoint and select "Conditions" to specify conditions under which the breakpoint should be hit.
Hit Count: Set how many times a breakpoint should be hit before pausing execution.
2. Watch Window
The Watch Window lets you monitor the values of variables and expressions as you step through your code.

Adding Variables: Drag and drop a variable into the Watch Window or type the variable name directly.
Complex Expressions: You can also add complex expressions to evaluate their results.
3. Locals Window
The Locals Window displays variables that are in the current scope, showing their names, values, and types.

Automatic Updates: The values update automatically as you step through the code.
4. Autos Window
The Autos Window shows variables used in the current line of code and the preceding line.

Context-Sensitive: This window automatically updates based on the current context in your code.
5. Immediate Window
The Immediate Window allows you to execute code and evaluate expressions during debugging.

Evaluate Expressions: Type and evaluate expressions to see their values.
Execute Commands: Run commands or call functions to test their outcomes.
6. Call Stack Window
The Call Stack Window displays the sequence of function calls that led to the current point in execution.

Navigate Call Stack: Double-click on a function call to navigate to its source code.
Analyze Call Order: Understand the order of function calls and identify where issues might have originated.
7. Exception Settings
Exception Settings allow you to configure how exceptions are handled during debugging.

Break on Exceptions: Configure Visual Studio to break execution when exceptions are thrown, even if they are caught.
Exception Types: Specify which types of exceptions to break on.
8. Step Into, Step Over, Step Out
These commands control the execution flow of your program during debugging.

Step Into (F11): Move into the function call.
Step Over (F10): Execute the function call without stepping into it.
Step Out (Shift+F11): Continue execution until the current function returns.
9. Data Tips
Data Tips are pop-up windows that appear when you hover over a variable during a debugging session.

Quick Inspection: Hover over variables to see their values and types.
Pin Data Tips: Pin them to keep track of important values.
10. IntelliTrace
IntelliTrace (available in higher editions) provides historical debugging by recording your application's execution history.

Historical Debugging: Navigate back in time to see the state of variables and the call stack at different points in execution.
Event Timeline: View a timeline of events to understand the sequence of operations.
11. Diagnostic Tools Window
The Diagnostic Tools Window provides real-time data on performance and memory usage during debugging sessions.

Memory Usage: Analyze memory consumption and detect memory leaks.
CPU Usage: Identify performance bottlenecks by examining CPU usage.
Using These Tools to Identify and Fix Issues
Set Breakpoints at suspected problematic lines of code to pause execution and inspect the state.
Step Through Code using Step Into, Step Over, and Step Out to follow the program's execution flow.
Monitor Variables in the Watch, Locals, and Autos windows to see how values change.
Use Data Tips to quickly inspect variable values by hovering over them.
Check the Call Stack to understand the sequence of function calls and trace back to the origin of an issue.
Evaluate Expressions in the Immediate Window to test hypotheses and execute code snippets.
Handle Exceptions using Exception Settings to break on specific exceptions and diagnose issues early.
Analyze Performance and memory usage using the Diagnostic Tools Window to identify and address performance issues.
Use IntelliTrace to go back in time and inspect the state of the application at previous points in execution.
By leveraging these tools, developers can effectively debug their applications, identify issues, and implement fixes, leading to more robust and reliable software.


Citation: 
https://chatgpt.com/c/6fe6f56b-74b4-4a5d-bf40-4a1e75f204a6

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

ANSWER
a) Clone and code from within the IDE: One can clone the repo down to their local machine to start committing and pushing.

b) Create and push new repos: Visual Studio handles the local and remote repository creation.

c) Branching, Staging and Committing: Create and switch between branches from the status bar. View your changes, stage the files you want to commit, and make commits with GitHub issue search in the Git Changes tool window.

d) Merge and Rebase: Merge or rebase branches after completing features directly from within Visual Studio.

e) Create a Pull Request: You can add your title, description with Markdown support, reviewers, and see your changes summarized all at once inside Visual Studio.

f) Resolve merge conflicts: Visual Studio will recognize merge conflicts right when they occur, and show you the unmerged changes in the Git Changes window.

A real-world example of a project:

Setting up the project
Let’s install the dependencies we need. We will be using Express for our application and Jest and SuperTest for testing the application:

npm install express 
npm install jest supertest --save-dev
Creating the application and adding tests
Next, we add index.js and app.js files to an src directory. In your terminal, run the following commands:

mkdir src
cd src
touch index.js app.js app.test.js
Open the created app.js file and add the following code.

const express = require("express");
const app = express();

app.get("/test", (_req, res) =>  {
  res.status(200).send("Hello world")
})
module.exports = app;
In the index.js file, add this code:

const app =  require( "./app");
const port = process.env.PORT || 3000;

app.listen(port, () =>
  console.log('Example app listening on port 3000!'),
);
Let’s also add a test for the endpoint we just created. In the app.test.js, add the following code:

const app = require("./app")
const supertest = require("supertest")
const request = supertest(app)

describe("/test endpoint", () => {
    it("should return a response", async () => {
        const response = await request.get("/test")
        expect(response.status).toBe(200)
        expect(response.text).toBe("Hello world");
    })
})
In the package.json file, add the start and test scripts to the scripts:

"scripts": {
    "start": "node src",
    "test": "jest src/app.test.js"
}
Run npm start and npm test to ensure that everything works as expected.

Setting up the workflow
Let us get back to our GitHub workflow we pulled from our repository: the main.yml file, or whatever you named yours. We will modify this file to build the application and run tests whenever a pull request is merged to the main branch, and deploy this application to Heroku.

So in that file, change:

# Controls when the workflow will run
on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]
To this:

on:
  push:
    branches: [ main ]
Since we are building a Node application, we need an action to set up Node.js for build. We do not need to build this from scratch since this action is already available in the GitHub Marketplace. So we go to GitHub Marketplace to find an action we can use.

On GitHub, click on Marketplace in the top navigation. Search for Node and you see a Setup Node.js Environment action under Actions.

GitHub Setup Node.js Environment

Click on it to see a description of the action and how to use it. You will see this screen with a description.

Setup Node.js Environment Description

We are going to replace the steps in our workflow with the steps here.

So we replace this code:

  # Steps represent a sequence of tasks that will be executed as part of the job
    steps:
      # Checks-out your repository under $GITHUB_WORKSPACE, so your job can access it
      - uses: actions/checkout@v2

      # Runs a single command using the runners shell
      - name: Run a one-line script
        run: echo Hello, world!

      # Runs a set of commands using the runners shell
      - name: Run a multi-line script
        run: |
          echo Add other actions to build,
          echo test, and deploy your project.
With this:

steps:
  - uses: actions/checkout@v2
  - uses: actions/setup-node@v2
    with:
      node-version: '14.x'
  - run: npm install
  - run: npm test
We can make it more understandable by adding names to the steps:

steps:
    - uses: actions/checkout@v2
    - name: Use Node.js
      uses: actions/setup-node@v2
      with: 
        node-version: "14.x"

    - name: Install dependencies
      run: npm install

    - name: Run test
      run: npm test
At this point, if we push this to our main branch, we will see this action run. But because we want to go a step further to add automatic deployment to Heroku, we will add a second job to our workflow.


Citation:
https://visualstudio.microsoft.com/vs/github/

https://blog.logrocket.com/ci-cd-node-js-github-actions/


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
