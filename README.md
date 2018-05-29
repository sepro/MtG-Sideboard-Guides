# MtG Sideboard Guide generator

This notebook will guide you how to create concise sideboard guides, printable on a 63 x 88 mm 
standard card. It will load the data from a tab delimited text file, use **pandas** to transform 
the data to a matrix. Next, using a **jinja2** template, these data are turned into an **SVG** image.

![example guide](./img/example_guide.png "Example Guide")

## Example data

The included example data are for [BUG Delver](./img/BUG_index.png), [Death and Taxes](./img/death_and_taxes_index.png),
 [Lands](./img/Lands_index.png) and [Sneak 'n Show](Show_and_Tell_index.png).

