# Mini Tech Watch  
## Topic: GitHub Actions

## Sources Used  
- Official GitHub Documentation  
- GitHub Blog Articles  

## What I Learned  
GitHub Actions is an automation system built directly into GitHub.  
Its purpose is to automatically run tasks whenever something happens in a repository, such as a push, a pull request, or creating a tag.

These tasks can include:  
- running tests  
- checking code quality  
- deploying an application  
- executing scripts after each update  

All of this is defined in YAML workflows and executed by runners, which are machines that perform the tasks automatically.

## Why It Matters for Developers  
GitHub Actions makes many daily development tasks easier and more efficient:

- tests can run automatically  
- deployments become simpler (Laravel, Node.js, React, etc.)  
- code remains clean, stable, and reliable  
- repetitive work is eliminated  
- it aligns developers with modern CI/CD practices used by professional teams  

In short, it improves speed, consistency, and professionalism in any project.

## Simple Example  
In a Laravel project, you can set up a workflow so that every time you push code:

- PHP is installed on the runner  
- dependencies are installed via Composer  
- PHPUnit tests are executed  
- if everything passes, the application is deployed automatically  

No manual intervention is needed.  
This results in faster development and a more organized workflow.

## Summary Sentence  
Today, I learned about GitHub Actions and how it automates tasks such as testing and deployment, making development faster, cleaner, and more professional.
