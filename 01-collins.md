---
title: Collins
modified: 2014-06-07 23-18-54
layout: page
tags: []
permalink: "collins.html"
comments: true
---

# Central Source of Truth

Truth is important in your infrastruture. Keeping it in a central location lets you automate repetitive tasks easily, and with confidence.

Collins acts as a central Source of Truth in the Genesis Stack. It provides an object-oriented view of different infrastructure components, and exposes these through a web interface and a REST-ful JSON api.

Collins was developed by [tumblr](http://tumblr.github.io), and this fork is maintained by [http://www.shopify.com](Shopify).

# Getting started

You can find more documenatation on setting up Collins [here](http://shopify.github.io/collins/#quickstart).

Or, try out this [vagrant box](https://github.com/OpenSRE/OpenSRE.github.io/releases/download/pre-velocity/collins-and-transmuter.box) to avoid setting up depenencies.

# The API

Collins has a [well documented REST api](http://shopify.github.io/collins/api.html). The best way to learn it is to run through it.

Try the following actions using the API:

+ Create an asset
+ Update / add attributes of that asset
+ Add entries to the asset log
+ Assign an IP address
+ Add / Update IPMI data
+ Create a new asset state
+ Update the state of an asset
+ Delete an asset
+ Create an asset hierarchy
