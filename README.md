# Test262 Python Harness

### Usage

This package exposes the following files for public use:

- `test262.py` - an executable designed to execute Test262 tests. For usage
  instructions, invoke this executable with the `--help` flag, as in:

      $ test262.py --help

- `parseTestRecord.py` - a module defining a `parseTestRecord` function which
  creates an object representation of the metadata encoded in the frontmatter
  of a given Test262 test file.

### Tests

Run the following command from the root of this projcet:

    $ python -m unittest discover test
