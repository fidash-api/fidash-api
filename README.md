Shield: [![CC BY-ND 4.0][cc-by-nd-shield]][cc-by-nd]

This work is licensed under a
[Creative Commons Attribution-NoDerivs 4.0 International License][cc-by-nd].

[![CC BY-ND 4.0][cc-by-nd-image]][cc-by-nd]

[cc-by-nd]: https://creativecommons.org/licenses/by-nd/4.0/
[cc-by-nd-image]: https://licensebuttons.net/l/by-nd/4.0/88x31.png
[cc-by-nd-shield]: https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg

# fidash API
Financial Data Sharing API


# Code sets:
The list of code sets used in the API:
* Currency codes: [ISO 4217](https://www.iso.org/iso-4217-currency-codes.html), [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217)
* Market Identifier Code: [ISO 10383](https://www.iso20022.org/market-identifier-codes), [Wikipedia](https://en.wikipedia.org/wiki/Market_Identifier_Code)
* Country Codes: [ISO 3166](https://www.iso.org/iso-3166-country-codes.html), [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166)

## String Formats
An optional `format` modifier serves as a hint at the contents and format of the string. This API uses the OpenAPI built-in string formats:

* `date` – full-date notation as defined by [RFC 3339, section 5.6](https://datatracker.ietf.org/doc/html/rfc3339#section-5.6), for example, 2017-07-21
* `date-time` – the date-time notation as defined by [RFC 3339, section 5.6](https://datatracker.ietf.org/doc/html/rfc3339#section-5.6), for example, 2017-07-21T17:32:28Z
