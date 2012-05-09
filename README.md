build-tools
===========

Build tools for pre commit to git repos

Installation
============

1. Copy the pre-commit file to you .git/hooks/ folder
2. Update the ABS_PATH to point to the location of the build tool folder
3. Make the pre pre-commit file writable chmod -x pre-commit
4. Commit away & be forever irritated by PHP/JS/CSS lint warnings.

Path Assumptions
================

The install assumes you have cloned the repository to your home directory in a hidden directory called 'gitbuildtools', ie the tools are expected to be in the following locations:

~/.gitbuildtools/JSLint
~/.gitbuildtools/csslint
~/.gitbuildtools/jslint4java
~/.gitbuildtools/php
~/.gitbuildtools/pre-commit
~/.gitbuildtools/rhino

If that is not the case update the path variables in pre-commit
