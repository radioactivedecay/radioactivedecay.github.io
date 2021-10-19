# radioactivedecay / radioactivedecay.github.io

Repository for hosting the radioactivedecay documentation using GitHub Pages.

## Updating the docs

The docs use the [Sphinx](http://www.sphinx-doc.org/en/master/) package with
the ReadTheDocs [theme](https://sphinx-rtd-theme.readthedocs.io/en/stable/).

The docs source is located in the
[`docs` directory](https://github.com/radioactivedecay/radioactivedecay/tree/main/docs)
within the main package repository.

Use the `Makefile` in that directory to compile static HTML pages by

```bash
make html
```

The HTML files are created locally in the `build` sub-directory. Copy those files
to the `docs` directory of this repository on the `main` branch. Push the
new commit to GitHub.
[radioactivedecay.github.io](https://radioactivedecay.github.io) will
automatically update with the new files.
