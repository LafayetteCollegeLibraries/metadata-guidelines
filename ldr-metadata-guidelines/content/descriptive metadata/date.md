---
title: "Date"
date: 2021-07-08T15:27:35-07:00
definition: "Date associated with the creation of the original resource."
repeatable: true
draft: false
---

## Guidelines

- Record the date in <u>[ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html)</u>/<u>[EDTF](https://www.loc.gov/standards/datetime/)</u> format.
  - The LDR application will display EDTF date in a human-readable format in the
 public-facing user interface.

 -  For published materials, use the **Issued** property instead.

 -  Avoid using abbreviations or Latin terms for dates.

## Examples

 | Encoding      | Date field value (encoded EDTF) | Display Date |
 | ----------- | ----------- | ----------- |
 | yyyy     | 1861       | 1861       |
 | yyyy-mm   | 2011-07        | July 2011        |
 | yyyy-mm-dd     | 1451-04-22       | April 22, 1451       |
 | yyyy-mm-dd/yyyy-mm-dd   | 1992-06-10/1999-07-31        | June 10, 1992 to July 31, 1999        |
 | yyyy~/yyyy~     | 1910~/1915~       | Circa 1910 to circa 1915       |
 | yyyy~   | 33        | Circa 33        |
