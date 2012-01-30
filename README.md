# solr-indexing

## A pluggable programmatic framework for streamlining solr indexing jobs

solr-indexing is a Pythonic programmatic framework for defining indexing jobs with minimum fuss. The framework introduces several notions
that abstract some of the details of typical medium-to-large-scale solr indexing tasks, including import of raw data (e.g from RDBMS) as well
as indexing into a sharded installation (using some hash-based or rule-based scheme).

## Requirements

All the requirements should be automatically installed when using the setuptools setup.py script

## Installation

To install the framework, use the included setup.py, e.g:

```bash
python setup.py install
```

This will by default install all the framework scripts into your global python environment, making
them available in your system PATH. 
You could also potentially install the framework under a Python [virtualenv](http://pypi.python.org/pypi/virtualenv).

## Configuration

TODO

## Example Usage

TODO

## API Documentation

TODO

## Credits

solr-indexing was created by [Adam Ever-Hadani](http://github.com/adamhadani/)

## Contact

Adam Ever-Hadani

- http://github.com/adamhadani
- http://www.linkedin.com/in/adamhadani
- adamhadani@gmail.com

## License

This software is available under the Apache license 2.0. See the LICENSE file for more info.
