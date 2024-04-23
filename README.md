# Caffeine Giant
Landing Page for Caffeine Giant Games Studio. 

## Links
* [GitHub Pages](https://hsinclair6140.github.io/caffeine-giant/)
* [Project Template](https://github.com/hsinclair6140/project-template)
* [Asset Factory](https://github.com/hsinclair6140/asset-factory)
* [Unreal Project Bot](https://github.com/hsinclair6140/unreal-project-bot)

## Projects
[Project 1]()

## Documentation
This repository contains Sphinx code that can be edited, built, and published to a GitHub Pages website. 
See the [GitHub Pages](https://hsinclair6140.github.io/caffeine-giant/) for the built results of this documentation. 

## Building the Docs Through GitHub Actions Automation
Merging any non-main branch into main will trigger a GitHub Action that will build and publish the docs to [GitHub Pages](https://hsinclair6140.github.io/game-development-process/). 'pages' is the branch that will be published and should not be used for any other reason.

## Building the Docs Locally
The following section provides instructions on how to build the HTML locally. This step is not necessary, but may be useful for a quick preview of what the built HTML may look like.

### Dependencies
#### Python
##### Version
[Python 3.11-64 bit](https://www.python.org/downloads/windows/).

##### Python Package Dependencies
To automatically create a Python virtual environment to build the Sphinx docs, run doc_env_setup.bat.

To manually install the required Python dependencies to an existing Python environment, run the following command:

`pip install -r doc_requirements.txt`

### Build
To build the Sphinx code, run the following command in the root of the project:

`sphinx-build doc _build`

The HTML will be built to _build folder and can be preview by opening the HTML files within.
