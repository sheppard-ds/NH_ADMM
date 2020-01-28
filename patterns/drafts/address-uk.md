# address-uk

This pattern was last updated 28/01/2020, this is version 0.2

Pattern Created: 24/01/2020.  This pattern is experimental.

This pattern covers the standard UK address pattern.  For delivery of mail the minimum requirements would be the addressee, town or city and postcode.  A more detailed field for a Unique Property Reference Number may be added in future, see references for further information

Address is mostly used in the FSA for premises information

### Format

The address consists of five lines as follows.  It is recommended that an address matching service is used, where a postcode is used to search for the correct address.  Technical Design Authority will be able to advise on API to use.  

| Line No | Description  | Required |
|---------|--------------|----------|
| Line 1  | Building and Street | Required |
| Line 2  |              | Optional |
| Line 3  | Town or City | Required |
| Line 4  | County       | Optional |
| Line 5  | Postcode     | Required |

#### Notes
-   **Lines 1 and 2** - Street names should not be abbreviated eg Road, Lane Street, Avenue should not be abbreviated to Rd, Ln, St or Ave.  (use of address matching service would cater for this).

-   **Line 2** is used if there is additional street or locale information eg

    Flat 3\
    15 Sycamore Avenue

    or

    Heron House\
    345 London Road

-   **Line 3** is used for the town or city (or locale, see example below), regardess of whether Line 2 has been populated.
In the example below, Lines 1 and 2 have been used for the house name and street, followed by a locale on line 3, with the Town or City on line 4

    Red Bank Farm\
    The Shore\
    Bolton Le Sands\
    CARNFORTH\
    LA5 8JR

-   **Line 4** - is used for the County, however, it is not actually required for mail delivery but is commonly included as part of the address.  Gov.uk shows line 4 as County in their address pattern (see reference below). It is possible for County to be missing from an address as in the above example.

-   **Minumum requirements** are that lines 1, 3 and 5 are populated.

### References
-   [Royal Mail - How to address mail](https://www.postoffice.co.uk/mail/how-to-address-mail)
-   [gov.uk - address pattern](https://design-system.service.gov.uk/patterns/addresses/)
-   Premises Entity Model - to be added

### Further reading
-   [UPRN numbers](https://www.ordnancesurvey.co.uk/business-government/tools-support/uprn)
-   [AddressBase](https://www.ordnancesurvey.co.uk/business-government/products/addressbase)
-   [Understanding UK address referencing](http://www.restore.ac.uk/geo-refer/91221ctuks00y00000000.php)
