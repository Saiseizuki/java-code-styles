Java Code Styles
================

IntelliJ IDEA code style settings for Voyager's Android projects.


Notable changes from Square's
-----------------------------
* All annotations always consume one line each, same as enum constants.
* Multiple parameters (Wrap if long and aligned).
* New line after ‘}’ on try-catch, switch, if-else statements (easier editing if using command line text editors such as vim).
* Force usage of braces on for and if-else statements even if only having a single line of code.
* 100 fixed column width.
* Ensure right margin not exceeded.
* Field (‘m’) and Static (’s’) auto removal for getters and setters of var name.

Installation
------------

 * Run the `install.sh` script.
 * Restart IntelliJ if it's running.
 * Open IntelliJ Project Settings -> Code Styles, change the code style to 'VoyagerAndroid'


License
-------

[![Public domain](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
