[![Gitter chat](https://badges.gitter.im/codefresh-io/beta.png)](https://gitter.im/codefresh-io/beta "Gitter chat")

![codefresh](https://dl.dropboxusercontent.com/u/7079908/public_images/codefresh_logo_web.png)

## Welcome to the Codefresh Beta program!

We are very pleased to have you as part of our beta program and we welcome your feedback. We are currently provisioning access to a limited number of people. Access to the platform is granted by GitHub or BitBucket ID, so please complete your registration [here](http://goo.gl/forms/PjMqFDysVG).

## What is Codefresh?

We are a startup headquartered in Palo Alto. We are passionate about Node.js, Docker, microservice architecture, and DevOps. Our mission is to enable Development and QA teams to test, fix and collaborate on multi-Docker applications in the most efficient, usable and cost-effective way.

## What can you do with our service?

Our primary goal is to provide one-click access to on-demand, Cloud hosted workspaces to demonstrate, test, edit, and collaborate on any commit for any branch in a GitHub repo for Dockerized Node service applications.

We want to make it easy to configure and launch an orchestrated environment that matches production for Node.js services and their dependencies, making it fast, simple and painless to collaborate, test branches, and share feature previews with others.

Codefresh provides a terminal and a web IDE (based on Eclipse Orion) that allow you to test, edit code and commit changes. For convenience, we provide a streamlined interface to GitHub branch management. While your primary development environment might be on your desktop, Codefresh makes it trivial to spin up cloud-hosted environments for working on any branch and sharing previews with other members of your team.

## Getting Started

Please see our [Getting Started](https://github.com/codefresh-io/beta/wiki/Getting-Started) wiki page.

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
 * Repo settings (displayed in repo settings page) are not fully implemented/saved

 * npm install

Unlike our public Labs beta, the private beta does not automatically run `npm install`. You will need to run it manually in the terminal. However, make sure to note the next section about `NODE_ENV`.

* NODE_ENV

`NODE_ENV` is set to production. If you have `devDependencies` in your `package.json` that you want to install (to run tests, for example), make sure to explicitly set it to `development` before installing.

    NODE_ENV=development npm install

 * Setting the port

A public port is exposed for you to test and is displayed at the top left in the following screenshot. However, the `PORT` environment variable is not currently being set. Make sure to explicitly provide it when running your app.

    PORT=9000 npm start

or

    PORT=9000 node <module>

![port](http://images.codefresh.io.s3.amazonaws.com/getting-started/port-assignment.png)


