# A modern Front End development environment

These instructions exist only because my envinroment setup is growing so fast and there's simply too many repositories to consider when building the stack from scratch.

This assumes you don't have *anything* pre-installed. If you have something installed, please just skip the step. Scroll down to [Installation](https://github.com/ronilaukkarinen/dudestack-instructions#installation). **Note:** This is not yet tested, so feel free to do so.

#### Dudestack-instructions = Instructions for setting up

- Vagrant environment with [jolliest-vagrant](https://github.com/ronilaukkarinen/jolliest-vagrant)
- WordPress stack with [wpstack-rolle](https://github.com/ronilaukkarinen/wpstack-rolle) (based on [roots/bedrock](https://github.com/roots/bedrock))
- Gulp, nodejs and npm-modules with [gulpfile-rolle](https://github.com/ronilaukkarinen/gulpfile-rolle)
- Landing pages with [modern-html5-boilerplate](https://github.com/ronilaukkarinen/modern-html5-boilerplate)

### Part of the daily workflow

Please let me know if you have suggestions for new/better apps/modules/plugins...

- [BitBucket](https://bitbucket.org/) - Bitbucket is a free code DVCS hosting site for Git and Mercurial. Manage your development with a hosted wiki, issue tracker and source code.
- [RVM](https://rvm.io/) - RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.
- [Homebrew](http://brew.sh/) - The missing package manager for OS X
- [Node.js](http://nodejs.org/) - Node.js® is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications.
- [npm](https://www.npmjs.com/) - A package manager for node/browsers/gulp/etc.
- [Vagrant](https://www.vagrantup.com/) - Create and configure lightweight, reproducible, and portable development environments.
- [Gulp](http://gulpjs.com/) - Automate and enhance your workflow
- [BrowserSync](http://www.browsersync.io/) - Time-saving synchronised browser testing.
- [Composer](https://getcomposer.org/) - Dependency Manager for PHP
- [WP-CLI](http://wp-cli.org/) - A command line interface for WordPress
- [Google Chrome Canary](https://www.google.com/chrome/browser/canary.html) - Google Chrome Canary has the newest of the new Chrome features.
- [Sublime Text 3](http://www.sublimetext.com/3) - Sublime Text is a sophisticated text editor for code, markup and prose.
- [CSSComb](http://csscomb.com/) - CSScomb is a coding style formatter for CSS.
- [PlainTasks](https://github.com/aziz/PlainTasks) - An opinionated todo-list plugin for Sublime Text editor.
- [WakaTime](https://wakatime.com/) - Analytics for programmers
- [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter) - A plugin for the Sublime text 2 and 3, which underlays selected hexadecimal colorcodes with their real color.
- [Monokai Soda](https://github.com/buymeasoda/soda-theme) - A theme for Sublime Text
- [Emmet](https://github.com/sergeche/emmet-sublime) - Emmet is a plugin for many popular text editors which greatly improves HTML & CSS workflow
- [SnapRuler](http://www.snaprulerapp.com/) - Screen ruler that does the job for you
- [ColorSnapper](http://www.colorsnapper.com/) - The missing color picker for Mac
- [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake) - Don't let your Mac fall asleep
- [Trello](https://trello.com/ronilaukkarinen/recommend) - Trello is the free, flexible, and visual way to organize anything with anyone.
- [Todoist](http://todoist.com/) - Todoist is the best online task management app and to-do list.
- [f.lux](https://justgetflux.com/) - Is your computer keeping you up late? f.lux is free software that warms up your computer display at night, to match your indoor lighting.
- [ImageOptim](https://imageoptim.com/) - better Save For Web

## Requirements

- Mac OS X
- Command line
- Patience

## To Do

- [Bower](http://bower.io/)
- [HHVM](http://hhvm.com/)

# Installation

1. Install latest version of [XCode](https://developer.apple.com/xcode/downloads/) to get necessary utils. Apple's XCode development software is used to build Mac and iOS apps, but it also includes the tools you need to compile software for use on your Mac. XCode is free and you can also find it in the [App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12).
2. Open **Terminal** and run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` to download latest version of [Homebrew](http://brew.sh/)
3. Install latest version of [rvm](https://rvm.io/) with `curl -L https://get.rvm.io | bash -s stable --auto-dotfiles --autolibs=enable --rails` to get ruby working
4. Install latest version of [Git](http://git-scm.com/downloads) with `brew install git`
5. [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads)
6. Install [Vagrant](https://www.vagrantup.com/) with `brew install vagrant`
7. Install vagrant-triggers with `vagrant plugin install vagrant-triggers`
8. Clone [jolliest-vagrant](https://github.com/ronilaukkarinen/jolliest-vagrant) with `git clone git@github.com:ronilaukkarinen/jolliest-vagrant.git` to your home directory (`cd ~`), modify **Vagrantfile** if necessary
9. Create Project directory under your home dir with either **Finder** or `mkdir ~/Projects` (this is preferred, but if you decide to store your projects elsewhere, you will have to modify every config where Projects are defined). This directory is the intended location for every project created with this stack.
10. Clone [wpstack-rolle](https://github.com/ronilaukkarinen/wpstack-rolle) to your home directory with `git clone git@github.com:ronilaukkarinen/wpstack-rolle.git`
11. Run `cd ~/wpstack-rolle && sh setup.sh` and complete the setup process
12. Run `createproject` and wait the script to run through. **Note:** It's intended that every project name is one word, written in lowercase.
13. Go to your project directory by `cd ~/Project/projectname` and clone [gulpfile-rolle](https://github.com/ronilaukkarinen/gulpfile-rolle) with `git clone git@github.com:ronilaukkarinen/gulpfile-rolle.git .` (note the dot in the end of a command, we want these to the same directory)
14. Edit `PROJECTNAME` (project folder name) and `THEMENAME` (your theme folder name in content/themes/x) to match your WordPress project and theme name sin **gulpfile.js** and **package.json**.
15. Install [Node.js](http://nodejs.org/) with `brew install node`
16. Install npm updates checker [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) with `sudo npm install -g npm-check-updates`
17. Check updates for npm modules by running `npm-check-updates -u` (still in the Project directory, /Users/yourusername/Projects/yourproject. You can check where you are by `pwd`)
18. Install npm package updates by `npm install` and update them by `npm update`
20. Install [Google Chrome Canary](https://www.google.com/chrome/browser/canary.html)
21. Run `gulp watch`. A new Google Canary browser window should open and you can start coding your WordPress theme.
22. If you want to create a landing page instead, go to Project dir with `cd ~/Projects`, clone [modern-html5-boilerplate](https://github.com/ronilaukkarinen/modern-html5-boilerplate) with `git clone git@github.com:ronilaukkarinen/modern-html5-boilerplate.git`, rename folder to your project, edit **gulpfile.js** and start coding