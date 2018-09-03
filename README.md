# Nonogram
A more difficult Nonogram

It only shows the total number of marks for each row and column.
On the bright side, you get a green background when you got everything right in a row or column.

## Configuration
Open  index.html and search for "//settings". You can change the following:

```
//settings

var boardSize = 6;        //the board size
var global_chance = 0.4;  //the percentage under which you have a "black" cell
var unknownText = "";     //the text shown in the cells if not marked / not yet clicked
var markText = "X";       //the text shown in the cells if marked
```
