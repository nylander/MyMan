# My Man(ual files)

## Description

Put your manual files in the folder `mymanfolder`.

Find and read them using `myman`.

The Python script [`myman`](myman) reads the file list in [`mymanfolder`](mymanfolder),
and allows the user to utilize TAB completion to select the manual (file) needed.
The script tries to open the file based on the OS default application for the
specified file and filetype.

## Installation

1. Make sure Python (v. 3) is installed
2. Place (and/or rename) the folder `mymanfolder` so some location
3. Edit the script `myman` to include the path to your `mymanfolder`
4. Place the script `myman` in your PATH.
5. Start adding manuals to the `mymanfolder`

## Example

    $ myman
    Enter manual name (use TAB completion): <TAB> <TAB>
    RegExpr           latex-card        perl-regexp-card  python-card       svn-card
    html-card         perl-card         python            r-card            vi-card
    Enter manual name (use TAB completion):p <TAB> <TAB>
    perl-card         perl-regexp-card  python            python-card
    Enter manual name (use TAB completion): pe <TAB>
    Enter manual name (use TAB completion): perl- <TAB> <TAB>
    perl-card         perl-regexp-card
    Enter manual name (use TAB completion): perl-c <TAB>

## Note

The script is a based on a version written in Perl back in 2004.
Thanks to Jeet Sukumaran for python inspiration.

Untested (Mon 12 sep 2022) on macos and MS Windows.

## Licence

MIT

