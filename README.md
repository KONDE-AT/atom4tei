# Atom4TEI

A loosely structured collection of potentially useful packages to turn [Atom](https://atom.io/) editor for working with XML/TEI documents. 

## linter-autocomplete-jing

* https://atom.io/packages/linter-autocomplete-jing

### functions
> Auto complete and on-the-fly validation of XML documents against RELAX NG (compact, XML), Schematron (1.5, ISO), W3C Schema (XSD 1.0) and DTD

### pros
* published on [Atoms Package Repo](https://atom.io/packages)


## atomic-tei

* suggested by Christian Wagner
* https://github.com/neelsmith/atomic-tei

### functions

* validation on the fly
* suggestions of allowed elements
* some (not TEI specific) snippets

### pros

* once the package is installed, it's functionalities can be triggered easily by simply changing the grammar
* package ships TEI-Schema

### cons

* not published on [Atoms Package Repo](https://atom.io/packages) -> No installation from within Atom possible
* depends upon [linter-autocomplete-jing](https://github.com/aerhard/linter-autocomplete-jing)

## atom-xsltransform

https://atom.io/packages/atom-xsltransform

### functions
>Transform XML Documents using XSL Stylesheets.
By default, this package uses JavaScript native XSLTProcessor, without any OS dependent tools.
If you would prefer to use a custom XSLT transform tool, you can specify the command in Settings.

## cons
* Unlike oXygen you can't create/store/configure any transformation scenarios.

## eXist-db-packag

https://atom.io/packages/existdb

## functions
(copied)
* tree view to browse the contents of the database
open, edit and save files stored remotely in the database
* syntax highlighting and linting of XQuery scripts (based on xqlint)
autocomplete showing all functions and variables which are in scope, including those from imported modules
* a hyperclick provider to navigate to the definition of a function, even if located in an imported module
refactoring of variables
* XML auto-close tags, tag renaming
* execution of XQuery scripts within the editor
* symbols view to navigate to functions and variables which are in scope for the current XQuery

### comments

* An eXist-db package needs to be installed to the database.
* I noticed that e.g. invalid files/scripts are not stored although the editor interface claims it. But not further investigated yet.

## atom-entity-ac

https://github.com/acdh-oeaw/atom-entity-ac

### functions

Provides autocomplete for entities fetched from an eXist-db endpoint. Basically the same what the [ediarum oXygen plug-in](https://github.com/telota/ediarum/) does.

### pros

* own development -> full control

### cons

* own development
