# Speciality Ecodev

TYPO3 extension to ship common configuration specific to abteilung.

Please refer to Ecodev's Version for original reference.
https://github.com/Ecodev/speciality_ecodev.git

Add into `AdditionalConfiguration.php` something like:

```
// Include global configuration.
require_once (PATH_site . '../configuration/Settings.php');
require_once (PATH_site . 'typo3conf/ext/speciality_ecodev/Configuration/PHP/Typo3ConfVars.php');
```
