# sphinx-template

A template sphinx project using the rtd theme setup for Github Pages

## Requirements
``` bash
pip install sphinx sphinx_rtd_theme
```

## Usage

1. Run `make html` from the repository's root directory. This will generate a `build` directory and also copies necessary files to the `docs` directory for serving the site with Github Pages.

Note: You must direct Github pages to build from the docs directory 
`Settings->Pages->Build and Deployment->Branch`
