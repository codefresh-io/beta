
![codefresh](http://images.codefresh.io.s3.amazonaws.com/logo/codefresh_logo_120x106.png)

## Welcome to the Codefresh Private Beta!

We are very pleased to have you as part of our beta program and we welcome your feedback.

## What is Codefresh?

We are a startup headquartered in Palo Alto. We are passionate about Node.js, Docker, microservice architecture, and DevOps.

## What can you do with our service?

Our primary goal is to provide one-click access to on-demand, Cloud hosted workspaces to test, edit and collaborate on any commit for any branch in a GitHub repo for Dockerized Node service applications.

We want to make it easy to configure and launch an orchestrated environment that matches production for Node.js services and their dependencies, making it fast, simple and painless to collaborate, test branches, and share feature previews with others.

Codefresh provides a terminal and a web IDE (based on Eclipse Orion) that allow you to test, edit code and commit changes. For convenience, we provide a streamlined interface to GitHub branch management. While your primary development environment might be on your desktop, Codefresh makes it trivial to spin up cloud-hosted environments for working on any branch and sharing previews with other members of your team.

## Getting Started

Please see our [Getting Started](wiki/Getting-Started) page.

## How to provide feedback

We are interested in hearing about your use cases, insights, and suggestions for improvement.

Please file issues [here](https://github.com/codefresh-io/beta/issues).

We have a private Google group for discussions [here](https://groups.google.com/forum/#!forum/codefresh-private-beta).

If you can’t access the group, please send an email to beta@codefresh.io

## What will I get out of this?

In addition to the opportunity to have a say in shaping the product and prioritizing features, you will get to be among the first cool kids on the block to have a personal profile page that let’s you highlight your repos with click to launch badges. Stay tuned!

## What’s in this release?

 * Browse your public and private repo branches and commits, merge branches
 * One click to open a workspace for any commit in a branch
 * Configure environment settings for launch
 * Launch your Node service application

## Known Issues & Limitations

 * Login using GitHub repo. We support only GitHub at the moment. We plan to add Bitbucket support.
 * “TEST” link is still ‘work in progress’. Coming soon. 
 * Current implementation uses one Docker container for a repo (in the next version user will be able to visually create fig recipe for multiple containers) 
 * Global Search in the IDE is not working (known bug)
 * User is limited (at the moment) to one running environment at a time
 * Repo settings (displayed in repo settings page) are fully implemented/saved


