# Submission Scripts

This repository contains scripts to send submissions to IncrediBL. If you would
like to add something please see the [Contributing] (#contributing) section of 
this document.

## Current Methods

### Bash

This script can be used standalone via command line or included/referenced in 
another application. No installation or dependencies, simply copy it to your
machine and do the needful. Documentation is contained at the top of the script.

### irssi

The irssi script can be used via irssi to submit hosts. This is ideal for IRC
Operators or really vigilant IRC netizens.

## Contributing

### Bug Reports

Non-security bug reports should be submitted via GitHub. Bug reports about
security issues should be disclosed to IncrediBL administrators privately.

When submitting a bug report, please include the following information:

* Submission method (Perl, irssi, Bash, etc.)
* Method version
* Perl/irssi/Bash version/build date
* Operating system version/distro
* Errors you received
* Steps to recreate problem

### Submitting New Methods

Don't see a method you like? Patches welcome! Fork this repository, add your
method, then submit a pull request. If it's your first time we'll be gentle.

#### Coding Standards

We could argue about tabs vs spaces. Personally I prefer tabs, but if you NEED
to use spaces, please use no less than 2 and no more than 4. Whatever you
choose, be consistent. Don't mix tabs and spaces.

There's a line length cap of 80, but this is a soft cap. If you go over 80 we
won't break your legs unless your submission is unreadable.