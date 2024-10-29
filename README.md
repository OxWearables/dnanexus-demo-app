# DNAnexus Demo App

### Gotchas
- *dxapp.json*: `regionalOptions` should match your DNAnexus account region.
- *dxasset.json* and *dxapp.json*: Should `distribution`, `release`, `version` match?
- *dxasset.json* and *dxapp.json*: Only `"version": "0"` seems to work if `"release": "20.04"`
- *dxasset.json*: Beware of Python versions and package support. For example, Ubuntu 20.04 ships with Python 3.8, then only `numpy<=1.24.4` will be supported in the asset.