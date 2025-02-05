# Changelog

## 1.0 (July 19th, 2012)

* Initial release. [JI/MS]

### 1.1 (August 21st, 2012)

* Added /get_key functionality to translate a legacy Mediaburst username and password into a new Clockwork API key. [JI]
* Deprecated `checkCredit()` and replaced with `checkBalance()` [JI]

### 1.2 (September 7th, 2012)

* Added various new Wordpress classes, including the Clockwork_Plugin class for writing plugins based on Clockwork. [JI]

### 1.3 (September 18th, 2012)

* Added `is_valid_msisdn()` method. [JI]

#### 1.3.1 (November 13th, 2012)

* Updated `is_valid_msisdn()` method to handle 9-digit phone numbers, e.g. Norway. [JI]

#### 1.3.2 (December 18th, 2015)

* Switched license to MIT rather than ISC as people haven't heard of ISC and they're very similar
* Added account type to balance checks.

#### 2.0.0 (November 30th, 2017)

* We have added support for composer as a package manager and remove a lot of old code.

#### 2.0.1 (January 29th, 2022)

* New fork by Rock & Scissor to add support for php 7.4+ now that Mediaburst has been acquired by Textanywhere
* Fixed issue with balance check to make sure tagName exists as a property when looping through DOM items.
