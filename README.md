# cheatset

[![Gem Version](https://badge.fury.io/rb/cheatset.png)](http://badge.fury.io/rb/cheatset)

Generate your own cheat sheets as docsets for [Dash](http://kapeli.com/dash) from markdown files. 

## Installation

    $ sudo gem install cheatset

Note: this requires the Xcode Command Line Tools to be installed. Install them using this:

    $ xcode-select --install
    
If it still doesn't work, it most likely means you got Xcode 5.1 which just broke a lot of gems. See [Issue #2](https://github.com/Kapeli/cheatset/issues/2#issuecomment-37369283) for more details and a workaround.

Then download ``mmd2cheatset.rb`` script from this repo and place it somewhere in your path. Make it executable with ``chmod a+x mmd2cheatset.rb`` .

## Usage

Write a markdown file containing your cheat sheet data, then convert this file to a docset by calling

    $ mmd2cheatset.rb cheatsheet.md

## Thanks

[Bretterpstra](http://brettterpstra.com/2014/03/21/dash-docsets-from-multimarkdown/) for the initial code of ``mmd2cheatset.rb``.
