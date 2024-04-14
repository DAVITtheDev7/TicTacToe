## TicTacToe Android App

This repository contains the source code for a simple TicTacToe game for Android, developed in Java using Android Studio. The game features a dynamic user interface built with the help of Android's `ViewBinding`, enabling easy access and manipulation of UI components.

### Features
- **Interactive UI**: The game features a user-friendly graphical interface, with images representing the X and O marks.
- **Multiplayer**: Two players can play the game, taking turns to mark Xs and Os in a 3x3 grid.
- **Winning Logic**: The app checks for a winner after each move, considering all possible winning combinations.
- **Dynamic Player Turns**: Highlights the current player's turn visually in the UI.
- **Reset Functionality**: Players can restart the game at any time using a reset feature.

### How It Works
- **Player Interaction**: Players tap on the grid images to mark their X or O.
- **Game Progression**: The app keeps track of the turns and marks on the board. It updates the board based on player input and switches turns between players.
- **Win Check**: After every move, the app checks if there's a winner by evaluating predefined winning combinations.
- **End Game**: If a player wins or all squares are filled without a winner, a dialog shows the game result, and players can choose to restart.

### Technologies Used
- **Android Studio**: For development and testing.
- **Java**: Main programming language used.
- **Android SDK**: Provides tools and APIs necessary to develop apps for Android.
- **ViewBinding**: Used to more easily interact with views using their IDs in a type-safe manner.

### APK Download
You can download the APK and try out the app using this link:
[Download TicTacToe APK](https://drive.google.com/file/d/141YuxeJ9uMEuBwKSFIfP4sKUrGnDRbeY/view?usp=sharing)

### Installation
Clone this repository and import into **Android Studio**
```bash
git clone https://github.com/DaviDM2005/TicTacToe.git
```
Build the project in Android Studio and run it on an emulator or actual device.

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

