### Tareas calificadas por los compañeros: Segmenting and Clustering Neighborhoods in Toronto

#######################################################################################################
Notebook :### Toronto_Cluster Practice 1.ipynb                                                      ###
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
Notebook: ### Toronto_Cluster Practice 2.ipynb                                                      ###
#######################################################################################################

#5. Now that you have built a dataframe of the postal code of each neighborhood:
		along with the borough name and neighborhood name, in order to utilize the Foursquare location data, we need to 
		get the latitude and the longitude coordinates of each neighborhood. Given that this package can be very unreliable, 
		in case you are not able to get the geographical coordinates of the neighborhoods using the Geocoder package, here 
		is a link to a csv file that has the geographical coordinates of each postal code: http://cocl.us/Geospatial_data

#######################################################################################################
Notebook: ### Toronto_Cluster Practice 3.ipynb                                                      ###
#######################################################################################################

#6.Explore and cluster the neighborhoods in Toronto. You can decide to work with only boroughs that contain the word Toronto and then replicate the same analysis we did to the New York City data. It is up to you.
	Just make sure:
		1-to add enough Markdown cells to explain what you decided to do and to report any observations you make.
		2-to generate maps to visualize your neighborhoods and how they cluster together.
#######################################################################################################
Notebook: ### Capstone Project - The Battle of Neighborhoods WK1.ipynb                              ###
#######################################################################################################
#7.A description of the problem and a discussion of the background. 
   A description of the data and how it will be used to solve the problem.

For the second week, the final deliverables of the project will be:
#######################################################################################################
Notebook: ### Capstone Project - The Battle of Neighborhoods WK2.ipynb                              ###
Files CSV :Police Facility Locations.csv, wellbeing_toronto-SAFETY-DEMOGRAPHICS.csv                 ###
#######################################################################################################

#8.For the second week, the final deliverables of the project will be:

	1- A link to your Notebook on your Github repository, showing your code. (15 marks)
	2- A full report consisting of all of the following components (15 marks):
	3- Introduction where you discuss the business problem and who would be interested in this project.
	4- Data where you describe the data that will be used to solve the problem and the source of the data.
	5- Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, if any, and what machine learnings were used and why.
	6- Results section where you discuss the results.
	Discussion section where you discuss any observations you noted and any recommendations you can make based on the results.
	Conclusion section where you conclude the report.
	3. Your choice of a presentation or blogpost.
https://medium.com/@jmhuertasg/coursera-capstone-project-the-battle-of-neighbourhoods-83a09c51fab6
