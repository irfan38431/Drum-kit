# Drum Kit 🥁

A simple interactive Drum Kit application that allows users to play drum sounds by clicking on buttons or pressing keys on their keyboard. Each button on the screen corresponds to a different drum sound, making it easy to create rhythmic beats.

## Features

- **Interactive UI:** Click on the buttons on the screen to play different drum sounds.
- **Keyboard Support:** Use the keyboard keys ('w', 'a', 's', 'd', 'j', 'k', 'l') to play corresponding drum sounds.
- **Sound Effects:** Includes a variety of drum sounds like toms, crash, kick-bass, and snare.

## How It Works

- Each button on the screen is associated with a specific sound file.
- When a button is clicked or its corresponding keyboard key is pressed, an event listener triggers the appropriate sound to play.
- The JavaScript code dynamically binds these events and plays the sounds.

## Project Structure

```
Drum-Kit/
│
├── index.html          # Main HTML file
├── styles.css          # Styles for the Drum Kit
├── index.js            # JavaScript for sound events
└── sounds/             # Folder containing sound files
    ├── tom-1.mp3
    ├── tom-2.mp3
    ├── tom-3.mp3
    ├── tom-4.mp3
    ├── crash.mp3
    ├── kick-bass.mp3
    └── snare.mp3
```

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/irfan38431/drum-kit.git
    ```
2. **Open the project**:
    - Navigate to the project directory and open `index.html` in a web browser.
3. **Play the Drum Kit**:
    - Click the buttons on the screen or press the corresponding keys ('w', 'a', 's', 'd', 'j', 'k', 'l') on your keyboard to play different drum sounds.

## Technologies Used

- **HTML**: For creating the structure of the web page.
- **CSS**: For styling the Drum Kit interface.
- **JavaScript**: For adding interactivity and playing sounds.


