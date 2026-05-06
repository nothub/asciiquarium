# Asciiquarium

Asciiquarium is an aquarium/sea animation in ASCII art.  
Enjoy the mysteries of the sea from the safety of your own terminal!

![preview](https://user-images.githubusercontent.com/48992448/219967010-69ee6002-a299-444e-b9cd-fc5222cb7488.gif)

> Original by Kirk Baucom <kbaucom@schizoid.com>  
> https://robobunny.com/projects/asciiquarium/html

---

## Installation

Asciiquarium is a single perl script, so all you have to do is make sure
it's executable and put it somewhere convenient, like `/usr/local/bin` or
`/usr/local/games`.

### Dependencies

Asciiquarium depends on the Term::Animation perl module, which depends on
Curses. You can get both modules from http://search.cpan.org. This program
will only run on platforms that have a Curses library (so it won't work on
Windows, but you might get it to run under cygwin).

Installing dependencies on debian/ubuntu:
```
sudo apt install perl-modules libcurses-perl
sudo cpan -i Term::Animation
```

## Usage

```
Options:
  -c --classic      Only show species from Asciiquarium 1.0
  -t --transparent  Transparent background
  -s --screensaver  Exit on any keypress
  -h --help         Print help and exit
  -v --version      Print version and exit

Hotkeys:
  q                 quit
  r                 redraw
  p                 pause
  t                 toggle transparency
  space,            add new entity
  followed by:
      b             big fish
      B             suBmarine
      d             dolphins
      D             Ducks
      h             fishhook
      j             jellyfish
      m             monster
      O             swOrd
      r             random
      s             ship
      S             Shark
      w             whale
      W             sWan
```

## Historical

Asciiquarium was originally written by Kirk Baucom ([homepage](https://robobunny.com/projects/asciiquarium/html)).  
Many [changes from different people](CHANGES.txt) were integrated into the application.

The original version of this program is available at:  
http://robobunny.com/projects/asciiquarium

Claudio Matsuoka's fork is available at:  
https://github.com/cmatsuoka/asciiquarium
