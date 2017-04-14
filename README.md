# bibkeys

Find matching citations in two BibTeX files. The matched keys are printed to the screen.

## Dependencies

`bibkeys` depends on `bibtexparser`. Install this Python module using: 

```bash
pip install bibtexparse
```

## Usage

```bash
# Basic usage
bibkeys REFERENCE.BIB OTHER.BIB

# Getting help
bibkeys --help
```

## Options

*   `--diff`

    Print only the keys that are different.
