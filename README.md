# Gas, Cash & Chaos

Gas, Cash & Chaos is a browser-based road-trip game built with HTML, CSS, and JavaScript.

You are the only driver available for a summer trip to the beach. Keep the car moving, respond to random events, and manage fuel, money, stamina, morale, and tension until you reach the destination.

The game stores your selected character and current progress in the browser with `localStorage`.

## Game features

- Three selectable characters
- Random events with choices that change your stats
- Six possible endings, including one successful ending
- A gallery that records unlocked endings
- A pause menu and an in-game progress display

## How to run the game locally

The game has no package dependencies or build step.

1. Download or clone this repository.
2. Open the `Gas-Cash-Chaos` folder.
3. Open `index.html` in a modern web browser.

You can also serve the project with a local web server. For example, if you have the VS Code Live Server extension, right-click `index.html` and select **Open with Live Server**.

## How to play

1. Select **Avatar** from the main menu to choose a character.
2. Select **Play** to start a new trip.
3. Hold `D` or the right arrow key to drive.
4. Select the event icon when it appears.
5. Choose an action during each event and watch how it changes your stats.
6. Press `Esc` to pause or resume the game.

Reach the destination before fuel, money, stamina, or morale reaches zero. The trip also ends if tension reaches 100.

## Project structure

```text
Gas-Cash-Chaos/
|-- index.html          # Main menu
|-- Avatar.html         # Character selection
|-- Prologue.html       # Story introduction
|-- Game.html           # Driving screen
|-- Event.html          # Random event screen
|-- Gallery.html        # Unlocked endings
|-- Info.html           # In-game instructions
|-- Win.html            # Successful ending
|-- GameOverPages/      # Loss endings
|-- css/                # Page styles
|-- images/             # Game art and interface assets
`-- js/                 # Game logic and browser storage
```

## Built with

- HTML5
- CSS3
- JavaScript
- Web Storage API
