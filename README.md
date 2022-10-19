# About

Repository for a school project from [BUT](https://www.vut.cz/en).

## Releases

Releases are published using Github actions. Everytime there is a push to master a new release is published and contains a built pdf file. A release can be found [here](https://github.com/SamoKopecky/minsp-project/releases). Each release is tagged with the time the push to main was made.

## Build

Install the required dependencies using [this guide](https://gist.github.com/ogajduse/ad4db70f9a6d396a133e6fd68f1a1204). After that install [latexmk](https://mg.readthedocs.io/latexmk.html).

To generate a pdf run:

```sh
latexmk -pdf prace.tex
```
