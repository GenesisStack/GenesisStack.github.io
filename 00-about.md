---
layout: page
title: About
permalink: "about.html"
---

# Built by Shopify, inspired by tumblr

The Alchemy Transmuter is a part of the "Genesis" stack, which is inspired by tumblr's infrastructure management and Source of Truth Stack.

tumblr uses a tool called "Phil" to render iPXE menus for a Linux distro called "Invisible Touch" based on information stored in "Collins".

While Collins was Open Sourced, Phil, Visioner, and Invisible Touch were not.

[Shopify](http://www.shopify.com) has implemented and released their own version of these two components, and in an attempt to avoid confusion, has chosen an "Alchemy" theme for them. Together, they form the "Genesis" stack.


| Tumblr                                                    | Purpose                   | Genesis                    |
|:----------------------------------------------------------|:--------------------------|:---------------------------|
| [Collins](http://tumblr.github.io/collins/index.html)     |Central Source of Truth            | [Collins\*](http://shopify.github.io/collins/) |
| [Phil](http://tumblr.github.io/collins/tools.html#phil) + [Visioner](http://tumblr.github.io/collins/tools.html#visioner) |iPXE render / Provisioner  | [Alchemy Transmuter + Spells](http://shopify.github.io/alchemy-transmuter-public/)|
| [Invisible Touch](http://tumblr.github.io/collins/tools.html#it)   |Baremetal Job Runner       | [Alchemy Linux](http://shopify.github.io/alchemy-linux-public/) |

\* We are currently using our own forked version of collins, but intend to upstream our changes.

# Contributing

If you're interested in contributing, just fork, and submit a PR!
