# Project_1B - Color Crush

This is a 8x8 grid Match-Three, game similar to Candy Crush. 


###Technology
The technology used include:

- HTML;
- CSS;
- Javascript and jQuery 2.2.4.


###How it works

The game uses HTML/CSS flexbox to lay out the squares in the grid. The presentation and game logic are cleanly separated - styling is mostly done via CSS. The actual grid state is stored within a 'grid' array in javascript. 

A start grid is presented to the player. Players can then swap between adjacent squares to form a row or column with the same type of square. These same squares are 'destroyed' and squares above them fill their place.

This swap-destroy-fill cycle is repeated until there are no more possible moves.
