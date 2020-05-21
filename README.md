# gromacs-WCA patch

Patch file for [GROMACS][1] ver. 4.5.7

## Functions

This patch adds

- environment variable "GMX_NB_GENERIC_WCA" to change the Lennard-Jones potential to the Weels, Chandler, Andersen (WCA) potential (J. Chem. Phys., 54, pp5237-5247, 1971).

## Prerequisites

GROMACS-4.5.7 Source: [gromacs-4.5.7.tar.gz][2]

### Installing

`patch -p1 < gromacs-4.5.7-wca.patch`

in the top source directory and make.

## Authors

Makoto Yoneya.

[1]: http://www.gromacs.org/
[2]: ftp://ftp.gromacs.org/pub/gromacs/gromacs-4.5.7.tar.gz
