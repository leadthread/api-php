# LeadThread API v2
[![Latest Version](https://img.shields.io/github/release/leadthread/api-php.svg?style=flat-square)](https://github.com/leadthread/api-php/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://travis-ci.org/leadthread/api-php.svg?branch=master)](https://travis-ci.org/leadthread/api-php)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/leadthread/api-php/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/leadthread/api-php/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/leadthread/api-php/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/leadthread/api-php/?branch=master)
[![Total Downloads](https://img.shields.io/packagist/dt/leadthread/api-php.svg?style=flat-square)](https://packagist.org/packages/leadthread/api-php)

## Resources
[API v2 Documentation](https://leadthread.docs.apiary.io/)

## Installation

Install via [composer](https://getcomposer.org/) - In the terminal:
```bash
composer require leadthread/api-php
```

## Usage
```php
use LeadThread\Api\LeadThread;

$client = new LeadThread($API_TOKEN, "your_company_domain");

$positions = $client->positions->all();
```
