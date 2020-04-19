# omf-repository

Oh My Fish personal package repository

Custom package repository for the Oh My Fish Fish shell framework.

This repository contains a list of my personal Fish packages that can be installed by name using Oh My Fish. 

# Repository format

Packages are referenced in the repository using property files located in the packages/ directory. The actual code of each package is stored in separate, individual Git repositories maintaned by the package mantainer themselves. This keeps control of the package in the owner's hands, but still allows easy sharing of the package.

The name of each property file indicates the package name, and the various properties in the file describe the package and how it can be installed. These are the properties currently used:

type: The type of package. Can be plugin or theme.
repository: A cloneable Git URL to the package source repository.
maintainer: The name and email of the maintainer of the package.
description: A short description of the package.