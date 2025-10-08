Team name: Los Tigres

Team members: Rylan Petroelje, Jacob Ferry, Landon Wissink, Sujan Tamaring

# Introduction

PickyPrep is a meal preparation tool designed for picky eaters. PickyPrep will let the user choose ingredients they either like, tolerate, or don't like, and then will provide recommendations based off of the information it's given.

- A login system with a username and password that saves your preferences.
- Ingredient Like/Dislike List: Users can mark foods they like, tolerate, or won't eat
- Texture/Flavor Tags: Relevant recipes and ingredients will be marked with tags like chewy, granular, mushy, and other features picky eaters generally have distaste for. The idea behind this is that if we are making software for picky eaters, we want to be comprehensive and take into account another real point of interest.
- Allergy Tracking: Recipes will be marked if they contain popular allergens (Eggs, Dairy, Gluten, etc.)
- Gradual Exposure to certain ingredients: Recommend users recipes with maybe 1 or 2 ingredients they marked as tolerate or didn't like.

# Anticipated Technologies

- Retool: Will act as our front end and pull from MongoDB
- MongoDB: Primary database for storing data and running queries
- GitHub: Central software used for ticketing and storing project details
- VSCode: IDE for any non-database coding we need to write.

# Method/Approach

* Store likes/dislikes, allergies, and preferred cuisines inside a user database
* Pull Foods from a Recipes database using queries
* Returns options for breakfast, lunch, and dinner
* Returns total ingredients needed.

# Estimated Timeline

* Phase 1 (September 1 - 30)
  -  Create a project proposal
  -  Define functional and nonfunctional requirements.
  -  Define anticipated technologies and become aquainted with them
  -  Create a wire-frame on paper of what we want this application to look like on the front-end and how we want the pages to link to eachother.
* Phase 2 (October 1 - 31)
  - Create a database with the following tables (MongoDB):
    + Users (UID, username, password, preferences, allergies)
    + Ingredients (IID, ingredient_name)
    + Recipes (RID, recipe_name, ingredients, texture_tags, allergens)
  - Populate Ingredients and Recipes tables with public data.
  - Build the frontend of the website with retool
* Phase 3 (November 1 - 30)
  - Link our frontend with MongoDB so we can both push data into it and pull data out.
  - Add any final touches
  - Fix any final bugs.
* Phase 4 (December 1 - 15)
  - Present the final project

# Anticipated Problems

The Recipe database will probably be a mess. I can already think of all the tags we are going to want to put on each food. Ingredients will be diverse so having a large dataset is best for variability. 

