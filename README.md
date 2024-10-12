# Quiz-App

This is a simple Quiz App built using Java in Android Studio. The app allows users to take quizzes and get instant feedback on their performance. It supports multiple-choice questions and keeps track of the user's score.

## Features

- Multiple-choice questions with 4 options each.
- Displays the user's score at the end of the quiz.
- Simple and intuitive UI.


## Requirements

- Android Studio 4.0+
- Java 8+
- Minimum SDK Version: 21 (Android 5.0 Lollipop)
- Gradle Version: 7.0+

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/lisharodrigues/Quiz-App.git
   cd Quiz-App
   ```

2. **Open in Android Studio:**
   - Open Android Studio.
   - Select `Open an existing project` and choose the `Quiz-App` directory.
   - Let Android Studio configure the project.

3. **Build the project:**
   - Sync the Gradle files by clicking on "Sync Now" when prompted.
   - Build the project by selecting `Build` > `Make Project`.

4. **Run the app:**
   - Connect your Android device or launch an Android Emulator.
   - Click on the green play button in Android Studio to run the app.


## Customization

- **Add more questions:** To add more questions, modify the `PlayActivity.java` class or the questions array in the `MainActivity.java`.
- **Modify themes:** Customize the app theme by editing the styles in `res/values/styles.xml`.

## Future Improvements

- Add support for different question types (e.g., True/False, Fill in the Blank).
- Store high scores locally using SQLite or SharedPreferences.
- Implement user authentication and store quizzes in a cloud database (Firebase).
- Add animations for a better user experience.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with any enhancements or bug fixes.

