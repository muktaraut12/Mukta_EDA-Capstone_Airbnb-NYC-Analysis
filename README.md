# Mukta_EDA-Capstone_Airbnb-NYC-2019 dataset
#### <b> Perform Exploaratory Data Analysis on Airbnb New York Data </b>
#### <b> Project Status - Completed </b>

## Project Summary
Airbnb is a vacation rental company who is unique in this market segment.
Airbnb, Inc., based in San Francisco, California, operates an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.
With a simple exploratory analysis of the dataset, we were able to derive many meaningful insights from the huge volume of data that will help us make future business decisions.

## Problem Statement
Since 2008, guests and hosts have used Airbnb to explore innovative travel and stay options and has personalized the way of experiencing the world.
Today, Airbnb is a unique service that is used and recognized by the whole world.
Data analysis on millions of listings provided through Airbnb is a crucial factor for the company to monitor current business status as well as predict future trends and challenges.

## About the data
### Context
This dataset describes the listing activity and metrics in New York and Subburbs, from year 2019.
In the dataset, we have <b><u>14 columns and 48895 rows</u></b>
<b>The column names are as follows - </b>
<li>id                                    
<li>name                                 
<li>host_id                               
<li>host_name                            
<li>neighbourhood_group                   
<li>neighbourhood                         
<li>latitude                              
<li>longitude                             
<li>room_type                             
<li>price                                 
<li>minimum_nights                        
<li>number_of_reviews                     
<li>last_review                       
<li>reviews_per_month                 
<li>calculated_host_listings_count        
<li>availability_365

There are null values in columns as follows - 
<table>
<tr>
<th><b>Column name</b></th>	
<th><b>Null values</b></th>
</tr>
<tr>
<td>name</td>
<td>16</td>
</tr>
<tr>
<td>host_name</td>
<td>21</td>
</tr>
<tr>
<td>last_review</td>
<td>10052</td>
</tr>
<tr>
<td>reviews_per_month</td>
<td>10052</td>
</tr></table>

### Approach Taken
In the data exploration and analysis, answers to the below given questions were discovered from the data - 
<ol>
<li> What can we learn about different hosts and areas?
<li> What is percentage of listings in each neighbourhood group?
<li> Which is the host with highest number of listings?
<li> Find out top 10 neighbourhoods.
<li> What is the average price, maximum price and minimum price of an airbnb listing by property type?
<li> What can we learn from predictions? (ex: locations, prices, reviews, etc).
<li> Which hosts are the busiest and why?
<li> Find out correlation between different columns.
</ol>

### Technical Details
<li>We have used <b><u>Python for EDA.</u></b>
<li>Modules used in the EDA are - 
<ol>
<li>numpy
<li>pandas
<li>matplotlib
<li>seaborn
</ol>

### Conclusions and Inferences
<li>The listings spread across five NYC boroughs, with <u>Manhattan (42.8%) having the largest proportion<u>, followed by Brooklyn (42.3%) and Staten Island (0.8%) having the least. 
<li>The <u>percentage distribution</u> of three unique room types was as follows: 
<ol>
<li>Entire home/apt — 52.3% 
<li>Private room — 45.5%
<li>Shared room — 2.2%.</ol>
<li>The top 10 neighbourhoods out of 221 neighbourhoods were substituted for deep down analysis, where <u>Williamsburg and Bedford-Stuyvesant</u> were found to be more <u>popular neighbourhoods</u> in Brooklyn. 
<li>‘Shared rooms’ barely made it into the top 10 neighbourhoods.
<li>A statistical analysis shows that <u>Manhattan</u> has the <u>most expensive price range </u>with an average of $ 150 followed by Brooklyn with an average of $ 90. 
<li><u>Bronx</u> provides the <u>cheapest accommodation</u> among all. 
Taking a closer look at price distribution, we see that most number of listings are concentrated below $ 200.
<li>The majority of listings have listed their minimum night record below 10. One unusual thing to note here is the peak in the listing frequency for the minimum night of 30. It is possible that some owners have listed their properties on a monthly rental basis, which may explain this.
<li>Manhattan had the most listings, but that traffic in Manhattan is somewhat lower compared to Brooklyn, which has the highest number of reviews on average. This may be due to differences in the price distribution between Manhattan and Brooklyn.
<li>It is evident that hosts are using simple and location-oriented keywords to differentiate their listings. Several mentions of “private rooms” indicate the popularity of this room type in the city.

