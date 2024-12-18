# Recipe-Book-App
## DESCRIPTION
Using a basic understanding of kotlin I created a CRUD mobile app for recipes. This was made with the goal to gain a better understanding in kotlin along with learning the basics of creating a app

## INSTALLATION
 - Install all the files within the Repository and keep them within the same directory
 - Open Android Studio or something else to run/create Apps
 - Run the project either in a phone emulator or on an actual phone

## FEATURES
  - OOP
  - Camera Usage (Not working yet)
  - SQLite Database

## USAGE
  - Click on New (+) to add a new recipe (Cant take pictures yet)
  - Click on View All (hamburger thing) to see all recipes on one screen and interact with them
    - Share - This will export the information about the specific recipe into a file
    - Delete - This will remove the specific recipe from the system
  - Click Random to show a random recipe that has been added to the database
  - Click Update to update information about the recipe you are currently looking at (Not working yet)

## DESCRIPTIONS

### AllRecipes
  - Shows a recycler view of each recipe in the database
  - 2 functions for each recipe share, delete
### DatabaseHelper
  - File dedicated to the database, holds helper functions to be used in other pages
### InformationFragment
  - Holds basic information on a single recipe
  - Button to show actual recipe
  - In a fragment to allow for a tablet view
### MainActivity
  - Holds both InformationFragment and RecipeFragment depending on the size of the device
  - Holds a toolbar to move around the application
### NewRecipe
  - Allows the user to create a new entry into the database
  - Uses the camera and gallery to input an image into the database (Not working yet)
  - Updating a recipe also comes to this page (It will autofill information) (Not working yet)
### RecipeActivity
  - Shows the recipe for the item that was in Main
### RecipeAdapter
  - Creates functionallity for items in the recycler view (AllRecipes)
### RecipeFragment
  - Shows the recipe for the item that is in InformationFragment (Only for large devices)


## AUTHOR(s)
  - N. Carter - https://www.linkedin.com/in/nathanielbcarter/
