---
title: Demo
modified: 2014-06-07 23-18-54
layout: page
tags: []
permalink: "demo.html"
comments: true
---

# Demo boxes

To save time setting up software dependencies, we've provided some Vagrant Boxes.

After [setting up Vagrant](http://docs.vagrantup.com/v2/getting-started/index.html), download these boxes, or use our Vagrant files below.

Vagrant Boxes:

+ [collins/alchemy transmuter box](https://github.com/OpenSRE/OpenSRE.github.io/releases/download/pre-velocity/collins-and-transmuter.box)
+ [alchemy linux box](https://github.com/OpenSRE/OpenSRE.github.io/releases/download/pre-velocity/alchemy-linux.box)

Vagrant files:

+ [collins/alchemy transmuter](https://gist.githubusercontent.com/dalehamel/a33daefdd7e842f33e51/raw/106b2860184a7c5965ac2ac165ed8ec6a6002462/gistfile1.txt)
+ [alchemy linux](https://gist.githubusercontent.com/dalehamel/4ee424fbeaf929731ded/raw/80fb7050d6ce450f8e88829a18ffbece09ce00ad/gistfile1.txt)

**Note:** If you're attempting to use these Vagrant files at Velocity, substitute "config.vm.box\_url" with the path to the box on the file server, or else it will try to download it externally.

# Sample usage

## Collins / Transmuter

```
mkdir collins
cd collins
wget https://gist.githubusercontent.com/dalehamel/a33daefdd7e842f33e51/raw/106b2860184a7c5965ac2ac165ed8ec6a6002462/gistfile1.txt -O Vagrantfile
vagrant up
vagrant ssh
```

To start collins:

```
cd collins
git pull --rebase origin master
play run
```

To start the transmuter:

```
cd alchemy-linux-public
git pull --rebase origin master
bundle install
bundle exec ruby transmuter.rb
```

## Alchemy Linux


```
mkdir alchemy
cd alchemy
wget https://gist.githubusercontent.com/dalehamel/4ee424fbeaf929731ded/raw/80fb7050d6ce450f8e88829a18ffbece09ce00ad/gistfile1.txt -O Vagrantfile
vagrant up
vagrant ssh
```

