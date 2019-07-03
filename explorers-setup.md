# Set up for our explorers

Here's a list up all the explorers and apps we maintain, along with setup instructions for each. Most of these are documented in other locations. This doc attempts to gather all those links into one place

This assumes that everything in the [computer setup](computer-setup.md) section has been installed.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Salaries](#salaries)
- [Prisons](#prisons)
- [Schools](#schools)
- [Republic API](#republic-api)
- [Campaign finance](#campaign-finance)
- [Elections](#elections)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## [Salaries](https://salaries.texastribune.org/)

The basic setup is documented on in its [Github repo](https://github.com/texastribune/salaries.texastribune.org).

How to update salaries in [documented on Confluence](https://wiki.texastribune.org/pages/viewpage.action?pageId=12420703).

You will need SSH into the production server in order to update the DB. You will first need to create a `~/.ssh/config` file if you don't have one already. And then copy the salaries production info shown at the bottom of this [Confluence readme](https://wiki.texastribune.org/display/TECH/AWS+hosts0).

As part of the setup, you will need to get a `newsapps.pem` file, which we can hook you up with.

## [Prisons](https://www.texastribune.org/library/data/texas-prisons/)

Prisons is in the Github repo for the Tribune's main site. It's updated once a month. We've documented how to update in [this readme](https://github.com/texastribune/texastribune/tree/master/snollygoster/dataapps/prisons/scripts).

To deploy to the production DB, you will need to get credentials. Currently, Daniel is the one responsible for handing those out.

## [Schools](https://schools.texastribune.org/)

The schools app is updated once a year. The code behind the app is located in this [Github repo](https://github.com/texastribune/scuole). The data is loaded separately in [this repo](https://github.com/texastribune/scuole-data/).

This section will be more fleshed out next time we update schools.

## [Republic API](https://republic.texastribune.org/api/v1/)

## Campaign finance

## Elections

