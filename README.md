# Crime Data Explorer

The FBI collects and publishes [Uniform Crime Reporting (UCR)](https://ucr.fbi.gov/) data on an annual basis. Over 18,000 law enforcement agencies across the country voluntarily participate in the program by submitting data through a state UCR program or directly to the FBI. This open data project is part of our ongoing efforts to improve the accuracy and timeliness of the nation’s crime statistics.

The Crime Data Explorer is a collaboration between [18F](https://18f.gsa.gov/) and the FBI Criminal Justice Information Services (CJIS) Division. It aims to make national, state, and local crime data more accessible and understandable to the public.
 
## Available datasets
The FBI collects several [types of data](https://ucr.fbi.gov/ucr-program-data-collections). These datasets are available for download via the Crime Data Explorer and the underlying API:

- Summary Reporting System (SRS): monthly offense, arrest, and clearance data for crimes known to law enforcement from 1960–2014.
- National Incident-Based Reporting System (NIBRS): reports from individual crime incidents with offense, location, victim and offender demographics, property damage, and arrestee details from 1991–2014.
- Estimated data:  Summary (SRS) data that has been estimated to create trends for crime occurrences on the state and national level. The FBI has traditionally included estimates in their [annual publications](https://ucr.fbi.gov/ucr-publications). 
- Police Employee Data: totals for full-time sworn and civilian law enforcement employees by state from 1960–2014.
- Uniform Crime Reporting Participation Data: SRS and NIBRS participation rates for individual law enforcement agencies by state and year from 1960–2014.
These datasets are available for download; we’re working on adding them to the API:
- Law Enforcement Officers Killed and Assaulted (LEOKA): totals for officers who were killed or assaulted in the line of duty from 1974–2014.
- Hate Crime: totals by state, year, and bias motivation for hate crimes across the country from 1991–2014.
- Cargo Theft: totals by state, year, property type, and property value for cargo thefts from 2013–2014. This is a relatively new dataset for the FBI.
- Human Trafficking: totals by state and offense for commercial sex acts and involuntary servitude from 2013–2014. This is also a new dataset for the FBI.
 
## About the data

### The FBI’s role in collecting this data

To ensure crime data is uniformly reported across the nation, the FBI provides contributing law enforcement agencies with documentation that explains how to classify and score offenses. Though crime definitions vary from state to state, the FBI asks agencies to report offenses according to Uniform Crime Reporting guidelines.

Although the FBI makes every effort through its editing procedures, training practices, and correspondence to ensure the validity of the data it receives, the accuracy of the data depends on the adherence of each contributor to the established standards of reporting. It is the responsibility of each state UCR program or individual contributing law enforcement agency to submit accurate data or correct existing errors.

### Avoid rankings and comparisons

Since crime is a sociological phenomenon influenced by a variety of factors, the FBI discourages ranking locations or making comparisons between states, counties, or agencies as a way of measuring law enforcement effectiveness. Some of this data may not be comparable to previous years because of differing levels of participation over time.

### Unestimated data

While the FBI has traditionally included estimates in their [annual publications](https://ucr.fbi.gov/ucr-publications), the Crime Data Explorer provides data without estimates or modifications through downloads and in agency-level views. As a result, the data available for download may vary from the FBI’s annual reports.

### Working with NIBRS data

Each incident-based (NIBRS) ZIP file includes a group of CSVs that you can join together with the internal incident ID or the law enforcement agency’s Originating Agency Identifier (ORI).

The incident IDs are generated to make it easier to work with the data. These numbers are not specific to local law enforcement agencies and bear no relation to other identifiers that could be linked to a real case number.
 
## Related resources

We encourage you to explore, make suggestions, and contribute to our code. This repository, [Crime Data Explorer](https://github.com/18F/crime-data-explorer), is the best place to submit general feedback about the site.

- [Crime data API](https://github.com/18F/crime-data-api): code for the RESTful API behind the Crime Data Explorer
- [Crime data style](https://github.com/18F/crime-data-style): visual style guide and user interface component library
- [Uniform Crime Reporting (UCR) documentation](https://ucr.fbi.gov/user-manuals): user manuals developed by the FBI
- [API documentation](https://crime-data-api.fr.cloud.gov/swagger-ui/): technical documentation for the crime data API
 
## Get involved
[![Follow along with the progress on our Waffle.io board](https://badge.waffle.io/18F/crime-data-explorer.svg?label=ready&title=Ready)](http://waffle.io/18F/crime-data-explorer)

We’re thrilled you want to get involved! 
- Read our [contributing guidelines](https://github.com/18F/crime-data-explorer/blob/master/CONTRIBUTING.md). Then, [file an issue](https://github.com/18F/crime-data-explorer/issues/new) or submit a pull request.
- If you’re a developer, follow the installation instructions in the README.md page of each repository to run the apps on your computer.
- If you have questions about the data, including potential errors or discrepancies, please email the FBI Criminal Justice Information Services Division at cjis_comm@leo.gov.
Copyright and licensing
This project is in the public domain within the United States, and we waive worldwide copyright and related rights through [CC0 universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/). Read more on our [license page](https://github.com/18F/crime-data-explorer/blob/master/LICENSE.md).


## Other project repositories
* [18f/crime-data-api](https://github.com/18f/crime-data-api)
* [18f/crime-data-frontend](https://github.com/18f/crime-data-frontend)
* [18f/crime-data-prototypes](https://github.com/18f/crime-data-prototypes)
* [18f/crime-data-style](https://github.com/18f/crime-data-style)
