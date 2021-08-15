![Cover](https://drive.google.com/uc?id=1BQ5OuFUBinF9MJMqMtxyHBQpObld5LEJ)

# Tokyo2020
Creating and analysing a Dataset of the medals results in TOKYO Olympics Games 2020.

### Process:
* Get the data from the [Olympics oficial site](https://olympics.com/) using webscraping;
* Create a mini dataset from each country
* Concatenate all mini datasets into a big one
* Start making some analysis
* Use the streamlit to make the web application 

### Chalenges:
* The data it's not so organized, they used icons to represent the medals
* Every country has a different link to acess

### RoadMap:
- [ ] Acess the Medal Board in Olympics site
- [ ] Go to the detal medal board for each of the 90 or so countries
- [ ] For each country, download the board and all of the medal icons links
- [ ] Replace all the icon links in the DataFrame by: Gold | Silver | Bronze
- [ ] For each table craate a column with the name of the respective country
- [ ] Concatenate all tables
- [ ] Replace all the abbreviation for the full name of the sport
- [ ] Ude Regex to extract if it's a Fem or Masc Medal
