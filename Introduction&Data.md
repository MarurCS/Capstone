## 1.	Introduction 


 Toronto is the most populous city in Canada with over 6 million people. Being a multicultural and cosmopolitan city, people of varied ethnic backgrounds dwell here. As Toronto is also a business hub, visitors from around the globe arrive here and hang out in restaurants, pubs and shopping malls. With an influx of people, new restaurants pop up on a frequent basis to satiate the visitors’ palates.

A study by Ohio State University revealed that nearly 60% of restaurants close or change ownership within the first year and 80% fail within the first 5 years. With the average restaurant profit margins falling between 3-5%, it’s vital to set the business up for success from the beginning by having a strategic plan for significant foot fall and minimum competition.

Two important points to consider before setting up a restaurant in Toronto are to understand the ethnic backgrounds of its residents and keep the competition at a bare minimum.

**This project focuses on assisting any party interested in opening a restaurant by:**

**a) Identifying the ethnic backgrounds of residents in a given neighbourhood in Toronto and**

**b) Locating a neighbourhood where the competition of similar restaurants is lowest**

**Any potential entrepreneur looking to open a restaurant in the city of Toronto can be benefited by this analysis** as the objective of this project is to cluster the neighbourhoods based on the ethnicity of its residents and also intend to identify the presence of similar restaurants which would minimize competition.

Based on the food preferences of people living in the vicinity of the restaurant the right type of cuisine can be offered to the customers. When there is limited competition more customers can be expected to visit our restaurants and thereby maximizing  business and profits. We use Foursquare API to retrieve and study any existing competitors in the neighbourhood. This is done by filtering the specific list of restaurants from the overall list of venues we obtain from the Foursquare API query.

Hence, it is imperative that anyone interested in opening a new restaurant should study the demographic distribution of the neighbourhood and identify any competition before deciding on the type of restaurant and its location.




 

## 2. Data

Demographic data about Toronto is available on the www.toronto.ca website. 

The link to the csv file is:https://www.toronto.ca/ext/open_data/catalog/data_set_files/2016_neighbourhood_profiles.csv

The above file has comprehensive data about the residents of Toronto city which includes:

a) Population

b) Income

c) Education

d) Ethnic origin

e) Languages spoken

f) Mobility 

Below is how the data looks:


![Snip1.JPG](attachment:Snip1.JPG)

For our analysis we need only the 'Ethnic Origin Population' data available under the column 'Characteristic' and the different neighborhoods available along with their respective populations. The neighborhoods are provided as columns 6 to 144. Each neighborhood contains data split on its residents with respect to different ethnicities.

The remaining of the columns in this data are redundant to our analysis and can be dropped.

Only ethnic origins with high number of residents (such as Chinese, English & other European countries, Indian) are retained to simplify our analysis and the rest are left out as their numbers are not quite significant. 

#### 2.1 Foursquare API
Using Foursquare API, a free application providing geographical data, we can retrieve the different venues available in the various neighborhoods of Toronto city. 

The link to this application is: https://foursquare.com/developers/apps
This website is easy to use and has excellent documentation on creating developer account and how to retreive the location data. Our interest lies in obtaining the list of restaurants and other eateries in various neighborhoods using Foursquare API. The retreived data can be used to filter out the type of restaurant we are looking for and then be compared against the existing ethnic population and competitors to make a calculated decision on setting up any new restaurant.


```python

```
