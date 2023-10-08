# README

# Gender Equality Tracker: Towards a More Equal World 

## Data Source
- UNdata: [United Nations Development Programme](https://hdr.undp.org/data-center)
- [The World Bank](https://wbl.worldbank.org/)
- Country: ['Brazil','Canada','China','Germany','India','United States']

## Dashboard Design
The primary objective of this dashboard is to provide a comprehensive and user-friendly interface for tracking and analyzing gender equality indexes across five distinct countries: Canada, China, India, Japan, and the United States. This dashboard offers a centralized platform to explore key metrics and trends related to gender equity. It aims to empower stakeholders, policymakers, and advocates with the data and insights they need to make informed decisions, drive positive change, and foster a more inclusive society. Through an intuitive and interactive experience, this dashboard enables users to navigate, understand, and engage with the nuances of gender equality.

### Who are the users?
No previous knowledge about gender equality related indicators are required, as the dashboard is easily understood.
- Government policymakers and agencies
- Academic researchers and institutions
- Advocates and activists
- Media and journalists
- General public

### Indicators
- Gender Development Index (GDI)
- Gender Inequality Index (GII)
- Estimated gross national income per capita (2017 PPP $)
- Labour force participation rate (% ages 15 and older)
- Population with at least some secondary education (% ages 25 and older)
- Share of seats held by women in national parliaments (%)
- Maternal mortality ratio (Per 100,000 live birth)


### Data Encoding System

| Data   | Data Type   | Data Encoder |
| ----------- | ----------- | ----------- |
| Country | Norminal | HUE of Colors |
| Gender | Norminal | HUE of Colors |
| GDI | Ratio | Postion on Y-Axis | 
| GII | Ratio | Postion on X-Axis | 
| Estimated GNI Per Capita | Ratio | Width of Bars |
| Labor Force Participation Rate | Ratio | Postion on Y-Axis |

### Final Demo
![Demo](./Demo.png)

## Usage
```bash
npm install browser-sync
npm run server
```