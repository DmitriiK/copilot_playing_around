Need to create a kind of Schulte Table as an HTML page.
But instead of numbers, it should use icons—each icon represents some fruit or vegetable. You can use Unicode emoji to display fruit.
The order of the items is specified at the beginning of the game and is shown on the game field at the top as a subset: one row with buttons, like a sliding window with the number of buttons equal to the size of the main grid.
This row and the main grid should be in separate bordered containers. In the "ordering row" border, you should have the label "Ordered items" at the top.
Each time the user correctly clicks the icon on the main grid, the subset of items in this row slides left—so the icon from the clicked button (which is supposed to be top-left) disappears, the remaining buttons move to the left, and a new icon appears at the top-right side of the row to display the order.
Each time the user incorrectly clicks a button in the main grid, it should briefly flash red.

The gameplay should:
- Allow specifying the size of the main grid (from 4 to 6). The default value is 4, and both the main grid and ordering row should already be populated at the very beginning.
- Once the user changes the grid size in the option control, both grids should be rebuilt.
- Have Play/Stop buttons.
- Have a timer.
