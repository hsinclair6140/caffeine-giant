# game-development-process
Process Definition for Video Game Development.

## Overview
This repository contains Sphinx code that can be edited, built, and published to a GitHub Pages website. 
See the [GitHub Pages](https://hsinclair6140.github.io/game-development-process/) for the built results of this documentation. 

## Building the Docs Through GitHub Actions Automation
Pushing to this repository on any non-main branch will trigger a GitHub Action that will build and publish the docs to [GitHub Pages](https://hsinclair6140.github.io/game-development-process/).

## Building the Docs Locally
The following section provides instructions on how to build the HTML locally. This step is not necessary, but may be useful for a quick preview of what the built HTML may look like.

### Dependencies
#### Python
##### Version
[Python 3.11-64 bit](https://www.python.org/downloads/windows/).

##### Python Package Dependencies
The requirements.txt file contains all Python dependencies needed to build the Sphinx documentation locally. Run the following command using the desired Python environment:

`pip install -r requirements.txt`

### Build
To build the Sphinx code, run the following command in the root of the project:

`sphinx-build doc _build`

The HTML will be built to _build folder and can be preview by opening the HTML files within.
