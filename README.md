# RISC OS Community Utilities collection

This repo contain a collection of command line utilities required by most of the projects in this organisation and that can be useful to others as well.

## Which utilities are contained here?

To check each single utility please have a look at the directory `src`. 

If you are willing to help completing them please ensure you git pull the `develop` branch. To contribute please make sure you have read the contributing guide you can fine [here](CONTRIBUTING.md).

For more info check the README.md you'll find in each component directory in `src`.

## How to build them?

We are working to ensure they build with both RISC OS major compilers:

* ROOL DDE
* GNU GCC

So, in order to compiler them you must have installed at least one of the two compilers.

To compile the whole lot just click (fromt he RISC OS Desktop Filer) on the file MkDDE to build using ROOL DDE and mkGCC to build using GNU GCC.

Tests should also be compiled with the components

