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

## 🎨 Color Palette

| Name                   | Hex Code     | Preview                  |
|------------------------|--------------|--------------------------|
| Tea Green              | `#CEDAB9`    | ![Tea Green](https://via.placeholder.com/100x100/CEDAB9?text=+) |
| Cambridge Blue         | `#7F9F92`    | ![Cambridge Blue](https://via.placeholder.com/100x100/7F9F92?text=+) |
| Cambridge Blue 2       | `#A2C1A3`    | ![Cambridge Blue 2](https://via.placeholder.com/100x100/A2C1A3?text=+) |
| Wheat                  | `#F3DEAF`    | ![Wheat](https://via.placeholder.com/100x100/F3DEAF?text=+) |
| Buff                   | `#EBC389`    | ![Buff](https://via.placeholder.com/100x100/EBC389?text=+) |
| Primary Color Dark     | `#556869`    | ![Primary Color Dark](https://via.placeholder.com/100x100/556869?text=+) |
| Primary Color          | `#81A59A`    | ![Primary Color](https://via.placeholder.com/100x100/81A59A?text=+) |
| Secondary Color        | `#ECC3B0`    | ![Secondary Color](https://via.placeholder.com/100x100/ECC3B0?text=+) |
| Secondary Color Dark   | `#CFBFB9`    | ![Secondary Color Dark](https://via.placeholder.com/100x100/CFBFB9?text=+) |

## 📂 Project Structure
- **Models**:
  - `Category`: Represents a word category with its list of words.
  - `Game`: Tracks the current game state, guessed letters, and remaining chances.
- **Widgets**:
  - `FigureImage`: Displays the hangman figure dynamically.
  - `Letter`: Represents individual letter tiles.
- **Pages**:
  - `HomeScreen`: Entry point of the app.
  - `CategorySelectionPage`: Manage and choose categories.
  - `GamePage`: Core gameplay logic and UI.
  - `GameOverPage`: Displays results after a win or loss.

## 🚀 Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/doctorcode9/hangman_flutter.git
   cd hangman_flutter
   flutter pub get
   flutter run
🤓 Good People <a href="https://github.com/doctorcode9"><img align="left" src="https://avatars.githubusercontent.com/u/73842931?s=100" height="75"></a>

<br> <br> 🎥 Preview

<!-- Add your screen recording here -->

🛠️ Techniques Used

Architecture: MVC (Model-View-Controller)
Lottie: For dynamic animations.
Path Provider: For managing file storage.
URL Launcher: To handle external links.
Audio Players: For adding sound effects.
📜 License This project is licensed under the MIT License - see the LICENSE file for details.

❤️ Acknowledgements This project is part of the University-sponsored Next Academy's Flutter programming instruction.

Enjoy the game and challenge your friends! 🕹️



### Changes made:
1. **Color Palette**: Increased the size of the color previews to `100x100` for better visibility.
2. **Screen Recording Placeholder**: Added a placeholder space with the label "Add your screen recording here." You can replace the placeholder link with the actual video URL once you have the recording ready.


