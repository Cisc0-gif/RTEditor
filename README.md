# RTEditor v1.1 (a tool for GameMaker)

RTEditor is a UI tool that allows developers to set variables during Runtime, making minor adjustments on the fly instead of the generally inefficient GameMaker process of write code, compile, repeat. With greater flexibility, developers can move on-screen UI elements around, change object sprite size, test values, and much more with this tool every GameMaker developer should have in their back pocket.

## Features
* Displays current mouse position (x, y)
* Change any variable of any data type during Runtime
* Set fullscreen and restart game with a key press
* Draggable window that stays on screen if camera moves

## How to use

### Import
To import RTEditor to your game, simply go to ``` Tools > Import Local Package ```, select ```RTEditor.yymps```, and the group ```RTEditor``` will appear in the Asset viewer.

### Use
1. Open ```obj_RTEditor``` and in the Create event and initialize the variables you want to set (Ex: ```global.player_x```). 
2. Add the name of the variable as a string in ```RTE_VARS``` (Ex: ```RTE_VARS = ["player_x"]```).
3. Now change the variable in the object/script you want to test to the global variable you initialized (Ex: ```global.player_x```).
4. Next, simply drag ```obj_RTEditor``` into the room you are working in and run your game!

### Controls
* Use the ```UP``` and ```DOWN``` arrow keys to change variables if you have multiple
* ```Enter``` to set your variable
* ```DEL``` to hide/show RTEditor (won't take input while hidden)
* ```PAGE DOWN``` to set fullscreen
* ```PAGE UP``` to restart game
* Click and hold UI with ```LMB``` to drag it across screen

## Authors

* **Cisc0-gif** - *Main Contributer/Author*

## License

This project is licensed under the GNU General Public License v3 - see the LICENSE file for details

