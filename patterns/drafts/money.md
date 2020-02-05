---
layout: default
title: Money
nav_order: 6
has_children: false
---
# Money

This pattern was last updated 05/02/2020, this is version 0.1

Pattern Created: 05/02/2020.

Stable {: .label .label-green }

## Description
A monetary sequence is used to denote the cost of a product or service. This can be a cost to the FSA or a source of revenue for the FSA. All monies are converted to pound sterling (£) as this is the currency of the Food Standards Agency (FSA) uses.

### Format

For the purposes of this example I have included the GBP Sterling £ sign as a prefix.  This may not always be used as some tables will display the decimilised number in a field and the £ sign will be displayed in the field Header.  

| Description | Number |
| ----------------------------| -----------:|
| One Pence  | £0.01 |
| Ten Pence | £0.10 |
| One Pound   | £1.00 |
| Ten Pound | £10.00 |    
| One Hundred Pound | £100.00 |
| One Thousand Pound | £1,000.00 |
| Ten Thousand Pound | £10,000.00 |
| One Hundred Thousand Pound | £100,000.00 |
| One Million Pound | £1,000,000.00 |

For accounting purposes the FSA occasionally rounds to the nearest 1000 this usually has the following displayed in the column header as Cost (000).  For Example

| Cost | Cost (000) |
|------------: |--------: |
| £123,456.00 | £123 |

Negative or minus figures can be displayed with a prefix of - or it can be displayed within () please see table below for examples.

| Loss | Display as |
|------------------ |-------------: |
| minus £123,456.00 | -£123,456.00 |
| minus £123,456.00 | -123,456.00 |
| minus £123,456.00 | (£123,456.00) |

### Developers
FSA use money for buying and selling goods and services.  In all cases Please see the relevant API documentation available through the reference below.

### References
-   [Currency code ISO 4217](https://en.wikipedia.org/wiki/ISO_4217)

#### Further reading
-   [Pound sterling](https://en.wikipedia.org/wiki/Pound_sterling)
-   [Currency_symbol](https://en.wikipedia.org/wiki/Currency_symbol)
