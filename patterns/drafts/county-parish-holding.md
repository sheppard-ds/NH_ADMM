# County Parish Holding Number

## Description
The County Parish Holding number identifies one or more parcels of land, which when grouped together form a holding.

In the FSA it exists solely for the purposes of linking with data from external sources, including (but not limited to);
-   Animal and Plant Health Agency
-   Red Tractor Farm Assurance
-   Environment Agency
-   Public Health England

### Data type and pattern
When working with the CPHN in the FSA our preferred pattern to split the CPHN in to three separate fields;
1. A numeric field of two digits in the format `00`, this is the number associated with a county
2. A numeric field of three digits in the format `000`, this is the number associated with a parish
3. A numeric field of four digits in the format `0000`, this is the number associated with a holding

Often the CPHN will be provided as an alphanumeric string, in the format `01/234/5678`. This will need to be parsed to be stored correctly.

#### Notes
Sometimes a CPHN can include a herd number, which is an additional two digits after the holding number, we do not use these.

#### Additional Information
[https://www.gov.uk/guidance/register-land-you-use-to-keep-livestock](https://www.gov.uk/guidance/register-land-you-use-to-keep-livestock)
