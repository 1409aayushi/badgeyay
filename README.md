fossasia-badge-generator
========================

This script generates the badges for the FOSSASIA conference.

[Download Current Badges](https://niccokunzmann.github.io/download_latest/all-badges.pdf)
[![Build Status](https://travis-ci.org/niccokunzmann/fossasia-badge-generator.svg?branch=master)](https://travis-ci.org/niccokunzmann/fossasia-badge-generator)

Specification
-------------

### Input

- The input is a set of csv files in the same folder, UTF-8.
- The csv file is named after the badge type to take. 
  Example: `vip.png.csv` uses the picture `vip.png`.
- The CSV has up to 4 columns for the name and the twitter handle.
  They will be filled if this number is filled:
  - `__X_`
  - `__XX`
  - `_XXX`
  - `XXXX`

### Output

The output file is svg / pdf / multipage pdf of size A3.
Each badge has the size A6.
The outputs are in a folder derived form the input csv.

### Usage

You need Ubuntu.

You can run the `merge_badges.sh` file.
It generates badges for every csv file and combines them to one.

Related Repositories
--------------------

- https://github.com/fossasia/fossasia-artwork/tree/master/Badges/Badges-2017
