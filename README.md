# README

This extension adds syntax highlighting and snippets support for the excellent
[Factor](https://factorcode.org/) concatenative programming language.

## Snippets

Here is a list of included snippets

- bi
- cleave
- cond
- functor
- if
- ::
- let
- spread
- tri
- : (word definition)
- "
- [
- [1


## Factor listener integration
there is a vscode integration available that is not in the latest release
(0.98 at time of writing). if you are running factor from **sources** / dev builds,
You can do the following to fire up vscode from your scaffold directly:

    EDITOR: editors.visual-studio-code
    \ word edit
    "math" edit


All the hard work was already done thanks to the factor/misc/Factor.tmbundle files,
This extension was generated from them. Thanks to whoever made that!
All images and factor material is owned by Factor.

See [Factor license.txt](https://factorcode.org/license.txt) for BSD license.
See the [Factor Repository](https://github.com/factor/factor)

For more information on Factor checkout the [Factor site](https://factorcode.org/)

