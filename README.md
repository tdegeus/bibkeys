# bibkeys

Find matching citations in two BibTeX files. The keys from the reference file are printed together with the match keys from the reference files. The matching is attempted in the following order:

1.  `doi` (digital object identifier).
2.  `eprint` (arXiv identifier).
3.  `journal`, `volume`, `number`, and `pages`.

```bash
# Basic usage
bibkeys REFERENCE.BIB OTHER.BIB

# Getting help
bibkeys --help
```

## Options

*   `--diff`

    Print only the keys that are different.

## Dependencies

`bibkeys` depends on `bibtexparser`. Install this Python module using: 

```bash
pip install bibtexparse
```
