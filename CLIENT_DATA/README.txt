The initial version of this package was created by Eric Esser, Wissenschaftszentrum Berlin für Sozialforschung (Berlin Social Science Center) and published at the DFN-Repository of the initiative OPSI4instituts: https://opsi.wzb.eu
Contact, questions and suggestions: eric.esser@wzb.eu / opsi@wzb.eu

REQUIREMENTS
------------
- Possession of a license file or serial number for full version is required

HOWTO
-----
1. Install the package on the opsi server on the command line by "opsi-package-manager -i -p ask dfn_f4transkript_<version-/packagenumber>.opsi".
2. If a concurrent license is aquired, copy your "licence.dat" file in the "custom" directory in the project folder of the product on the OPSI server.

PROPERTIES
----------
* custom-post-deinstall: define filename for include script in custom directory after deinstallation.
* custom-post-install: define filename for include script in custom directory after installation.
* desktopicon: generate or delete desktop icon.
* kind-of-license: defines the kind of license. "opsi-property" uses the serial from the property "licensekey", "licensepool" uses the serial from the license pool of the license module of opsi. The according license pool has to be specified in the property "licensepoolname". "license-file" uses a "licence.dat" file whoch has to be placed in the custom folder on the opsi server and is used für concurrent licenses. "testversion" will install the program as test version.
* licensekey: the serial of the software. Is needed if the property "kind-of-license" is set to "opsi-property".
* licensepoolname: the name of the licence pool of the license module of opsi. Is needed if the property "kind-of-license" is set to "licensepool".