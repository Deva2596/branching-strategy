# Mobify Branching Strategy

## What is the purpose of this repository?

As Mobify continues to grow and expand its operations globally, consistency across all teams and partners is a key
focus. The more aligned all Mobify projects are, the more productive everyone will be.

This repository and its documentation outline:
* How we develop features
* When and how we create a release
* What to do when a hot fix is required
* Anything else related to our branching strategy

### This repository will be helpful for:

* Any new Mobify employees who will be involved in both internal and client-facing projects
* Partners, contractors, etc who modify project code
* Onboarding

### What the repository is not:

* Written in stone. Pull requests are welcome and we will update this document with lessons learned
and improvements as we go
* The one and only way to work on projects. There are always certain edge cases where things
have to be tweaked, but don't let tweaking become the norm

## Project Types

Depending on the type of project, one of two branching strategies is used:

### 1) Continuous Deployment

Use this strategy for projects where features get deployed as soon as they're ready.

[Learn more](./continuous-deployment.md)

### 2) Release Deployment

Use this strategy for projects where features get bundled into a release and then
deployed together.

[Learn more](./release-deployment.md)
