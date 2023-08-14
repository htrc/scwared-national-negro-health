# Introduction
The `workset` directory contains multiple data files with metadata about the workset and its volumes. Details about each file, its format, and structure are included below
explain:

## `national-negro-health-news.csv`
## `national-negro-health-week.csv`

These are simple CSV files listing the volume ID and some additional metadata for each volume in the worksets.

The columns in the CSV file are:

- id (volume identifier)
- title 
- year (year of publication)
- language (volume language represented as ISO-369-3 language code) 
- authors

Example:

| id | title | year | language | authors |
|:---|:---   |:---  |:---      |:---     |
| uva.x002706721 | National Negro health news. | 1950 | eng | United States Public Health Service |
| uva.x002706970 | National Negro health news. | 1942 | eng | United States Public Health Service |
| uva.x002707450 | National Negro health news. | 1946 | eng | United States Public Health Service |


## `national-negro-health-news.json`
## `national-negro-health-week.json`

These are JSON files with some basic metadata about the worksets themselves, including the creators of and contributors to the worksets. Also included is a list of workset IDs as persistent links to the item in the [HathiTrust Digital Library](https://hathitrust.org).

