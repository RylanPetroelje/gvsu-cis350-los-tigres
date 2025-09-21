Team name: Los Tigres

Team members: Rylan Petroelje, Team Member 2, Team Member 3, Team Member 4

# Introduction

PickyPrep is a meal preparation tool designed for picky eaters. Pickyprep will let the user choose ingredients they either like, tolerate, or don't like, and then will provide recommendations based off of the information it's given.

- A login system with a username and password that saves your preferences.
- Ingredient Like/Dislike List: Users can mark foods they like, tolerate, or won't eat
- Texture/Flavor Tags
- Allergy Tracking
- Gradual Exposure to certain ingredients (tags 

# Anticipated Technologies

- Retool: Will act as our front end and pull from MariaDB
- MongoDB: Primary database for storing data and running queries
- Jira: Ticketing software to assign eachother goals and bugfixes
- VSCode: IDE for any non-database coding we need to write.

# Method/Approach

* Store likes/dislikes, allergies, preferred cuisines inside a user database
* Pull Foods from a Recipes database using queries focused on ingredients
* Returns options for breakfast, lunch, and dinner
* Returns total ingredients needed.

# Estimated Timeline

* Phase 1
  -  Create system for users input ingredients they like/dislike
     + Build a frontend for this
     + Worry about actual values for these later
     + Generate queries to pull from a database
* Phase 2
  - Populate a recipe database
     + Either use public APIs like Spoonacular, Edamam, or USDA FoodData Central
     + Or build our own
     + Or both
  - Then we can fill the ingredients dataset
* Phase 3
  - Code everything




# Anticipated Problems

The Recipe database will probably be a mess. I can already think of all the tags we are going to want to put on each food. Ingredients will be diverse so having a large dataset is best for variability. 


