---
toc: false
layout: post
comments: false
categories: [APCSP]
title: Personal CPT Progress Check Notes
---

## Purpose and Function
The purpose of my CPT project is to allow users to easily look for recipes from our entire database so that they find the perfect one for them

The function is that the users will be able to use a search bar to type in a certain recipe that they want, and they will see the most relevant results based on the keywords for each recipe.
&nbsp;
## Data Abstraction
When the JSON data for all the saved recipes is parsed, then a list called relevantRecipes, will record all of the relevant recipes based on the keywords of the recipe. This will appear on a table on the website after the user searches for their recipe.

&nbsp;
## Managing Complexity
Using keywords for each recipe and storing the results in a list based on the keywords, allows for a simple way to display results of the search.

&nbsp;
## Procedural Abstraction
First, the user will enter an input in the search bar and this will send a request to the server, then, a procedure called recipeSearch() will search through the recipes in the database and all the keywords of the recipe to display relevant results. Furthermore, a function called sortingRecipes() will order the recipes from most to least relevant. Finally, the procuedure will also delete the list after exiting the search feature.

&nbsp;
## Algorithm Implementation
Sequencing will be used to order the results of the inputs from the relevance by using predefined keywords for each recipe.

&nbsp;
## Testing
1. My first test will be to check if the procedure correctly places the relevant recipes in the list
2. Test if a new list is created for new searches and this is deleted when the user exits the search, or the the website altogether

&nbsp;
## Video Plan