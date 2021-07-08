---
title: "Date"
date: 2021-07-08T15:27:35-07:00
draft: true
---

# Date

| Condition  | Value |
|-------------|---------------------------|
| Definition  | Date associated with the creation of the original resource. |
| Required?   | No                        |
| Repeatable? | Yes                        |

# Guidelines

- Record the date in [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html)/[EDTF](https://www.loc.gov/standards/datetime/) format. \
&rarr; The LDR application will display EDTF date in a human-readable format in the
 public-facing user interface.

 -  For published materials, use the **Issued** property instead.

 -  Avoid using abbreviations or Latin terms for dates.

 | Encoding      | Date field value (encoded EDTF) | Display Date |
 | ----------- | ----------- | ----------- |
 | yyyy     | 1861       | 1861       |
 | yyyy-mm   | 2011-07        | July 2011        |
 | yyyy-mm-dd     | 1451-04-22       | April 22, 1451       |
 | yyyy-mm-dd/yyyy-mm-dd   | 1992-06-10/1999-07-31        | June 10, 1992 to July 31, 1999        |
 | yyyy~/yyyy~     | 1910~/1915~       | Circa 1910 to circa 1915       |
 | yyyy~   | 33        | Circa 33        |
