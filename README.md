# project-3-blue-team

## Our Project and Purpose
Our project analyzes data on food donation from [South Philadelphia Community Fridge](https://www.southphillyfridge.com). South Philadelphia Community Fridge (SPCF) is an all-volunteer mutual aid organization in the South Philadelphia neighborhood that provides 24/7 no-questions-asked food aid through a network of free fridges and pantries. The visualizations and analysis produced by our project will be used by SPCF in grant applications and conversations with funders to depict the scope and scale of the organization's work. 

## How to Use Our Project
Our Jupyter Notebook contains interactive graphics that can only be viewed on Binder. Use the button to view the notebook on Binder.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vjayne93/project-3-blue-team/HEAD?labpath=fridge_fills_binder.ipynb)

In order to meet the requirements of this project, our repository contains two versions of our code. The first, fridge_fills.ipynb, shows how we used PyMongo to extract data from MongoDB and converted the database into CSV files within the notebook. The second version of our code, fridge_fills_binder.ipynb, analyzes data directly from the CSV files. This second version of our code can be deployed in [Binder](https://mybinder.org/v2/gh/vjayne93/project-3-blue-team/HEAD?labpath=fridge_fills_binder.ipynb) so the end user can use the dynamic widgets and visualizations.  

![LUHV_FILL](https://github.com/vjayne93/project-3-blue-team/assets/152992214/faa4be10-6c31-4147-a5cd-9e6e1b88a756)

Our dataset includes every <i>"fridge fill"</i> in the year 2023. A "fridge fill" is the organization's terminology for any food donation to a fridge or pantry location. The data was tracked by volunteers who delivered and stocked food.  

![IMG_5669](https://github.com/vjayne93/project-3-blue-team/assets/152992214/3c586e3a-bc59-4f98-b290-f02d997ae32b)

The five types of "fridge fills" tracked in the dataset are Rescued Groceries, Purchased Groceries, Meals, Homecooked Meals, and Food Drive. <br>
<b>Rescued Groceries</b> are donated from grocery stores, larger food banks, restaurants, bakeries, and similar sources of food. <br>
<b>Purchased Groceries</b> are bought by volunteers with funds donated from supporters. <br>
<b>Meals</b> are made in commercial kitchens supporting organizations, such as Double Trellis Food Initiative, The People's Kitchen, Asian Food Collective, and others.<br>
<b>Homemade Meals</b> are made by volunteers. <br>
<b>Food Drive</b> donations come from schools, workplaces, religious organizations, events, and other groups that collect food to donate. <br>

![IMG_7905_Original](https://github.com/vjayne93/project-3-blue-team/assets/152992214/21d9122c-c59b-4cf8-9557-1b54dd5e4d0c)

## Ethical Considerations
Our data was obtained directly from volunteers at SPCF with their permission. SPCF does not obtain identifying information about anyone who receives food from their fridges and pantries to reduce stigma and protect privacy. Our dataset includes the chosen names of volunteers who picked up and delivered food to community fridge and pantry locations. We did not include names of volunteers in our final analysis or visualizations, as comparing the activity of different volunteers or specifiying particular volunteers as the most productive is not in line with the spirit of mutual aid, and is not relevant to our project's purpose. 

## Data References
Our dataset was collected by volunteers at SPCF, with significant contributions from volunteers Ginny Robinson, Rose MW, and Kathryn Nolan. 

## Code References
We received guidance from the [mybinder.org-user-guide repository.](https://github.com/jupyterhub/mybinder.org-user-guide) We used guidance from the EdX XPert Learning Assistant AI in the development of our code. 

## Contributions:
 
Fara Naghavi: 
Question(s): Which community fridge location received the most donations? Did this change based on the time of year?
Graph(s): Choropleth map (South Philadelphia Community Fridge)
          Donations Received per Month in 2023

Jessica Chellappa:
Question(s): In what month were there the most food donations? In what month were there the least food donations? 
Graph(s): Donations by Dropoff Location

Victoria Martin-Nelson:
Question(s): Which type of fill is most prevalent? Does this change month by month?
Graph(s): Total Days in Operation 
          Total Number of Dropoffs
          Average Donations all Days in Operation 
          Average Donations per Day for Each Location 
          Total Fills per Month for Each Fill Type in 2023

Mia Hursh: 
Question(s): Which time of day are there the most food donations? Does this vary by month?
Graph(s): Donations by Time of Day across Months in 2023
          Donations by month
