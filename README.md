
Built by https://www.blackbox.ai

---

```markdown
# Necromancer Game

## Project Overview
The **Necromancer Game** is an interactive browser-based game where players control a necromancer character who can move around a game area, attack enemies, and convert them into allies. Utilizing a simple yet engaging interface and animations, players can strategize their movements and actions to build a powerful team.

## Installation
To get started with the Necromancer Game, simply clone the repository and open the `index.html` file in your preferred web browser. There is no additional installation required.

```bash
git clone <repository-url>
cd necromancer-game
open index.html  # or use your browser of choice to open the file
```

## Usage
- **Controls**: 
  - Use the **arrow keys** to move the necromancer around the game area.
  - Press the **Space bar** to attack nearby enemies.
  
The goal of the game is to defeat enemies, converting them into allies where possible, while navigating the game area effectively.

## Features
- Dynamic character interactions with the ability to convert enemies into allies.
- Engaging animations for characters, including the necromancer, enemies, and allies.
- A health bar representation for each character, indicating their current health status.
- Simple yet intuitive controls for an engaging gameplay experience.

## Dependencies
This project uses the following external libraries and frameworks:
- **Tailwind CSS** for styling and layout.
- **Font Awesome** for iconography.
- **Google Fonts (Orbitron)** for a unique game typography.

These libraries are imported directly from their CDNs in the `index.html` file and do not require installation through `npm`.

## Project Structure
The project is structured as follows:

```
/necromancer-game
├── index.html         # Main HTML file containing game interface and logic
```

### HTML Structure
- **`<head>`**: Contains metadata, linked stylesheets, and scripts.
- **`<body>`**: Main game container, including:
  - Title and game controls info.
  - Game area where characters are displayed.
  - Info panel showing player interaction instructions and ally count.

### JavaScript Logic
The game logic is contained within a `<script>` tag in the HTML file. Key components include:
- **Character Class**: Base class for all characters (necromancer, enemies, allies).
- **Necromancer Class**: Inherits from `Character` and adds specific movement and attack mechanics.
- **Game Loop**: Handles real-time updates for character movement and game interactions.

This structure simplifies adding new features or characters in the future.

---

Feel free to customize and extend the game further, adding your own characters, artwork, and mechanics to create a unique experience!
```