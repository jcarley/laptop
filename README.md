Laptop
======

Laptop is a script to set up a Linux laptop for Rails development.

Requirements
------------

We support:

* [14.04: Trusty Tahr](https://wiki.ubuntu.com/TrustyTahr/ReleaseNotes),
* [16: Linux Mint](http://www.linuxmint.com/rel_petra_cinnamon.php)


Install
-------

Read, then run the script:

    bash <(wget -qO- https://raw.githubusercontent.com/jcarley/laptop/master/laptop.sh)

What it sets up
---------------

* Zsh as your shell
* Oh-My-ZSH
* Bundler gem for managing Ruby libraries
* Heroku Config plugin for local `ENV` variables
* Heroku Toolbelt for interacting with the Heroku API
* Hub gem for interacting with the GitHub API
* Node.js and NPM, for running apps and installing JavaScript packages
* MySQL for storing relational data
* Rbenv for managing versions of the Ruby programming language
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* SublimeText 3 for editing rails code
* Google Chrome browser for surfing the web

