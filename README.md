# A modern Front End development environment

My company is a digital agency called Dude (Digitoimisto Dude Oy), [check out the company website](https://www.dude.fi) where I'm the head of technical development at the moment. I'm using plenty of tools, apps, modules, frameworks which together are called "stack". Dudestack-instructions contains information about these tools *and* instructions on how to set up a similar stack.

This repo and instructions exist only because my envinroment setup is growing so fast and there's simply too many repositories to consider when building the stack from scratch.

The instructions assume that you don't have *anything* pre-installed. If you have something installed, please just skip the step. Scroll down to [Installation](https://github.com/ronilaukkarinen/dudestack-instructions#installation).

This is just a tip of the iceberg, but I hope it's useful to you.

**Note:** [The Instructions](https://github.com/ronilaukkarinen/dudestack-instructions#installation) are completely untested, so feel free to do so and throw an issue if something doesn't work out just quite it should.

### Dudestack-instructions = Instructions for setting up

- Vagrant environment with [jolliest-vagrant](https://github.com/ronilaukkarinen/jolliest-vagrant)
- WordPress stack with [dudestack](https://github.com/ronilaukkarinen/dudestack) (based on [roots/bedrock](https://github.com/roots/bedrock))
- Gulp, nodejs and npm-modules with [devpackages](https://github.com/ronilaukkarinen/devpackages)
- Landing pages with [modern-html5-boilerplate](https://github.com/ronilaukkarinen/modern-html5-boilerplate)

### Tools / bulding blocks for SCSS, jQuery, PHP

#### For building

- [BitBucket](https://bitbucket.org/) - Bitbucket is a free code DVCS hosting site for Git and Mercurial. Manage your development with a hosted wiki, issue tracker and source code.
- [Homebrew](http://brew.sh/) - The missing package manager for OS X
- [Homebrew Cask](http://caskroom.io/) - Homebrew Cask extends Homebrew and brings its elegance, simplicity, and speed to OS X applications and large binaries alike.
- [RVM](https://rvm.io/) - RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.
- [Node.js](http://nodejs.org/) - Node.js® is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications.
- [npm](https://www.npmjs.com/) - A package manager for node/browsers/gulp/etc.
- [Vagrant](https://www.vagrantup.com/) - Create and configure lightweight, reproducible, and portable development environments.
- [Vagrant Manager](http://vagrantmanager.com/) - Manage your vagrant machines in one place with Vagrant Manager for OS X.
- [Gulp](http://gulpjs.com/) - Automate and enhance your workflow (my gulpfile.js can be found in [devpackages](https://github.com/ronilaukkarinen/devpackages))
- [BrowserSync](http://www.browsersync.io/) - Time-saving synchronised browser testing. (included in Gulp like in many other awesome tasks, check out my [devpackages](https://github.com/ronilaukkarinen/devpackages))
- [Bower](http://bower.io/) - A package manager for the web (to install and update CSS/Javascript packages and their dependencies, see my [devpackages](https://github.com/ronilaukkarinen/devpackages))
- [Composer](https://getcomposer.org/) - Dependency Manager for PHP
- [WP-CLI](http://wp-cli.org/) - A command line interface for WordPress
- [Google Chrome Canary](https://www.google.com/chrome/browser/canary.html) - Google Chrome Canary has the newest of the new Chrome features.
- [Sublime Text 3](http://www.sublimetext.com/3) - Sublime Text is a sophisticated text editor for code, markup and prose. (also check out my current [sublime-settings](https://github.com/ronilaukkarinen/sublime-settings))

#### For developing and designing

##### Layout

- [Jeet Grid System](http://jeet.gs/) - Smart CSS preprocessor grids
- [Font Awesome](http://fortawesome.github.io/Font-Awesome/) - The iconic font and CSS toolkit
- [Normalize.scss](https://github.com/JohnAlbin/normalize-scss) - A modern, HTML5-ready alternative to CSS resets
- [Vide](http://vodkabears.github.io/vide/) Easy as hell jQuery plugin for video backgrounds
- [jQuery.equalHeights](https://github.com/mattbanks/jQuery.equalHeights) - Simple equal heights jQuery plugin
- [Packery](http://packery.metafizzy.co/) - Packery makes your crazy & clever layout a real thing.
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/) - Magnific Popup is a responsive lightbox & dialog script with focus on performance and providing best experience for user with any device
- [fancyBox](http://fancyapps.com/fancybox/) - Fancy jQuery Lightbox Alternative

##### Boilerplates

- [Outline](https://github.com/matt-harris/outline) - Outline is a simple CSS starter responsive boilerplate for any new web project, created by Matt Harris
- [Blueplate](https://github.com/chrishumboldt/Blueplate) - A lightweight, responsive CSS layout engine and SASS mixin library
- [Penguin](https://github.com/bq/penguin) - Lightweight and extensible front-end basecoat

##### Social Media integrations

- [Pongstagram](http://pongstr.github.io/pongstagr.am/ ) - jQuery plugin that lets you display your Instagram media to your website using Bootstrap Front-end styles and modal-plugin.
- [Instagram-PHP-API](https://github.com/cosenary/Instagram-PHP-API) - An easy-to-use PHP Class for accessing Instagram's API
- [Facebook PHP SDK](https://github.com/facebookarchive/facebook-php-sdk) - The Facebook SDK for PHP provides a native interface to the Graph API and Facebook Login (preferably [v4](https://github.com/facebook/facebook-php-sdk-v4))
- [php-foursquare](https://github.com/hownowstephen/php-foursquare) - A simple foursquare API v2 library for PHP focused on supplying core functionality without any extra bloat.
- [Pintlabs Untappd](https://github.com/PintLabs/Pintlabs_Service_Untappd) - PHP library to interact with the Untappd public API

##### Forms

- [Buttons](https://github.com/alexwolfe/Buttons) - A CSS button library built using Sass and Compass

##### Navigations

- [Flexnav-rolle](https://github.com/ronilaukkarinen/flexnav-rolle) - A jQuery plugin for responsive menus
- [Trunk.js](http://www.roblukedesign.com/trunk/trunk.html) - A responsive web design to hide top navigation into a navigation drawer on Tablets and Mobile Phones
- [Responsive Nav](http://responsive-nav.com/) - Responsive navigation plugin without library dependencies and with fast touch screen support

##### Typography

- [Sass Boilerplate's fontFace](https://github.com/magnetikonline/sassboilerplate) - Easy include a webfont
- [knife](https://github.com/Pushplaybang/knife) - Nail vertical rhythm, modular scale, and REMs like a boss with this simple set of SASS/SCSS variables, functions and mixins. (preferred)
- [Sassy-Gridlover](https://github.com/hiulit/Sassy-Gridlover) - Super easy to use Sass mixins to establish a typographic system with modular scale and vertical rhythm. (alternative)
- [Sassline](https://sassline.com/) - Set text on the web to a baseline grid with Sass & rems.

##### Effects

- [Animate.css](http://daneden.github.io/animate.css/) - A cross-browser library of CSS animations. As easy to use as an easy thing.
- [WOW.js](http://mynameismatthieu.com/WOW/) - Reveal Animations When Scrolling
- [Slick](http://kenwheeler.github.io/slick/) - The last carousel you'll ever need
- [skrollr](http://prinzhorn.github.io/skrollr/) - Parallax scrolling for the masses
- [waypoints](http://imakewebthings.com/waypoints/) - Waypoints is the easiest way to trigger a function when you scroll to an element.
- [saffron](https://github.com/colindresj/saffron) - A simple Sass mixin library for animations and transitions

##### Freebies

- [StockSnap.io](https://stocksnap.io/) - Beautiful free stock photos. (CC0)
- [TheStocks.im](http://thestocks.im/) - The best royalty free
stock photos in one place (CC0)
- [Pexels Videos](https://videos.pexels.com/) - Completely free stock videos. (CC0)
- [Pixel Buddha](http://pixelbuddha.net/) - Free and premium resources for designers and developers
- [Streetwill](http://streetwill.co/) - Free Hi-Res Photos (CC0)
- [Life of Pix](http://www.lifeofpix.com/) - Free high-resolution photos (CC0)

##### Inspiration and useful parts

- [CodyHouse](http://codyhouse.co/)
- [Codrops](http://tympanus.net/codrops/)
- [Codepen](http://codepen.io/)

#### Other apps and tools included in daily workflow

Please let me know if you have suggestions for new/better apps/modules/plugins...

- [SnapRuler](http://www.snaprulerapp.com/) - Screen ruler that does the job for you
- [ColorSnapper](http://www.colorsnapper.com/) - The missing color picker for Mac
- [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake) - Don't let your Mac fall asleep
- [Amphetamine](https://itunes.apple.com/us/app/amphetamine/id937984704?mt=12) - With Amphetamine, you can effortlessly override your energy saver settings and keep your Mac awake.
- [Trello](https://trello.com/ronilaukkarinen/recommend) - Trello is the free, flexible, and visual way to organize anything with anyone.
- [Todoist](http://todoist.com/) - Todoist is the best online task management app and to-do list.
- [f.lux](https://justgetflux.com/) - Is your computer keeping you up late? f.lux is free software that warms up your computer display at night, to match your indoor lighting.
- [ImageOptim](https://imageoptim.com/) - better Save For Web
- [Moom](http://manytricks.com/moom/) - Move and zoom windows

## Requirements

- Mac OS X
- Command line
- Patient learning curve
- Urge to always know more about anything

## To Do

- [HHVM](http://hhvm.com/)

# Installation

1. Install latest version of [XCode](https://developer.apple.com/xcode/downloads/) to get necessary utils. Apple's XCode development software is used to build Mac and iOS apps, but it also includes the tools you need to compile software for use on your Mac. XCode is free and you can also find it in the [App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12).
2. Open **Terminal** and run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` to download latest version of [Homebrew](http://brew.sh/)
3. Run `brew install caskroom/cask/brew-cask` to get [Homebrew Cask](http://caskroom.io/)
4. Install latest version of [rvm](https://rvm.io/) with `curl -L https://get.rvm.io | bash -s stable --auto-dotfiles --autolibs=enable --rails` to get ruby working
5. Install latest version of [Git](http://git-scm.com/downloads) with `brew install git`
6. Install latest version of [Composer](https://getcomposer.org) with `curl -sS https://getcomposer.org/installer | php && sudo mv composer.phar /usr/local/bin/composer && sudo chmod +x /usr/local/bin/composer`
7. [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads)
8. Install [Vagrant](https://www.vagrantup.com/) with `brew install vagrant`
9. Install [Vagrant Manager](http://vagrantmanager.com/) with `brew cask install vagrant-manager`
10. Install vagrant-triggers with `vagrant plugin install vagrant-triggers`
11. Create directory for your projects under your home dir with either **Finder** or `mkdir ~/Projects` (this is preferred, but if you decide to store your projects elsewhere, you will have to modify every config where Projects are defined). This directory is the intended location for every project created with this stack and all things related.
12. Clone [jolliest-vagrant](https://github.com/ronilaukkarinen/jolliest-vagrant) with `git clone https://github.com/ronilaukkarinen/jolliest-vagrant.git` to your Projects directory (`cd ~/Projects`), modify **Vagrantfile** if necessary
13. Clone [dudestack](https://github.com/ronilaukkarinen/dudestack) to your Projects directory with `cd ~/Projects && git clone https://github.com/ronilaukkarinen/dudestack`
14. Run `cd ~/Projects/dudestack && sh setup.sh` and complete the setup process
15. Run `createproject` and wait the script to run through. **Note:** It's intended that every project name is one word, written in lowercase.
16. Go to your project directory by `cd ~/Project/projectname` and clone [devpackages](https://github.com/ronilaukkarinen/devpackages) with `git clone https://github.com/ronilaukkarinen/devpackages .` (note the dot in the end of a command, we want these to the same directory)
17. Edit `PROJECTNAME` (project folder name) and `THEMENAME` (your theme folder name in content/themes/x) to match your WordPress project and theme name sin **gulpfile.js** and **package.json**.
18. Install [Node.js](http://nodejs.org/) with `brew install node`
19. Install npm updates checker [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) with `sudo npm install -g npm-check-updates`
20. Check updates for npm modules by running `npm-check-updates -u` (still in the Project directory, /Users/yourusername/Projects/yourproject. You can check where you are by `pwd`)
21. Install npm package updates by `npm install` and update them by `npm update`
22. Install [Google Chrome Canary](https://www.google.com/chrome/browser/canary.html)
23. Run `gulp watch`. A new Google Canary browser window should open and you can start coding your WordPress theme.
24. If you want to create a landing page instead, go to Project dir with `cd ~/Projects`, clone [modern-html5-boilerplate](https://github.com/ronilaukkarinen/modern-html5-boilerplate) with `git clone https://github.com/ronilaukkarinen/modern-html5-boilerplate`, rename folder to your project, edit **gulpfile.js** and start coding