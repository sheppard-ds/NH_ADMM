# address-uk

This pattern was last updated 24/01/2020, this is version 0.1

Pattern Created: 24/01/2020

This pattern covers the standard uk address pattern.  For delivery of mail the minimum requirements would be the addressee, town or city and postcode.  

### Format

The address consists of five lines as follows

| Line No | Description  | Required |
|---------|--------------|----------|
| Line 1  |              | Required |
| Line 2  |              | Optional |
| Line 3  | Town or City | Required |
| Line 4  | County       | Optional |
| Line 5  | Postcode     | Required/Optional ??? |

#### Notes
**Lines 1 and 2** - Street names should not be abbreviated eg Road, Lane Street, Avenue should not be abbreviated to Rd, Ln, St or Ave.

**Line 2** is used if there is additional street or locale information eg

Flat 3\
15 Sycamore Avenue

Heron House\
345 London Road

Line 3 is used for the town or city (or locale see example below), regardess of whether Line 2 has been populated.
In the example below, Lines 1 and 2 have been used for the house name and street, followed by a locale on line 3, with the Town or City on line 4

Red Bank Farm\
The Shore\
Bolton Le Sands\
CARNFORTH\
LA5 8JR


**Line 4** - is used for the County, however, it is not actually required for mail delivery but is commonly included as part of the address.  Gov.uk feature show line 4 as County in their address pattern (see reference below). It is possible for County to be missing from an address as in the above example

**Line 5** - is for the postcode

### References
-   [Royal Mail - How to address mail](https://www.postoffice.co.uk/mail/how-to-address-mail)
-   [gov.uk - address pattern](https://design-system.service.gov.uk/patterns/addresses/)

### Further reading
-   [UPRN numbers](https://www.ordnancesurvey.co.uk/business-government/tools-support/uprn)
-   [AddressBase](https://www.ordnancesurvey.co.uk/business-government/products/addressbase)

# To discuss
-   captialisation of Town/City, County
-   abbreviation lines to take
-   whether to include a separate field in the address grouping for uprn or leave for now
