This module allows you to find a country's name from its country code, and a country's code from its name.

Installation
```
npm install countrycode
```

Usage
```JavaScript
var countryCode = require("countrycode");

var myCountry = "Albania";

var myCountrysCode = countryCode.getCode(myCountry);
console.log(myCountrysCode); // Prints 213

var verifyCountryName = countryCode.getCountry(myCountriesCode);
console.log(verifyCountryName);	// Prints "Albania"
```

Note: Country names are NOT case sensitive
