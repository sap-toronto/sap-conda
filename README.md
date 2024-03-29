# wsp-sap-conda

A customized Conda installation for WSP Canada's System Analytics for Policy (SAP) group.

Please refer to the `construct.yaml` file for a list of packages that are bundled with the installer. The installer is intended to provide a base installation of Conda containing packages that are commonly used by all members of SAP. Specific packages used by certain individuals can be installed through the typical pip/conda routes.

This GitHub repo contains the files required to build the custom Conda installer using [Constructor](https://github.com/conda/constructor). When running Constructor, it will obtain the latest versions of the Python packages specified in the `construct.yaml` file.

New releases will (try to) fall in line with new Conda releases as they are published.

Please visit the [releases](https://github.com/bccheung/wsp-sap-conda/releases) page to download the *SAPconda* custom installer.
