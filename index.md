---
layout: default
---

### Welcome to the Philharmonic homepage.

[![Build Status](https://travis-ci.org/philharmonic/philharmonic.svg)](https://travis-ci.org/philharmonic/philharmonic)
[![Coverage Status](https://img.shields.io/coveralls/philharmonic/philharmonic.svg)](https://coveralls.io/r/philharmonic/philharmonic)

Philharmonic is primarily a cloud simulator focused on realistically
modelling geographically-distributed data centers influenced by real time
electricity prices and temperature-dependent cooling efficiency that we call
*geotemporal inputs*.

For a part of the functionality (namely VM pausing) it can interact with a
real OpenStack deployment and it offers a way to collect power measurements from
Eaton wattmeters. This experimental approach is no longer
the focus of development, however.

### Installation

For installation details see
[these instructions](https://github.com/philharmonic/philharmonic#installation).

### Usage

Generate the random input data.

    python simulate.py inputgen --conf=philharmonic.settings.fbf

You can then run the simulation.

    python simulate.py run --conf=philharmonic.settings.fbf

### Datasets

The datasets of real-time electricity prices and temperatures that can be used
in the simulation are described
[here](https://github.com/philharmonic/philharmonic/tree/master/io/geotemp).

### Authors and Contributors

The simulator was created by Dražen Lučanin (@kermit666)
while working as a research assistant at the
[Vienna University of Technology](http://www.infosys.tuwien.ac.at/staff/drazen/).

### Support or Contact

Interested in using Philharmonic and having trouble with it? Feel free to
[file a ticket](https://github.com/philharmonic/philharmonic/issues) or
[contact me directly](http://www.infosys.tuwien.ac.at/staff/drazen/).
