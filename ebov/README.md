This is a list of known human outbreaks of Ebola virus (EBOV - formerly known as Zaire species or ZEBOV) and a list of EBOV genomes with associated metadata (the sequences are not present but Genbank accession numbers are given). They are in comma-separated values (CSV) format with Unix line endings.

Where possible the dates and locations represent that of the earliest cases (i.e., closest to the origin of the outbreak).

## EBOV_Outbreaks.csv
The columns are as follows:

`outbreak` - a label for the outbreak with a primary location and a year.

`cases` - the number of recorded cases.

`deaths` - the number of recorded cases.

`adm0` - the country in ISO 3166 3 letter codes.

`adm1` - the top level within-country admin area (diacritics removed).

`adm1_name` - the name of the adm1 areas (anglicized).

`adm2` - the second level within-country admin area (diacritics removed).

`adm2_name` - the name of the adm2 areas (anglicized).

`adm3` - the third level within-country admin area where available (free text).

`health_zone` - a health zone or medical catchment area.

`other` - other geographical location name (possibly not on large scale maps).

`town_village` - the closest town or village for the earliest cases.

`location` - a representitive location for coordinates.

`latitude` - the latitude of the location (decimal degrees).

`longitude` - the longitude of the location (decimal degrees).

`dates` - the known or estimated time span of the epidemic (free text, month and year range).

`earliest_case` - the calendar date of the earliest known case (date of onset where possible).

`latest_case` - the date of the last known case (date of onset where possible).

`reference` - the primary reference for these data.

`reference_url` - the url for the primary reference.

`reference2` - a secondary reference.

`reference2_url` - the url for the secondary reference.

`notes` - notes about the derivation of the data where not explicit.

## EBOV_Outbreak_Genomes.csv

`label` - label used for genome

`country` - the country of origin (ISO 3166 3 letter codes)

`accession` - the Genbank accession number

`name` - the name of the sample or isolate

`date` - date of sampling (may be missing day or month if unknown).

`range` - the range of possible dates based on outbreak dates (free text)

`outbreak` - the outbreak name referring to `EBOV_Outbreaks.csv`

`exclude?` - whether this genome is excluded from the strict one-per-outbreak list.

`notes` - notes about the derivation of the data where not explicit.
