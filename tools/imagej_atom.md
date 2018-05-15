---
layout: default
title: "Developing ImageJ Code with Atom"
post_author: "Harrington, K."
---

# Overview

`atom-imagej-mode` allows users to run ImageJ2 scripts from Atom.

`atom-imagej-mode` is available [here](https://github.com/kephale/atom-imagej-mode).

# Installing atom-imagej-mode

8. Enable the imagej-server update site (https://imagej.net/ImageJ_Server) in Fiji

1. In Atom:  
`Packages \ Settings View \ Install Packages/Themes`

2. Search for:  
`atom-imagej-mode`

3. Install the package

4. In Atom:  
`Packages \ Settings View \ Manage Packages`

5. Search for:  
`atom-imagej-mode`

6. Choose the `Settings` for `atom-imagej-mode`

7. Enter the location of your ImageJ binary, e.g.

- OS X: /Applications/Fiji.app/Contents/MacOS/ImageJ-macosx
- Linux: /home/username/Fiji.app/ImageJ-linux64
- Windows: c:\Fiji.app\ImageJ-win64.exe

(Author TODO: Could we autoimport these instructions from the atom-imagej-mode repository?)

# Usage

1. Launch ImageJ server, by either a) `Launch ImageJ` from `atom-imagej-mode`, or b) `Start server` from Fiji

2. Open or create a new script, but make sure it is saved **and** use a filename extension that is appropriate for your scripting language (the script is read from disk and the file extension is used to autodetect your language).
