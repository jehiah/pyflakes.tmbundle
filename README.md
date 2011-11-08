pyflakes TextMate Bundle
========================

TextMate bundle with python validation on save. (validation done by pyflakes)

Prerequisites
=============

This bundle requires pyflakes to do syntax validation. There are several versions of pyflakes floating around on the net. I prefer this version:

    pip install git+https://github.com/jehiah/pyflakes.git

Installation
============

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/jehiah/pyflakes.tmbundle.git "pyflakes.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
