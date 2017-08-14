# api-enumerations

This repository is a clone of **git@github.com:companieshouse/api-enumerations.git**.  It is used within **RFA2** as a submodule.

As we are importing this repository as a submodule within git, it makes sense to only import a clone of the repository that we can control.  That way we don't lose the ability to build or deploy new servers if the companies house repository ceases to exist.

This allows us to perform lookups without breaking changes being introduced outside of our control.
