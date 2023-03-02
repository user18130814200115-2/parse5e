# parse5e

This repository contains a set of tools for preparing and parsing data for
[Dungeon sheets](https://github.com/canismarko/dungeon-sheets).

## Spells
You must obtain a csv file containing every spell you want to include.

This file can be obtained from https://5e.tools/spells.html.
Under `Filter` select your sources of preference, then at the bottom of the
page, click `Table view` and then `Download CSV`.

The file can then be streamed into the `parse5e` script for instance by running
`cat Spells.csv | parse5e`.
