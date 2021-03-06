[![Build Status](https://travis-ci.org/zoependlington/pdx-ontology.svg?branch=master)](https://travis-ci.org/zoependlington/pdx-ontology)
[![DOI](https://zenodo.org/badge/13996/zoependlington/pdx-ontology.svg)](https://zenodo.org/badge/latestdoi/13996/zoependlington/pdx-ontology)

# pdx-ontology

This ontology... YOUR DESCRIPTION HERE

## Build a OLS docker instance with ontologies in

```
docker build . -t pdxo-ols
docker run -p 8080:8080 -t pdxo-ols 
``` 

OLS should now be running at http://localhost:8080

## Versions

### Stable release versions

The latest version of the ontology can always be found at:

http://purl.obolibrary.org/obo/pdxo.owl

(note this will not show up until the request has been approved by obofoundry.org)

### Editors' version

Editors of this ontology should use the edit version, [src/ontology/pdxo-edit.owl](src/ontology/pdxo-edit.owl)

## Contact

Please use this GitHub repository's [Issue tracker](https://github.com/zoependlington/pdx-ontology/issues) to request new terms/classes or report errors or specific concerns related to the ontology.

## Acknowledgements

This ontology repository was created using the [ontology starter kit](https://github.com/INCATools/ontology-starter-kit)
