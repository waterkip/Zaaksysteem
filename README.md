# Zaaksysteem Client

[![Build Status](https://travis-ci.org/SimplyAdmire/Zaaksysteem.svg)](https://travis-ci.org/SimplyAdmire/Zaaksysteem)
[![Code Climate](https://codeclimate.com/github/SimplyAdmire/Zaaksysteem/badges/gpa.svg)](https://codeclimate.com/github/SimplyAdmire/Zaaksysteem)
[![Test Coverage](https://codeclimate.com/github/SimplyAdmire/Zaaksysteem/badges/coverage.svg)](https://codeclimate.com/github/SimplyAdmire/Zaaksysteem/coverage)

[![Latest Stable Version](https://poser.pugx.org/simplyadmire/zaaksysteem/v/stable)](https://packagist.org/packages/simplyadmire/zaaksysteem)
[![Total Downloads](https://poser.pugx.org/simplyadmire/zaaksysteem/downloads)](https://packagist.org/packages/simplyadmire/zaaksysteem)
[![Latest Unstable Version](https://poser.pugx.org/simplyadmire/zaaksysteem/v/unstable)](https://packagist.org/packages/simplyadmire/zaaksysteem)
[![License](https://poser.pugx.org/simplyadmire/zaaksysteem/license)](https://packagist.org/packages/simplyadmire/zaaksysteem)

This package is a PHP based client for Zaaksysteem (http://zaaksysteem.nl/). The client is standalone, meaning it does
not depend on any PHP framework. Implementations for frameworks like Flow are planned and will be released as separate
packages.

# Supported API's

## Object

Manual: https://zaaksysteem.url/man/Zaaksysteem::Manual::API::Object
For this API you have to configure an "Extern Koppelprofiel" in your Zaaksysteem instance.

Implemented methods:

- [ ] get
- [ ] list

## V1

Manual: https://zaaksysteem.url/man/Zaaksysteem::Manual::API::V1
For this API you have to configure an "Zaaksysteem API" in your Zaaksysteem instance.

Below you can find the implemented methods per API:

### Case

- [ ] get
- [ ] list
- [ ] create
- [ ] update
- [ ] transition
- [ ] prepare file

### Case\Document

- [ ] get
- [ ] list
- [ ] download file

### Case\CaseType
 
- [ ] get
- [ ] list

### Case\ControlPanel

- [ ] get
- [ ] list
- [ ] create
- [ ] update

### Case\Host

- [ ] get
- [ ] list
- [ ] create
- [ ] update

### Case\Instance

- [ ] get
- [ ] list
- [ ] create
- [ ] update

### Case\Subject

- [ ] create
