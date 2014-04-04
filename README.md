FileMaker recipe database
=========================

A basic recipe database for use on an iPad with FileMaker Go

##Functionality
This database is pretty basic, as it is meant to be a proof of concept containing minimal functionality. You can enter recipes, view them, search and that's about it. It is meant to be easy to use in the kitchen. The type is set at 18pt, using the Touch themes in FileMaker, which makes it legible on th iPad mini. You can add a photo to a container field, and a URL field for link to the reipe if it was originally found online, which you cn then open in a web viewer layout.

<img src="documentation/screenshots/filemaker-edit-recipe.png" width="540" alt="Edit Recipe"><br>
Edit Recipe layout on iPad

##Structure
There are 3 tables:

+ recipes
+ recipe_ingredients
+ recipe_tags

More details on the structure can be found in the Database Design report, in the 'documentation' folder. There is also a PDF relationship diagram.