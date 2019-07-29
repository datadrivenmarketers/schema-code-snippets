# Schema markup code (JSON-LD) snippets for a variety of Organizations, Products, Local Businesses, and Persons.

Use this repository for help and guidance when creating schema markup for your website. Unlike [Schema.org] (https://schema.org), these examples do not contain all of the available properties when it comes to publishing your markup. For a full overview of what properties you can use, please visit [Schema.org] (https://schema.org). 

Please note that these code snippets are void of actual business information. If you'd like to use these snippets for your own business, edit each line to reflect your business information.

Before
```Shell
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "",
    "addressLocality": "",
    "addressRegion": "",
    "postalCode": "",
    "addressCountry": ""
```
After 
```Shell
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 My Address St",
    "addressLocality": "Phoenix",
    "addressRegion": "AZ",
    "postalCode": "85001",
    "addressCountry": "US"
```

## Schema markup tools
1. [GEO coordinates converter](https://www.gps-coordinates.net/gps-coordinates-converter)
2. [Stuctured data testing tool from Google](https://search.google.com/structured-data/testing-tool/u/0/).
