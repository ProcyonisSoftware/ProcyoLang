# ProcyoLang

![ProcyoLang Logo](https://raw.githubusercontent.com/ProcyonisSoftware/ProcyonComponentsLogos/06fa759e799c31f77d4e35e31bd7c8dbe6b5c5bd/ProcyoLang.png)

ProcyoLang Interpreted Programming Language developed by [Gautham Nair](https://github.com/gauthamnair2005)

<<<<<<< Updated upstream
Latest : `ProcyoLang 1.0.2 Beta 1`
=======
Latest : `ProcyoLang 2.0.1 Beta 2`
>>>>>>> Stashed changes

Tools Included:

* ProcyoLang Script Interpreter (pl.py)
* Sample ProcyoLang Source Code (prog.pcl)

## ProcyoLang Interactive Shell vs ProcyoLang Script Interpreter

### ProcyoLang Interactive Shell

⚠️ NO LONGER SUPPORTED, UPDATED AND PROVIDED..!

The ProcyoLang Interactive Shell was a command-line interface that allowed users to interact with ProcyoLang, however, it lacked few features/commands present in ProcyoLang Script Interpreter, like actual `for` loop, `if-else` statements, etc.

### ProcyoLang Script Interpreter

The ProcyoLang Script Interpreter is a command-line tool that runs ProcyoLang Source Files (.pcl), which is supplied to it as argument.

#### Usage

`python pl.py prog.pcl`

## What's new in Beta 2?

* Removed unnecessary lines and modules import.
* Removed incomplete features.
* ProcyoLang renaming to Linea in Beta 3.
* Next version : Linea 0.1 Beta 3.
* Will be managed in Gautham Nair's [Linea](https://github.com/gauthamnair2005/Linea) repository.


## What was new in Beta 1?

* Entered Beta stage, comparatively stable than Alpha builds.
* Fixed known bugs.
* Added support for importing libraries using `use <modulename>`.

## What was new in Alpha 10?

* Improved array declaration.
* Experimental support for arrays in for loop.
* Fixed known bugs.

## What was new in Alpha 9?

* For loop code refactor.
* Added support for more operations in for loop.
* Improved error handling in ProcyoLang Script Interpreter.
* Interactive mode will be removed from Beta releases, which will arrive after Alpha 10.

## What was new in Alpha 8?

* Added support for simple `if-else`.
* We stopped updating the Interactive Shell with newer commands and script-specific features like loops, conditional statements, etc, as we promote and recommend the Script Interpreter. However, we will still provide the Interactive Shell in downloads and repository and not delete it.
* We stopped binary releases of pre-release versions of ProcyoLang, we will restart the binary executable release while this project reaches stability and enters stable or release-preview state.

## What was new in Alpha 7?

* Added support for `till` and `noDuckTill` member operators in `for` loop.
* Updated `input` to actually take input and store it in the specified variable.
* Added new string space escape sequence `|s|` in `for` loop and `input` routines.
* Fixed known bugs.

## What was new in Alpha 6?

* Added support for "real `for` loop", with print integer, string or iterating variable value support.
* Fixed few bugs.
* Removed old, fake `for` and `xfor` commands.
* Started maintaining proper `README.md`.
