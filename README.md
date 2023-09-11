# Python Sample: Enrich Names CSV

This repository contains an example [Python3](https://www.python.org/) [Jupyter
Notebook](https://jupyter.org/) that uses the
[HumanGraphics](https://www.humangraphics.io)
[API](https://developer.humangraphics.io) to enrich name-containing records stored in CSV.

## Setup

The notebook uses `$HOME/.humangraphics` as a special file for storing credentials. The `.humangraphics.example` file shows the format of that file. Before running the notebook, users should copy the example file to their local `$HOME` directory, rename it to `.humangraphics`, and fill in the appropriate facts with values from their HumanGraphics subscription.

## Files

* `.humangraphics.example` -- An example credentials file.
* `records.example.csv` -- An example set of names to enrich. Users can add and remove columns as needed as long as the `name` column remains and stores the name to process. Any additional columns are passed through to the result.
* `enriched-records.example.csv` -- An example output of the notebook for the given example inputs.
