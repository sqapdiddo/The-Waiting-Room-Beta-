🏢 The Waiting Building

The Waiting Building is a browser-based psychological horror game built with vanilla HTML, CSS, and JavaScript. It is a choice-driven narrative where every action is recorded, compliance is tracked, and clarity slowly erodes. There are no jump scares—only systems, procedures, and quiet consequences.

🧠 About the Game

You wake inside a bureaucratic space that insists it has seen you before.
A ticket system, forms, stamps, and rules guide you deeper into a process that never fully explains itself.

Your choices affect hidden variables such as:

Clarity (mental stability)

Compliance (willingness to follow rules)

Dread (psychological pressure)

As these values change, the game subtly alters how choices are presented and resolved.

This project is designed as Chapter One of a larger narrative.

🎮 Gameplay Features

Branching narrative with multiple endings

Persistent save system using localStorage

Conditional choices based on player state

Psychological “glitch” effects when clarity drops

Replayable paths with hidden narrative layers

No combat, no timers, no jump scares

🛠️ Tech Stack

HTML – structure

CSS – atmosphere & UI styling

JavaScript (Vanilla) – game logic & state handling

No frameworks. No libraries. Fully client-side.

📂 Project Structure
/
├── index.html        # Main HTML entry
├── style.css         # Visual styling
├── game.js           # Game engine & logic
├── storyData.js      # Story graph (JS-loaded)
├── story.json        # Raw story data (optional/reference)
└── README.md


⚠️ Note: The game uses storyData.js (not fetched JSON) to avoid CORS issues when running locally or on itch.io.

▶️ How to Run
Option 1: Local

Download or clone the repository

Open index.html in a browser

Click New to begin

Option 2: itch.io

Upload all files

Set project type to HTML

Set viewport to 630×500 (recommended)

Enable fullscreen (optional)

💾 Saving & Progress

Progress is automatically saved using localStorage.

Buttons:

New – starts a fresh run

Continue – resumes last save

Reset Save – clears progress

🎭 Content Warning

This game contains:

Psychological horror

Themes of surveillance, identity loss, and bureaucratic control

No explicit violence or gore

🔮 Future Plans

Additional chapters

Sound design & ambient audio

Visual distortion effects tied to mental state

Expanded meta-narrative across playthroughs

📜 License

This project is currently shared for portfolio and creative purposes.
All narrative content © the author.
