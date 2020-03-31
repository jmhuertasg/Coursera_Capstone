### Tareas calificadas por los compañeros: Segmenting and Clustering Neighborhoods in Toronto

#######################################################################################################
Notebook :### Toronto_Cluster.ipynb                                                                 ###
#######################################################################################################

For this assignment, you will be required to explore and cluster the neighborhoods in Toronto.

#1. Start by creating a new Notebook for this assignment.

#2. Use the Notebook to build the code to scrape the following Wikipedia page, https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M, in order to obtain the data that is in the table of postal codes and to transform the data into a pandas dataframe like the one shown below:

#3. To create the above dataframe:
		The dataframe will consist of three columns: PostalCode, Borough, and Neighborhood
		Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned.
		More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, you will notice that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11 in the above table.
		If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the borough.
		Clean your Notebook and add Markdown cells to explain your work and any assumptions you are making.
		In the last cell of your notebook, use the .shape method to print the number of rows of your dataframe.
		
#4. Submit a link to your Notebook on your Github repository. (10 marks)

#######################################################################################################
Notebook: ### Toronto_Cluster part 2.ipynb                                                          ###
#######################################################################################################

#5. Now that you have built a dataframe of the postal code of each neighborhood:
		along with the borough name and neighborhood name, in order to utilize the Foursquare location data, we need to 
		get the latitude and the longitude coordinates of each neighborhood. Given that this package can be very unreliable, 
		in case you are not able to get the geographical coordinates of the neighborhoods using the Geocoder package, here 
		is a link to a csv file that has the geographical coordinates of each postal code: http://cocl.us/Geospatial_data



