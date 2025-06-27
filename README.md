# quotes-project

#  Mindful Minutes

**Mindful Minutes** is a responsive mental wellness web app designed to promote calm, self-awareness, and positivity. It provides 1-minute meditations, breathing exercises, daily affirmations, mood tracking, light/dark mode toggle, and peaceful background music.

---

##  Features

-  **Daily Affirmation**  
  Random affirmation displayed from a JSON server or fallback quotes.

-  **1-Minute Meditation**  
  Simple timer and tracking to guide users through 1-minute mindful breaks.

- 🌬 **Breathing Exercise**  
  Animated breathing cues (e.g., "Breathe in", "Hold", "Exhale").

-  **Mood Tracker**  
  Save and view mood entries (7-day history) powered by `db.json`.

-  **Background Music**  
  Peaceful ambient music with toggle controls (mute/unmute).

-  **Light/Dark Mode Toggle**  
  Theme persistence with `localStorage`.

## screenshot
![image](https://github.com/user-attachments/assets/23094cd0-323b-4d94-9556-f6e56acd81b4)


---

## Tech Stack

- HTML, CSS, JavaScript (Vanilla)
- JSON Server (`db.json`)
- LocalStorage (for theme/music state)
- Responsive Design with Flexbox and Media Queries

---

## Project Structure

quotes-project/
│
├index.html
├ css/
│  style.css
├ js/
│  quote.js
├assets/
│  music.mp3
├ db.json
└ README.md

## Usage
1. Open index.html in your browser.

2. Toggle between light/dark mode.

3. Play or mute the relaxing background music.

4. View a new daily affirmation.

5. Select your current mood — it saves to the backend.

6. Start a 1-minute meditation or breathing session — it logs your activity.

7. View the past 7 days of mood history.
## NB you must run the json-server to view the mood history.



---

## Getting Started

### 1. Clone the Repo
git clone https://github.com/your-username/quotes-project.git
cd quotes-project

open the terminal live server to see the real action.
if installed, run JSON-SERVER in the terminal by: $:json-server --watch db.json
if not installed run $:npm install -g json-server.


## Inspiration
This project was created to promote mental wellness through small, mindful actions that fit into any daily routine — because even one minute of awareness can make a difference.

## Author
Built with love and mindfulness by Horace Kauna 💚
Your calm is your superpower.
https://github.com/Horace01b/quotes-project

## License
MIT License © 2025 [horace01b]


