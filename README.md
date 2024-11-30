[![Actions Status](https://github.com/raku-community-modules/SOAP-Client/actions/workflows/linux.yml/badge.svg)](https://github.com/raku-community-modules/SOAP-Client/actions) [![Actions Status](https://github.com/raku-community-modules/SOAP-Client/actions/workflows/macos.yml/badge.svg)](https://github.com/raku-community-modules/SOAP-Client/actions)

NAME
====

SOAP::Client - Quick and dirty SOAP client

SYNOPSIS
========

```raku
use SOAP::Client;

my $temp = SOAP::Client.new('https://www.w3schools.com/xml/tempconvert.asmx?WSDL');
say $temp.call('CelsiusToFahrenheit', Celsius => 100);
```

DESCRIPTION
===========

Warning: This library currently only supports the simplest of SOAP calls.

AUTHOR
======

Andrew Egeler

COPYRIGHT AND LICENSE
=====================

Copyright 2015- 2017 Andrew Egeler

Copyright 2018 - 2024 Raku Community

Licensed under the MIT license.

