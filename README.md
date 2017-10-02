[![Build Status](https://travis-ci.org/andolf/r-duelyst.svg?branch=master)](https://travis-ci.org/andolf/r-duelyst) [![dependencies](https://david-dm.org/andolf/r-duelyst/dev-status.svg)](https://david-dm.org/andolf/r-duelyst?type=dev)

# /r/duelyst

A more organized version of the stylesheet for the [Duelyst subreddit](http://reddit.com/r/duelyst/).

## How to run

**First install Node**. The are various ways to do this depending on your platform; if you're using Mac OS X then [Homebrew](http://brew.sh) is your best bet. For Windows, installing it with [their own installer](https://nodejs.org/en/download/) is the way to go.
After that, you want to run `npm install` in a terminal in the project folder to get the LESS package.

**Now write some LESS code**. If you're unfamiliar with how LESS works, [check out their documentation](http://lesscss.org/).

**Compile!** Simply run `npm run css` which contains the LESS script for compiling the LESS files into a minified CSS file, which can then be pasted into the stylesheet textbox in the subreddit editing tool.
