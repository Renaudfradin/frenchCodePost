# frenchcodepostaux

![Screenshot](/images/FrenchCodePostaux.png)
![Screenshot](/images/CodePostaux.png)

This extension searches for cities or French postal codes after entering a postal code or a city

This extension searches for street addresses, postal codes or cities in France using the public open data tool https://adresse.data.gouv.fr/api-doc/adresse.
It works with either entering a street address, a postal code or a city name and provides an auto-completion with an AJAX UI.
The selector will be only exposed when the country for the address is based in France.
Attention: for the good functioning of the extension, check that the Country field is selected (check box to tick) in Administer > Localization > Address Settings > Address Editing

The extension is licensed under [AGPL-3.0](LICENSE.txt).

## Requirements

* PHP v7.2+
* CiviCRM 5.41, 5.42, 5.43

## Installation (Web UI)

Learn more about installing CiviCRM extensions in the [CiviCRM Sysadmin Guide](https://docs.civicrm.org/sysadmin/en/latest/customize/extensions/).

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl frenchcodepostaux@https://github.com/Renaudfradin/frenchCodePost/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/Renaudfradin/frenchCodePost
cv en frenchcodepostaux
```