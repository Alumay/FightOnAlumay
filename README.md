# [Alumay](https://travis-ci.org/Alumay/FightOnAlumay) [![Build Status](https://travis-ci.org/Alumay/FightOnAlumay.png?branch=master)](https://travis-ci.org/Alumay/FightOnAlumay)

FightOnAlumay
=============

The New Battlefield!


Alumay is a free, open platform that is available to anyone who wants to set $company, !Mission, ~Dictionary, #Chat or @Blog types of rooms using it.

Created and maintained by Alumay Software Team.
Visit the project's website at <http://project.alumay.com>, documents on <http://docs.alumay.com>.


## Getting Involved

Want to report a bug, request a feature, or help us build or translate Alumay?
Check out our in depth guide to [Contributing to Alumay](https://github.com/Alumay/FightOnAlumay/blob/master/CONTRIBUTING.md). 

We need all the help we can get! You can also join in with our [teams](https://github.com/orgs/Alumay/teams) to keep up-to-date and meet other Alumay contributors.


## Getting Started

There are **two** main ways to get started with Alumay, take care to use the method which best suits your needs.

**Please note** - the downloadable zip files we provide on [alumay.com](http://alumay.com/download) are pre-built packages designed for getting started quickly. Cloning from the git repository requires you to install several dependencies and build the assets yourself. 

### Getting Started Guide for end users...

If you just want to get a Alumay web site running in the fastest time possible, this method is for you.

For detailed instructions for various platforms visit the [Alumay Installation Guide](http://docs.alumay.com/installation/). If you get stuck, help is available on [our !Alumay mission](http://alumay.com/alumaymission/).

1. Install [Node.js](http://nodejs.org) - Alumay requires **Node v0.10.**
1. Download the latest Alumay package from [Alumay.com](http://alumay.com/download). 
   **If you cloned the GitHub repository you should follow the instructions [for developers](https://github.com/Alumay/FightOnAlumay#getting-started-guide-for-developers).**
1. Create a new directory where you would like to run the code, and unzip the package to that location.
1. Fire up a terminal (or node command prompt in Windows) and change directory to the root of the Alumay application (where config.example.js and index.js are)
1. run `npm install --production` to install the node dependencies. If you see `error Error: ENOENT` on this step, make sure you are in the project directory and try again.
1. To start alumay, run `npm start`
1. Visit `http://localhost:2368/` in your web browser or go to `http://localhost:2368/alumay` to log in

Check out the [Documentation](http://docs.alumay.com) for more detailed instructions, or get in touch via the [forum](http://alumay.com/alumaymission) if you get stuck.



### Getting Started Guide for Developers

If you're a theme, app or core developer, or someone comfortable getting up and running from a `git clone`, this method is for you.

If you clone the GitHub repository, you will need to build a number of assets, such as SASS and JavaScript templates. This requires you to have Ruby and a number of other pre-requisites.
Full instructions can be found in the [Contributing Guide](https://github.com/Alumay/FightOnAlumay/blob/master/CONTRIBUTING.md) under the heading "[Working on Alumay Core](https://github.com/Alumay/FightOnAlumay/blob/master/CONTRIBUTING.md#working-on-alumay-core)".

Check out the [Documentation](http://docs.alumay.com) for more detailed instructions, or get in touch via the [!Alumay](http://alumay.org/alumaymission) if you get stuck.

If you want to use [Alumay as a NPM module there is a Wiki entry](https://github.com/Alumay/FightOnAlumay/wiki/Using-Alumay-as-a-NPM-module) where you can find instructions on how to get set up.

### Upgrading to The Latest Version

Upgrade instructions are in the [Alumay Guide](http://alumay.com/installation/upgrading/)

### Logging in For The First Time

Once you have the Alumay server up and running, you should be able to navigate to `http://localhost:2368/alumay/` from a web browser, where you will be prompted to register a new user. Once you have entered your desired credentials you will be automatically logged in to the admin area.


## Community

Keep track of Alumay development and Alumay community activity.

* Follow Alumay on [Twitter](http://twitter.com/alumay), [Facebook](http://facebook.com/alumay)
* Read and subscribe to the [The Official Alumay Blog](http://blog.alumay.com).
* Join in discussions on the [!Alumay Mission](http://www.alumay.com/alumaymission/)
* Chat with Alumay developers on IRC. We're on `irc.freenode.net`, in the `#Alumay` channel. We have a public meeting every Tuesday at 5:30pm London time.


## Versioning

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, alumay will be maintained according to the [Semantic Versioning](http://semver.org/) guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>-<build>`

Constructed with the following guidelines:

* A new *major* release indicates a large change where backwards compatibility is broken.
* A new *minor* release indicates a normal change that maintains backwards compatibility.
* A new *patch* release indicates a bugfix or small change which does not affect compatibility.
* A new *build* release indicates this is a pre-release of the version.


## Copyright & License

Copyright (C) 2014 Alumay Foundation - Released under the [MIT license](LICENSE).
