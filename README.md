pystock-dailycrawl
==================

A simple script that performs daily crawl with `pystock-crawler`.

Installation
------------

Just download the [ZIP](https://github.com/eliangcs/pystock-dailycrawl/archive/master.zip)
and extract it, e.g.,

    wget https://github.com/eliangcs/pystock-dailycrawl/archive/master.zip
    unzip master.zip
    rm ./master.zip

Usage
-----

    $ ./dailycrawl --help
    pystock-dailycrawl 0.7.0
    Usage:
      dailycrawl [-b S3_BUCKET] [-c SCRIPT_DIR] [-w WORKING_DIR] [-s START_DATE] [-e END_DATE] [-o OUTPUT_DIR]
      dailycrawl (-h | --help)
      dailycrawl (-v | --version)
