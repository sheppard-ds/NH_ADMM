# Telephone Number

This pattern was last updated 17/01/2020, this is version 0.x

Pattern Created: 17/01/2020

A telephone number is a sequence of digits used to connect to a fixed line or wireless device.  

Formats can vary by country or, in the case of the UK, within the country.

In the UK a number is generally made up of a geographic area code (prefixed with 01 or 02), discounting the leading zero these vary in length from 2 to 5 digits.  

The next part of the phone number (subscriber number can also vary in length) but the total number of digits will not exceed 10 (excluding the leading zero of the geographical code).

It is common for geographical codes to be frequently misquoted eg the geographical code for London is 020 but often quoted as 0207 or 0208 with the 1st digit of the 8 digit subscriber number added followed by the remaining 7 digits.

Mobile numbers have an 'area' code 07xxx followed by a 6 digit subscriber number.

the leading zero can be replaced by the appropriate country code, +44 for the UK, when dialling internationally.  It may be necessary to store international numbers for some areas of the FSA business.

The above is not intended as an indepth account of telephone number formatting.  Please see references linked below.

Although it would be possible to validate entry of phone numbers or to split the storage of phone numbers into geographical and subscriber numbers the effort to do this may outweigh the current benefits for the FSA at present.  Therefore the following formatting is proposed

### Format

Telephone numbers should be stored as a string entries, in order to preserve leading zeroes and potential special characters used for international dialling codes and formatting (eg +, (), -).

Field length of 20 would allow for the following examples plus other international variants plus any spaces (Guidelines within E.146 would restrict to 15 characters with all spaces and special characters removed (excluding '+' symbol for country code))

01xxx xxxxxx
01xx xxx xxxx
020 xxxx xxxx
01xx xx xxxxx
+44 xxxx xxxx xxxx

DN - at the moment the above format is intentionally loose to avoid transformation/validation of telephone numbers prior to storage and vice versa for presentation.  Business discussions may introduce a more prescriptive format.

### References

-   [International standards for telephone number formats](https://en.wikipedia.org/wiki/E.164)
-   [International guidelines for presentation of telephone numbers](https://en.wikipedia.org/wiki/E.123)
-   [UK telephone numbers](https://en.wikipedia.org/wiki/Telephone_numbers_in_the_United_Kingdom)
-   [Internation Trunk Prefix](https://en.wikipedia.org/wiki/Trunk_prefix)

#### Articles on best practices for handling phone Numbers

-   [MojoLingo - Handling Phone Numbers: Best Practices for Developers](https://mojolingo.com/blog/2015/best-practices-handling-phone-numbers/)

-   [What data type would you use to store a phone number](https://teamtreehouse.com/community/what-data-type-would-you-use-to-store-a-phone-number)
