# Dice Roll Distrubution

## Overview

A Jupyter Notebook that randomly generates values for `die_count` dice with `die_sides` amount of sides `iterations` times and finds the sum. The distribution is then plotted with a bar chart using [Matplotlib](https://matplotlib.org/stable/index.html)

<br>

### Examples

<div style="display: flex; justify-content: space-evenly">

<div style="display: flex; flex-direction: column; align-items: center;">
    <img src="./docs/dice_plot 2d,6s,100000i.png">
    <caption >2 6-sixed dice, 100000 times</caption>
</div>

<div style="display: flex; flex-direction: column; align-items: center;">
    <img src="./docs/dice_plot 3d,5s,50000i.png">
    <caption >3 5-sixed dice, 50000 times</caption>
</div>

<div style="display: flex; flex-direction: column; align-items: center;">
    <img src="./docs/dice_plot 4d,4s,20000i.png">
    <caption >4 4-sixed dice, 20000 times</caption>
</div>

</div>


## Options

- Number of dice - `die_count`
- Sides on each dice - `die_sides`
- Number of trials - `iterations`

# Todo

- Make graph height adapt to largest value rather than `iterations/(die_sides/die_count*1.5)`
- Adjust graph and bar width for larger `die_count` and `die_sides` values 



## Acknoledgements
Created by Nasser Kessas

## Contributing
PRs accepted, feel free to dive in! [Open an issue](https://github.com/nasserkessas/js-sidescroll-engine/issues/new) or submit PRs.

Dice Roll Distribution follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.