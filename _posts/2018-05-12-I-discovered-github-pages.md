---
layout: post
title:  "I discovered Github pages"
date:   2018-05-12 18:51:59
categories: github pages
---
## ThankGod I found it early ##
Why ThankGod  :pray: ? , well I was thinking to host my personal website and for that it required for me to
pick a server, virtual host and backend program. I would have cost me atleast 3 days of work and also
some money for host & domain  :disappointed: . But I was found this Github Pages and this is awesome :heart_eyes:   

## Advantages ##

* Fast and free website
* Jekyll static webserver
    * easy blogging
    * tons of jekyll templates just one fork away
* Platform to host documentation of all your project
* Show off your Resume on internet


## Installing Jekyll ##
Jekyll is a static site generator with a templating system that can be adapted for many types of websites, including blogs. It can be run on a server, or run locally and the generated files uploaded to a server. It is the default software used by Github Pages.

Tested with Jekyll 2.5.2 on Ubuntu 14.04 and 14.10
### Install Prerequisites ###

Install ruby, the ruby development libraries, and the make command.
`sudo apt-get install ruby ruby-dev make gcc nodejs`

### Javascript Workaround ###

Installation of nodejs is required because of an issue where Jekyll requires a JavaScript runtime even if it will not be used.
Install Jekyll

Install the Jekyll gem system wide. For speed, we are excluding the extended documentation. To include all documentation, omit the --no-rdoc --no-ri switches.

`sudo gem install jekyll --no-rdoc --no-ri`

### Start Jekyll ###
>Check that Jekyll has been successfully installed.
`jekyll -v`
>The current version is jekyll 2.5.2.

### Recommended ###

Additional gems can add features to Jekyll, such the github-pages gem which bundles together several gems supported by Github Pages.

`sudo gem install github-pages --no-rdoc --no-ri`

Although not required, git is often used to manage the files of a Jekyll website.

`sudo apt-get install git`

### Get Website Content ###

Now that Jekyll is installed, we need content for it to serve. We can either use a current website, or set up a new site from scratch.
Use Existing Site

Use git to clone an existing Jekyll website, such as this one!

`git clone https://github.com/mchelen/michaelchelen.net.git
cd michaelchelen.net`

Please note: the --config option must be specified to run michaelchelen.net locally. See Extra Options section below.
### Create New Site ###

For a new Jekyll site, use the new command to create a directory structure and config files.

`jekyll new my-awesome-site
cd my-awesome-site`

### Start Jekyll ###

Now that the basic config and layout are available, start Jekyll to generate the website HTML and start a local server.

`jekyll serve`

Then visit http://localhost:4000 in a web browser.
>Jekyll is now successfully runnning!


## My work ##
- [x] created Webpage using HTML5 template
- [x] created blog using Jekyll
- [ ] Project documentation


## References :

[Github Pages](https://pages.github.com/) Introduction.

[Jekyll Installation](http://michaelchelen.net/81fa/install-jekyll-2-ubuntu-14-04/) Complete.
