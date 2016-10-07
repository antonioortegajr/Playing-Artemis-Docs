#Game Master

Game Master is like the science console, but with everything fully scanned, and several extra features. IN the game it is know as game master. This role is designed to be used by a game master, a game puppeteer, just like a D&D dungeon master, or the operator of a military sim.

To use the Game Master console, your server MUST be running a mission designed for the Game Master console. By convention, these mission files should start with the word "Module", to separate them from "normal" missions that do not need a Game Master operator.

During play, the Game Master operator presses keys on the Game Master console. These key presses are sent to the server, and used by the script to trigger script events. The Game Master operator can also select objects by left-clicking them, and select points in space by right-clicking on the spot. Both selected objects and selected locations can be used by the script for various events. Finally, the Game Master console has two text entry lines, and several buttons used to send the entered text to various stations of the players' ship.

Because of the basic structure of this Game Master console system, the complexity and power of the Game Master system comes from the mission script you use. But the execution of events in the script are triggered by simple key presses. So, by convention, every Game Master script (starting with "Module") should come with a simple text file called "module-doc.txt", which details which keys do what.
