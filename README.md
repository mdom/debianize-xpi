<!---
% DEBIANIZE-XPI(1) GNU
% Mario Domgörgen
% Aug 29, 2015
--->

# NAME

debianize-xpi - generate debian packages for mozilla addons

# SYNOPSIS

debianize-xpi $MOZILLA\_DOWNLOAD\_URL

# DESCRIPTION

*debianize-xpi* generate debian packages for Mozilla Addons. Simple
provide the download url for the addon and it will produce a deb in your
current wokring directory named *xul-ext-addon-name.deb*

# INSTALLATION

There's a number of dependency you need to run *debianize_xpi*: curl to
download packages, xmlstarlet to parse the install.rdf and unzip to
uncompress it. For building the package you need the normal debuilder
toolchain and install-xpi from mozilla-devscripts. To install all
dependency via apt-get just call:

    $ apt-get install mozilla-devscripts curl unzip xmlstarlet devscripts

# COPYRIGHT

Copyright 2014 Mario Domgoergen <mario@domgoergen.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
