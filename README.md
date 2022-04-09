# Krypton Toolkit Help Files

Welcome to the Krypton Toolkit help files repository!

## What is this repository for?

The Krypton Toolkit help files repository contains all the files required to create the end-user documentation for the Krypton Toolkit projects. You can download the latest files [here](https://github.com/Krypton-Suite/Help-Files/releases).

## Prerequisites

In order to build the documentation, you **must** have the following:-

  - The latest Krypton Toolkit DLL/XML files
  - The latest [Sandcastle Help File Builder](https://github.com/EWSoftware/SHFB/releases)
  - Time (plus a beverage of your choice ;-))
  
## To build

  - Open `Source\Standard Toolkit\Full Documentation\Full Toolkit Documentation\Full Toolkit Documentation.shfbproj`
  - Remove **all** entries under `Documentation Sources`
  - Add the current DLL/XML files to `Documentation Sources`
  - Update the version number in `Help File` -> `Help file version`
  - Build - Note: this will take some time
  
The generated output will be located in `Source\Standard Toolkit\Full Documentation\Full Toolkit Documentation\Help`. Rinse & repeat for the Extended Toolkit.