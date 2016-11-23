# sg-school-leaver-destinations
Number, and percent, of school leavers in Edinburgh by destination from initial survey.

Information on the destination of leavers from publicly funded schools is provided to the Scottish Government by Skills Development Scotland. The data relate to the latest known destination of leavers in the September (2011) after the school year they left (2010/11).

For more information please see the publication Destinations of Leavers from Scottish Schools which is available at the following link http://www.scotland.gov.uk/Topics/Statistics/Browse/School-Education/Publications

Higher Education : includes leavers following HND (Higher National Diploma) or HNC (Higher National Certificate) courses, degree courses, courses for the education and training of teachers and higher level courses for professional qualifications. It also includes programmes at a level higher than the standard of the National Qualifications, i.e above SCQF level 7. Leavers with a deferred, unconditional place in higher education have also been included in this category.

Statistics provided by Scottish Government:  http://statistics.gov.scot/data/school-leaver-destinations

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/sg-school-leaver-destinations.git
```

Install npm dependencies

```
cd sg-school-leaver-destinations
npm install
```

Run the API (from the sg-school-leaver-destinations directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
