---
title: "Asocdate"
date: 2021-07-08T13:14:00-07:00
draft: true
---

# Associated Date

| Condition  | Value |
|-------------|---------------------------|
| Definition  | Additional date(s) associated with the resource. |
| Required?   | No                        |
| Repeatable? | Yes                        |

## Guidelines

- When used in legacy EAIC collections, this property refers to the date of an event documented in the photographic image, and later reproduced in an album or postcard.

- Record the associated date in [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html)/[EDTF](https://www.loc.gov/standards/datetime/) format. \
&rarr; The LDR application will display EDTF date in a human-readable format in the public-facing user interface.

- Avoid using abbreviations or Latin terms for dates.

| Encoding      | Date field value (encoded EDTF) | Display Date |
| ----------- | ----------- | ----------- |
| yyyy     | 1861       | 1861       |
| yyyy-mm   | 2011-07        | July 2011        |
| yyyy-mm-dd     | 1451-04-22       | April 22, 1451       |
| yyyy-mm-dd/yyyy-mm-dd   | 1992-06-10/1999-07-31        | June 10, 1992 to July 31, 1999        |
| yyyy~/yyyy~     | 1910~/1915~       | Circa 1910 to circa 1915       |
| yyyy~   | 33        | Circa 33        |
