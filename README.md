# Rails Mac Installer 

Rails Mac Installer (RMI) is a tool to get a Ruby on Rails environment running on a vanilla installation of Mac OSX Lion. 

## Disclaimer

Currently this installer is very dumb, it assumes you have a vanilla installation of Lion. If you've installed certain Ruby on Rails related components then use at your own risk even thought it should be safe. It has not been tested on any other versions of Mac OSX. 

## Install

    $ curl -L https://raw.github.com/synctree/rmi/develop/scripts/install/base | bash

## Components
  
  * Homebrew
  * OSX GCC Command Line Tools
  * RVM
  * Ruby 1.8.7, 1.9.2, 1.9.3
  * Rails
  * Pow

## TODO
  
  * Add options to allow script to add mysql, nginx, redis
  * Finish uninstall script

## Contributors

  * [Blake Petetan](https://github.com/petetan)