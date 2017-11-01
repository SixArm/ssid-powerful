# ssid-powerful


Syntax:

    ssid-powerful [options] <ssid>

Example:

    ssid-powerful "My Demo WiFi" && echo "yes" || echo "no"

You can decide what the word powerful means to you.

For example we use these:

  * Do we know the WiFi is free?
  * Do we know the WiFi is fast?
  * Do we know the WiFi is secure?


## Setup

To set up the configuration directory and data file:

    ssid-powerful --init

The configuration directory goes here by default:

    ~/.config/ssid-powerful/data.txt

The configuration file is plain text. You can edit it as you like.


## Usage

To add an item i.e. insert an item in the data file:

    ssid-powerful --add "foo"

To drop an item i.e. delete an item from the data file:

    ssid-powerful --drop "foo"

To query an item i.e. ask if the item is in the data file:

    ssid-powerful --query "foo"


## Options

Option paramters:

  * -i --init: initialize the configuration
  * -a --add <ssid>: append an item into the data file
  * -d --drop <ssid>: delete an item from the data file
  * -q --query <ssid>: ask if an item is in the data file
  * -h --help: print help text
  * -v --version: print version number
  * -V --variant: print the program name, version number, updated date.


## Tracking

  * Command: ssid-powerful
  * Version: 1.1.2
  * Updated: 2017-11-01
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)"
