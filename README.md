# Hangman Flutter Game 🎮

![banner](https://user-images.githubusercontent.com/73842931/203234278-72dc4c28-0542-475e-8b0a-a64993b7f79b.png)

A simple and fun Hangman game built with [Flutter](https://flutter.dev/) to challenge your vocabulary skills! Guess the word before the hangman is fully drawn. With various categories and customization options, this game is perfect for all ages.

## 🌟 Features
- **Start a game instantly** with the default category.
- **Choose from pre-made categories** or create your own category (add/edit/delete words).
- **Dynamic gameplay** with 6 chances to guess the word before losing.
- **Restart the game anytime** with a new word from the same category.
- **Game Over page** displays the correct word and options to try again or go back to the home page.
- **Win Dialog** when you successfully guess the word.
- Interactive and visually appealing **hangman figure** updates with every wrong guess.

## 🖌️ Design
- **Home Page**: Start the game, choose a category, or learn about the app.
- **Category Selection Page**: Browse or create categories to customize your game.
- **Game Page**: Play the game, track your guesses, and manage chances.
- **Game Over Page**: Try again or return to the home page.

### 🎨 Color Palette
```dart
class AppColor {
  static Color primaryColor1 = Color(0xFF556869); // Cambridge Blue
  static Color primaryColorDark1 = Color(0xFF81A59A);
  static Color secondryColor1 = Color(0xFFECC3B0); // Buff
  static Color secondryColorDark1 = Color(0xFFCFBFB9);
  static const Color teaGreen = Color(0xFFCEDAB9); 
  static const Color primaryColorDark = Color(0xFF7F9F92);
  static const Color primaryColor = Color(0xFFA2C1A3);
  static const Color secondryColor = Color(0xFFF3DEAF); // Wheat
  static const Color secondryColorDark = Color(0xFFEBC389); 
}
📂 Project Structure
Models:
Category: Represents a word category with its list of words.
Game: Tracks the current game state, guessed letters, and remaining chances.
Widgets:
FigureImage: Displays the hangman figure dynamically.
Letter: Represents individual letter tiles.
Pages:
HomeScreen: Entry point of the app.
CategorySelectionPage: Manage and choose categories.
GamePage: Core gameplay logic and UI.
GameOverPage: Displays results after a win or loss.
🚀 Getting Started
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/doctorcode9/hangman_flutter.git
Navigate to the project directory:
bash
Copy code
cd hangman_flutter
Install dependencies:
bash
Copy code
flutter pub get
Run the app:
bash
Copy code
flutter run
🛠 Prerequisites
Flutter SDK
A code editor like VS Code or Android Studio.
🤓 Good People
<a href="https://github.com/doctorcode9"><img align="left" src="https://avatars.githubusercontent.com/u/73842931?s=100" height="75"></a>

<br> <br>
🎥 Preview


🛠️ Techniques Used
Architecture: MVC (Model-View-Controller)
Lottie: For dynamic animations.
Path Provider: For managing file storage.
URL Launcher: To handle external links.
Audio Players: For adding sound effects.
📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

❤️ Acknowledgements
This project is part of the University-sponsored Next Academy's Flutter programming instruction.

Enjoy the game and challenge your friends! 🕹️


### **Next Steps**
1. Copy this content into a `README.md` file in your repository.
2. Customize the placeholder links/images if required.
3. Ensure the `assets` (like preview images or gameplay GIFs) are added to your repository or hosted online for accessibility. 

Let me know if you'd like additional tweaks!
