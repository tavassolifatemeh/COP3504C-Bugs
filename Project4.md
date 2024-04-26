# Page Number: 4

## Description
In the requirements for the tile class, the method "public Tile(sf::Vector2f position)" passes through "position", but in the description, it says it uses "_position". This can be confusing.

## Possible Fix
Correct the method to, "public Tile(sf::Vector2f _position)" to include the underscore.

## Name: Grace Cavarretta

# Page Number: 3

## Description
The toolbox class constructor "private ToolBox()" has the B capitalized while in all other uses of toolbox, the B is lowercase. This can be confusing when reading through the instructions and cause errors. 

## Possible Fix
Correct the capitalization of the Toolbox constructor to "private Toolbox()".

## Name: Brandon Jacobson

# Page Number: 5

## Description
"GameState(sf::Vector2i _dimensions = Vector2i(25, 16), int _numberOfMines = 50)" in the GameState class requires "sf::" before "Vector2i(25, 16), otherwise it will be considered undeclared.

## Possible Fix
Add "sf::" before "Vector2i(25,16)" to make it "GameState(sf::Vector2i _dimensions = sf::Vector2i(25, 16), int _numberOfMines = 50)"

## Name: Lokaghna Velugu Boreddi

# Page Number: 6

## Description
The link for "Windows: " under Helpful Links, "https://www.sfml-dev.org/tutorials/2.5/windowtg-window.php", does not work. (Likely due to the typo "windowtg")

## Possible Fix
Update the link to "https://www.sfml-dev.org/tutorials/2.5/window-window.php", which does work.

## Name: Patrick Byrd


# Page Number: 6

## Description
The link under "Using Documentation" is broken, directing to the address "https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php%23the-white-square-problem"

## Possible Fix
Update the link address to "https://www.sfml-dev.org/tutorials/2.5/window-window.php#the-white-square-problem", which does work.

## Name: Patrick Byrd


# Page Number: 6

## Description
In the file structure, Button.h is misspelled as Buton.h. 

## Possible Fix
Correct the spelling in the image to "Button.h".

## Name: Brandon Jacobson
