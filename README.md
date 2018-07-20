# Homelessness in America
## Background
Homelessness is an issue that continues to burden our communities across the globe. While typical discussion around the causes of homelessness can focus on the personal/individual level, it is known that many structural/macro level factors contribute to homelessness.

This goal of this project is to examine macro level factors that a related to homelessness using US data.

## How to Collaborate
If you are interested in collaborating on this project, please read the COLLABORATE document. 

## Resources
The following original sources were accessed to create datasets for analysis. These are located in the resources folder.

### [PIT and HIC Data Since 2007](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/)
At present the following databases are included:
- 2007 - 2017 PIT Counts by State
- 2007 - 2017 HIC Data by State

PIT: Point in Time
HIC: Housing Inventory Count

Each of these resources is reported by [Continuums of Care](https://www.hudexchange.info/programs/coc/)'s to the US Housing and Urban Development (HUD) department.

## Datasets
To assist in analysis, the original data sources have been split into different cleaned datasets. These are located in the datasets folder.

Information on data cleaning and validation can be found in the homelessness-working notebook.

### Homelessness
Due to the structure of the original dataset, the data has been split into a number of smaller datasets.
- **homelessness-final:** Full dataset of original categorizations.
- **homelessness-type:** Separates data according to homelessness type (chronic and non-chronic)
- **homelessness-shelter:** Separates data according to sheltered and unsheltered
- **homelessness-family:** Separates data according to family groupings - individuals and people in families
- **homelessness-age:** Separates data according to youth categories
- **homelessness-veteran:** Separates data according to veteran status or not

#### Using these datasets
It is important to understand that the categorizations found within the data are not mutually exclusive, and are therefore not additive. It is important that the data structure is understood before analysis is conducted. Information how the data is constructed can be found in the Data Configuration doc resources folder.
