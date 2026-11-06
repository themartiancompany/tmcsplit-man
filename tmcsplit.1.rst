..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025, 2026  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


==============
tmcsplit
==============

--------------------------------------------------------
Output pieces of FILE to PREFIXaa, PREFIXab, ...
--------------------------------------------------------
:Version: tmcsplit |version|
:Manual section: 1

Synopsis
========

tmcsplit *option* *[arguments]*


Description
===========

The Martian Company's Javascript GNU Split
implementation.


Options
========

-a, --suffix-length=N

  Generate suffixes of
  length N.


-h, --help

  Display help.


Examples
============

split \
  -a \
  "input.bin" \
  5

split-file \
  -x \
  "input.bin" \
  457000

split-file \
  -m \
  "output.bin" \
  "part1" "part2" ...


Bugs
====

https://github.com/themartiancompany/tmcsplit/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* split
* base64.js
* sha256sum.js
* tmccat

.. include:: variables.rst
