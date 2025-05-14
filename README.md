# codepath-prework

**ColorChangerApp**

**Description**

I created ColorChangerApp as a simple iOS application to practice my skills in Swift and Xcode. The app changes the background color to a random color every time I tap a button. I built it as a beginner-friendly project to understand UI elements and basic Swift functions.

**Features**

Changes the background color when the button is tapped.

Displays static labels with my name, university, and my aspirational job.

Simple and interactive user interface.

**Technologies Used**

Xcode

Swift

Storyboard for UI Design

**Getting Started**

**Prerequisites**

Xcode (version 14.0 or higher)

macOS Monterey or later

**Installation**

Clone the repository:

git clone https://github.com/yourusername/ColorChangerApp.git
Open the project in Xcode:

open ColorChangerApp.xcodeproj
Build and run the app on a simulator or a physical device.

**Usage**

Launch the app on the simulator.

Tap the button to change the background color.

**Code Overview**

**Main Functionality**

The button triggers a function that generates a random color using RGB values.

func changeColor() -> UIColor {
    let red = CGFloat.random(in: 0...1)
    let green = CGFloat.random(in: 0...1)
    let blue = CGFloat.random(in: 0...1)
    return UIColor(red: red, green: green, blue: blue, alpha: 0.5)
}

@IBAction func changeBackgroundColor(_ sender: UIButton) {
    let randomColor = changeColor()
    view.backgroundColor = randomColor
}
**App Brainstorming**

****Favorite Apps and Features
****
Instagram

Changing the background color of the messages screen.

Deleting old messages.

Spotify

Personalized playlists based on my listening habits.

Ability to download songs for offline listening.

Duolingo

Daily reminders to practice.

Gamified progress tracking.

**My App Idea**

I would like to build an app called MoodColor. The app will change the background color based on my current mood, which I can select from a list. The goal is to create a visually soothing experience that helps me track and reflect on my emotions. Additional features could include saving mood history and generating mood insights.

**Contributing**

Feel free to fork the project and make your own improvements. Pull requests are welcome.

**License**

This project is licensed under the MIT License.
