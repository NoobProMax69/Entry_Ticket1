The task

For the last couple of months you and a couple of friends have had a lot of fun trying to become better at cooking. You have met up every other week, decided what to cook, gone grocery shopping together, and finally used some teamwork to actually cook a meal and eat it. The meals have often been delicious but sometimes you have forgot to buy some ingredients or have bought the wrong ones, resulting in you having to improvise and even if you all laugh at it, you all agree that improvising is not something you are ready for yet.

To help with the shopping you have decided to write a script that can be used to create a shopping list. Your idea of how the script shall work is as follows, first you want the user to enter a title or heading for the shopping list then you want to use a loop with a menu that allows the user to add all the items that should go on the shopping list or see what items have been added so far. The items shall be stored in a string, each item separated by a new line character. Here is an illustration of what you have in mind:




Have the script mimic the functionality and formatting shown in this example videoLinks to an external site. of how it shall look when running the finished script. Pay special attention to how an erroneous input is handled, how the menu is formatted, and to the formatting of the final shopping list. Here is a breakdown of these three parts specifically:
Erroneous input in the menu
If the user enters an invalid menu option the following error message shall be displayed before the user is returned back to the menu allowing them to try again.

Error: Invalid choice, please try again.


Formatting of the menu
The menu shall have three options and shall be formatted exactly as can be seen below.

1. Add an item
2. Print currently added items
3. Finished


Formatting of the shopping list
When the user is done adding items and selects the menu option indicating this, the final shopping list shall be displayed using the following format:

--------------------
   Shopping 30/6
--------------------
Bread
Milk
Onions
Some clarification regarding the formatting:

The two lines with dashes shall contain 20 dashes each
The title shall have a minimum width of 20 and be center aligned
Each item in the shopping list shall be printed on its own line