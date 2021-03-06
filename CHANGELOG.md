# Changelog

All notable changes to `laravel-collection-macros` will be documented in this file

## 2.0.1 - 2016-01-24

- removed `split`, `partition` and `mapToAssoc`
- renamed `toAssoc` to `fromPairs`
- added `toPairs` and `withSize`

## 2.0.0 - 2016-01-24

**DO NOT USE, THIS RELEASE WAS WRONGLY TAGGED**

## 1.5.1 - 2016-01-24
- fixed tests

## 1.5.0 - 2016-11-29
- added `partition` method

## 1.4.4 - 2016-09-01
- `split` doesn't throw an error anymore when trying to split an empty collection

## 1.4.3 - 2016-08-30
- `version_compare` fix in 5.3 changes

## 1.4.2 - 2016-08-23
- updated for Laravel 5.3

## 1.4.1 - 2016-08-20

- maintenance release to kickstart Packagist after `composer.json` error

## 1.4.0 - 2016-08-20

- add `dump` macro

## 1.3.1 - 2016-08-16

- refactored `transpose` macro. It will throw an exception when invalid input is given and it'll return a collection of collections.

## 1.3.0 - 2016-08-12

- added `transpose` macro

## 1.2.0 - 2016-08-11

- added `assoc` and `toAssoc` macros

## 1.1.0 - 2016-08-10

- the collection will be passed to the callbacks of `ifAny` and `ifEmpty`

## 1.0.0 - 2016-08-09

- initial release
