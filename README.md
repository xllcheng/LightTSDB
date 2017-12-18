[![Build Status](https://travis-ci.org/FragJage/LightTSDB.svg?branch=master)](https://travis-ci.org/FragJage/LightTSDB)
[![Coverage Status](https://coveralls.io/repos/github/FragJage/LightTSDB/badge.svg?branch=master&bust=0)](https://coveralls.io/github/FragJage/LightTSDB?branch=master)
[![Coverity Scan Build](https://scan.coverity.com/projects/13257/badge.svg)](https://scan.coverity.com/projects/13257)

LightTSDB
=========
Light time series database class.

Introduction
============
This class store time series into the file system and can read float values by hours.

Features  ... developpment in progress
========
 - Choice of the store folder
 - Indexed read
 - Supported type float, double, int, bool.
 - (TO DO) Compressed file
 - (TO DO) Compile on Linux and Windows, Intel or ARM.

Portability
===========
Unit tests passed successfully on :
 - Windows Seven (CPU Intel Celeron)
 - (TO DO) Linux Ubuntu (CPU Intel Atom)
 - (TO DO) Linux Raspian on Raspberry Pi (CPU ARM)
 - (TO DO) Linux FunPlug on NAS DNS-320 (CPU ARM)

For more informations
=====================
(TO DO) See documentation in doc/html/index.html

Licence
=======
LightTSDB is free software : you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

LightTSDB is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with LightTSDB. If not, see http://www.gnu.org/licenses/.
