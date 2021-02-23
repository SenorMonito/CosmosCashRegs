# CosmosCashRegs


## Pre-requisites

- GNU make
- Pandoc
- Inter is Tendermint font. Can download from here: https://fonts.google.com/specimen/Inter


## Usage

- To create new report go just need to run `make buildmd` from top level directory
- To clean outputs run `make clean`

## notes

- This use a latex template from [here](https://github.com/Wandmalfarbe/pandoc-latex-template)
- Configuration is in two places:
    - The make file - this sets the file locations for source and output
    - The top of the report markdown in LiqMod.md, which sets font, footers, backgrounds etc. Check the above template for examples. 
