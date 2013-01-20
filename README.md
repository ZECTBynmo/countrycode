This module allows you to find a country's name from its country code, and a country's code from its name.

Installation
```
npm install countrycode
```

Usage
```JavaScript
var countryCode = require("countrycode");

var myCountry = "Albania";

var myCountrySearch = "";

var myCodeSearch = 93;

var myCountrysCode = countryCode.getCode(myCountry);
console.log(myCountrysCode); // Prints 213

var verifyCountryName = countryCode.getCountry(myCountriesCode);
console.log(verifyCountryName);	// Prints "Albania"

var findCountriesLike = countryCode.searchCountry(myCountrySearch);
console.log(findCountriesLike); // Prints [ { country: 'Albania', code: 213 }, { country: 'Svalbard', code: 0 } ]

var findCodesLike = countryCode.searchCode(myCodeSearch);
console.log(findCodesLike); // Prints [ { country: 'Afghanistan', code: 93 }, { country: 'Ecuador', code: 593 }, { country: 'Turkmenistan', code: 993 } ]
```

Note: Country names are NOT case sensitive
