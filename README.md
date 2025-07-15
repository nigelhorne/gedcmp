# gedcmp

Compare two gedcoms for missing and differing data,
producing a CSV which should be readable by any spreadsheet.

I use this to compare my Gedcoms on FindMyPast and Ancestry.
It could also be of use to compare Gedcoms with those of a family member.

## See Also

* [gedcom](https://github.com/nigelhorne/gedcom) - a general purpose utility for Gedcom files
* [ged2site](https://github.com/nigelhorne/ged2site) - create a website from a Gedcom file

# find_common

This script compares individuals across GEDCOM files and reports those who share **both the same birth and death dates**.

## Features

- Uses the `Gedcom` CPAN module for parsing
- Normalizes birth and death dates to avoid mismatches due to formatting
- Skips invalid or incomplete individuals gracefully
- Compares data across multiple GEDCOM files
- Identifies potential duplicate individuals by exact birth/death date matches

## SUPPORT

This module is provided as-is without any warranty.

## LICENSE AND COPYRIGHT

Copyright 2015-2025 Nigel Horne.

This program is released under the following licence:
GPL for personal use on a single computer.
All other users (including Commercial, Charity, Educational, Government)
must apply in writing for a licence for use from Nigel Horne at
`<njh at nigelhorne.com>`.
