# Awesome Python Code Formatters

A curated list of awesome Python code formatters

## Code formatters

+ [2to3](https://docs.python.org/2/library/2to3.html) -- Automated Python 2 to 3 code translation.
+ [add-trailing-comma](https://github.com/asottile/add-trailing-comma) -- A tool to automatically add trailing commas to calls and literals.
+ [autopep8](https://github.com/hhatto/autopep8) -- A tool that automatically formats Python code to conform to the PEP 8 style guide.
+ [black](https://github.com/python/black) -- The uncompromising Python code formatter.
+ [com2ann](https://github.com/ilevkivskyi/com2ann) -- Translates type comments to type annotations.
+ [decrapify](https://github.com/craigds/decrapify) -- Some scripts that use pybowler.io for refactoring Python code.
+ [docformatter](https://github.com/myint/docformatter) -- Formats docstrings to follow PEP 257.
+ [eradicate](https://github.com/myint/eradicate) -- Removes commented-out code from Python files.
+ [pep585-upgrade](https://github.com/snok/pep585-upgrade) -- Automatically upgrade your type hints to the new native types implemented in PEP 585.
+ [prettier](https://github.com/prettier/prettier) -- An opinionated code formatter, not only for Python.
+ [pybetter](https://pypi.org/project/pybetter/) -- Tool for fixing trivial problems with your code.
+ [pyupgrade](https://github.com/asottile/pyupgrade) -- A tool to automatically upgrade syntax for newer versions of the language.
+ [reindent.py](https://github.com/python/cpython/blob/master/Tools/scripts/reindent.py) -- Change Python (.py) files to use 4-space indents and no hard tab characters.
+ [teyit](https://github.com/isidentical/teyit) -- Unittest assertion formatter.
+ [unify](https://github.com/myint/unify) -- Modifies strings to all use the same quote where possible.
+ [yapf](https://github.com/google/yapf) -- Yet another Python code formatter from Google.
+ [flynt](https://github.com/ikamensh/flynt) -- A tool to automatically convert old string literal formatting to f-strings.

## Imports formatters

+ [absolufy-imports](https://github.com/MarcoGorelli/absolufy-imports) -- Convert relative imports to absolute.
+ [autoflake](https://github.com/myint/autoflake) -- Removes unused imports and unused variables as reported by pyflakes.
+ [isort](https://github.com/timothycrosley/isort) -- A Python utility / library to sort imports.
+ [pycln](https://github.com/hadialqattan/pycln) -- Removes unused imports.
+ [reorder-python-imports](https://github.com/asottile/reorder_python_imports) -- Reorders imports.
+ [unimport](https://github.com/hakancelik96/unimport) -- Removes unused imports.

## Improvements and wrappers

+ [black-macchiato](https://github.com/wbolster/black-macchiato) -- paints part of your python code black.
+ [blacken-docs](https://github.com/asottile/blacken-docs) -- Run `black` on python code blocks in documentation files.
+ [brunette](https://github.com/odwyersoftware/brunette) -- best practice Python code formatter, wrapper around `black` with improvements.
+ [gray](https://github.com/dizballanze/gray) -- wrapper around `isort`, `pyupgrade`, `add-trailing-comma`, and `unify`.
+ [jupyterlab_code_formatter](https://github.com/ryantam626/jupyterlab_code_formatter) -- A universal code formatter for JupyterLab.
+ [pyformat](https://github.com/myint/pyformat) -- wrapper around `autopep8`, `autoflake`, `docformatter`, and `unify`.
+ [shed](https://github.com/Zac-HD/shed) -- wrapper around `autoflake`, `black`, `com2ann`, `isort`, `pybetter`, `pyupgrade`, and `teyit`; with fully automatic configuration and `blacken-docs`-inspired support for code in docs files too.

## Libraries and refactoring

+ [bowler](https://github.com/facebookincubator/Bowler) -- Safe code refactoring for modern Python.
+ [fissix](https://github.com/jreese/fissix) -- backport of [lib2to3](https://docs.python.org/2/library/2to3.html), with enhancements.
+ [massedit](https://github.com/elmotec/massedit) -- edit text files with Python.
+ [rope](https://github.com/python-rope/rope) -- a python refactoring library.
+ [undebt](https://github.com/Yelp/undebt) -- tool for performing massive, automated Python code refactoring.
+ [LibCST](https://github.com/Instagram/LibCST) -- LibCST parses Python 3 source code as a CST tree that keeps all formatting details (comments, whitespaces, parentheses, etc). It's useful for building automated refactoring applications and linters.

## Code generators

This list doesn't contain tools that generate code, type annotations, comments etc. The difference is that code formatters transform your code from one form into another (which should be safe if the tool is stable) while code generators bring something totally new. If you're looking for code generators, check out the following links:

+ [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing#helper-tools-to-add-annotations-to-existing-code) for tools to generate type annotations.
+ [hypothesis ghostwriter](https://hypothesis.readthedocs.io/en/latest/ghostwriter.html) for generating tests.
