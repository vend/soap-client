# Versions

## v1.0.0-rc1

### Updates

 * Removed support for EOL'd PHP versions (5.3, 5.4, 5.5)
 * Added testing under PHP 7.0
 * Fix for phpforce/soap-client#28

## v0.0.0

### Comments

* Initial pre-release tag for composer so people don't have to track master in their packages.
* Additionally this allows aliasing in composer.json, allowing people to point at this repository and automatically 
track the main repository again when it releases anything higher than 0.0.0

### Updates

 * Added Quality Assurance Tools to composers require-dev, as well as configuration files for each

### Bug Fixes

 * Merged dkorrel/soap-client bd635e84a62067b0013f89324b797b88de0d6939 to fix update/upsert
   * Altered this to make it PSR-2 compliant
