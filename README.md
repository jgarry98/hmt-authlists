# `hmt-authlists`

This repository hosts CITE Collections defining authority lists for the Homer Multitext project.

Collections are cataloged in [CEX format](https://github.com/cite-architecture/citedx) in the file [catalog/catalog.cex](catalog/catalog.cex).

For each collection, a file in the [data](data) directory has the contents in a `cex` file.

## Editing a collection

Collections should be edited in a local clone of this repository and validated before committing.

## Validating



Opening an sbt console:

    sbt console


Then, in the console, load the file `validate.sc`.  (Note the colon in  `:load` !)

    :load count.sc

Follow the on-screen instructions to validate a collection (e.g., `validate("place")`).
