PocketBeagle User Interface
=========================
based on : https://github.com/jadonk/Beaglebone-UI

This is a UI that allows a user to interact with a pocketbeagle board with minimal to no coding experience. This allows a user to communicate to the board and use the ADC pins, digital (inputs, outputs, pwms) pins, and the user leds located at the top of the board. The only requirement is that the desired circuit is correct for the code to function properly. The code assumes that socket.io has been installed within cloud9, otherwise the location may need to be changed. The locations of the files within cloud9 are in a folder called BBUI. The html file contains the user interface and interactions from the user are sent to the js file, which uses socket.io to communicate to the board. The page runs on yourbeagleboneip:8070. Changes can be made to the file locations and file names at the top of the js file.
