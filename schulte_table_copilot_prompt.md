# Game description
Need to create a kind of Schulte Table as an HTML page.
As usual with a Schulte Table, it should have a square grid of buttons, let's call it the main grid.
But instead of numbers, it should use icons with pictures from some category, - let's say animals, food, or sport. You can use Unicode emoji for this.

# Gameplay detailed description
The order of the items is specified at the beginning of the game and is shown on the game field at the top as a subset of pictures from the main grid: one row with buttons, like a sliding window with the number of buttons equal to the size of the main grid. Let's call this part of the game field "ordered items."

This row and the main grid should be in separate bordered containers. In the "ordered items" border, you should have the label "Ordered items" at the top, as part of the border. It should contain the same number of buttons as the main grid and should always be on top of it, regardless of the browser window size.

the main grid should already be populated after the page is loaded, but the ordered items row should contain empty buttons at this point—it should be populated with icons once the game starts. 

Each time the user correctly clicks the icon on the main grid, the subset of items in this row slides left, so the icon from the clicked button (which is supposed to be the top-left in ordered items) disappears, the remaining buttons move to the left, and a new icon appears at the top-right side of the row to display the order.
Each time the user incorrectly clicks a button in the main grid, it should briefly flash red.
The game is finished once the user correctly clicks all the buttons on the main grid.

# Game field
The game field should have, besides the main grid and ordered items:
- Play/Stop buttons.
- A timer.
- A control to specify the category: animal or food.
- A control for specifying the size of the main grid (from 4 to 6, 4 is default). Once the user changes the grid size in the option control, both grids should be rebuilt.
- Under the "ordered items" row, display the name of the current item to be found in both English and Turkish (e.g., "Apple - Elma" or "Dog - Köpek"). This bilingual label should update each time a new item needs to be found.

# Non-functional requirement
- Use a separate .css file

