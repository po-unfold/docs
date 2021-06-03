---
layout: main
---

# {{site.game}}
*remembering the pandemic*

## General

<video width="320" height="240" autoplay controls style="border: 1px solid black" title="video (loading)">
  <source src="/trailer_short.mp4" type="video/mp4">
	<span style="color:red">Your browser does not support inline video. Click <a href="/trailer_short.mp4">here</a> to view seperately.</span>
</video>

{{site.game}} is a game about a teenager's experience throughout the Covid-19 pandemic of 2020-1. Our game is made up of our personal experiences, and we strive to be as accurate as possible.

Confinement was created using Python. You can view the source code [here](https://github.com/po-unfold/game). 

## Usage (skip to [how to play)](#how-to-play)
There are a couple ways you can install our game:
 - Download the [Windows app](/windows)
 - Download the [Mac app](/mac)
 - Install using the <a href="https://pypi.org/project/pushing_outshoot_unfold/">package</a>:

	**Requirements:**
	- Python 3.6+
	- `pip`
  
	```bash
	pip3 install pushing_outshoot_unfold # install the package
	# you may need to use `pip` instead of `pip3`
	pou # run the game
	```
    
- Build from the <a href="https://github.com/po-unfold/game">source</a>:

	**Requirements:**
	*Only intended for \*nix users (MacOS, Linux, BSD). If you are on Windows, either TRY building this, or just use the download.*
	- Git
	- the Python `setuptools` module
	- `pip`
	- Python 3.6+
  
	```bash
	# checkout code
	git clone https://github.com/po-unfold/game.git
	cd game
	# install sailboat
	pip3 install sailboat # you may need to use `pip` instead
	sailboat build # build latest version
	cd dist # enter `dist` directory
	ls # view output files
	```
  
## How to play
Once you have installed the app, open it up by double clicking it, or by running `pou` in the command line if you used `pip`. A window should show, asking you if you would like to have sound.

Type either `1` or `0` for sound or no sound, and be sure to resize the window to the shape you would like it before hitting enter.

The game progresses day by day, with different scenarios each time. Some days will have interactive parts in them that you will have to complete to move on.

If at any time you would like to exit the game, simply push `ctrl+c` to exit. Your progress is not saved.
