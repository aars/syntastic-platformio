# syntastic-platformio.vim

A simple plugin to configure syntastic c/cpp for platformio projects.

## how does it work?

It looks up the directory tree for `platformio.ini`, 
and tries to parse `.gcc-flags.json` from that directory,
then configures syntastic accordingly.

## Installation

This plugin is provided as is. It works directly under pathogen. I'm not sure 
about other plugin managers.
