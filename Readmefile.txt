The code includes three classes:Ingredient, Step, and Recipe.The Ingredient class represents an ingredient and includes features like name, quantity, unit, calories, and food group.
The Step class is used to represent a recipe step and includes a description property.The Recipe class handles recipes and has properties for name, ingredients, and steps.
The Recipe class includes a delegate called RecipeExceedsCaloriesHandler that notifies when a recipe's total calories surpass 300. A RecipeExceedsCaloriesEvent event to which you can subscribe to get updates.How to add ingredients and steps to a recipe.
A way for displaying the recipe details.A method for calculating the total calories in a recipe.
A technique for determining whether the total calories surpass 300 and triggering the RecipeExceedsCaloriesEvent if necessary.
The Main' method of the Program class is the application's entry point. It creates a list for storing recipes.Asks the user to submit recipe information (name, number of components, number of stages) until they type "exit".
Adds every recipe to the list.Sorts the recipes alphabetically by name and provides a list of recipe names.
Allows the user to select a recipe to display. Displays the information of the selected dish, including the total number of calories.
Subscribes to the 'RecipeExceedsCaloriesEvent' of the selected recipe and checks to see whether the total calories surpass 300, displaying a warning message if so.
The code enables users to create and manage recipes, such as adding ingredients and steps, viewing recipe details, calculating total calories, and receiving notifications if a recipe exceeds a calorie limit.
The code now features a more complex design. The Ingredient class now has characteristics for calories and food groups, and a new Step class handles step descriptions. The Recipe class now includes properties for name, ingredient and step lists, and event handling to inform when total calories surpass 300. 
Ingredients and steps can now be added, recipe details displayed, total calories calculated, and calorie limits checked.
The primary program now allows users to create numerous recipes, enter details interactively, sort recipes alphabetically, choose a recipe to display, calculate and display total calories, and receive warnings when recipes exceed 300 calories. 
Overall, the code provides a more comprehensive and user-friendly recipe management system, including additional tools for recording nutritional information.

https://github.com/ST10386008/RECIPEAPP



