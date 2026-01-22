# 📖 Omniscient Reader's Viewpoint: The First Scenario
*"The story I've been reading for 10 years has become reality."*
> **Course:** Algorithms I (Algoritmos I)  
> **Type:** Extra Activity / Interactive Story Project

## 📜 About the Project

This project is an interactive visual novel developed using a custom XML-based engine (Fable). It adapts the intense opening sequence of the famous web novel/manhwa **"Omniscient Reader's Viewpoint"**.

The player takes on the role of **Kim Dokja**, an ordinary office worker whose favorite apocalyptic novel suddenly becomes reality. Trapped in a subway car, the protagonist must navigate the "First Scenario" initiated by a Dokkaebi, making crucial moral decisions to survive.

## ✨ Features

* **Interactive Storytelling:** A narrative-driven experience where the player clicks to advance dialogue and action.
* **Branching Paths:** Choices matter. The player's decisions affect variables (state management) throughout the game.
* **State Management:** The game tracks items (e.g., catching insects) and player interactions to determine the outcome.
* **Multiple Endings:** Based on your choices and quick thinking, you can reach several distinct conclusions:
    * 🏆 **True Ending:** The path of the Omniscient Reader.
    * 🔪 **Psychopath:** Survival at the cost of humanity.
    * 🏃 **Coward:** Hesitation leads to irrelevance.
    * 🤝 **Accomplice:** Forced into a cruel alliance.
    * ✝️ **False Martyr:** A sacrifice that wasn't needed.
    * 👁️ **Big Brother:** The cold observer.

## 🛠️ Tech Stack

* **Language:** XML (Extensible Markup Language)
* **Engine:** Custom Interpreter (Fable/CodeFab)
* **Assets:** Custom PNG images for backgrounds, characters (Dokkaebi, insects), and UI elements.

## 📂 Project Structure

```text
.
├── assets/                  # Images and audio resources
│   ├── dokkaebi_2_.png      # Character sprites
│   ├── metro2.png           # Backgrounds
│   ├── sistema.png          # UI Elements
│   └── ...
├── pages/                   # Story Logic (XML scripts)
│   ├── start.xml            # Main menu
│   ├── middle.xml           # Intro sequence
│   ├── colega.xml           # Character interactions
│   ├── dokkaebi.xml         # The villain appears
│   ├── prova.xml            # The main challenge
│   ├── sagaz.xml            # "Smart" path logic
│   ├── lerdo.xml            # "Slow" path logic
│   └── final-*.xml          # Various ending scripts
└── fable.xml                # Main configuration and variable initialization
```
## 🎮 How to Play
Launch the Interpreter: Run the game through the specific engine provided for the course.

Navigate: Click on the text box or interaction areas to advance the story.

Make Choices: When prompted, select an action (e.g., check phone, talk to colleagues, look for items).

Survive: Try to find the logic behind the "First Scenario" to unlock the True Ending.

## 🧩 Logic Highlights
The game uses logic gates defined in XML to handle the narrative flow:

<fab-if> tags check for specific variable values (e.g., insetos=true) to unlock specific dialogue options or endings.

Variables like mensagem_frase or mensagem_sagaz control the step-by-step progression of scenes.

## 📢 Acknowledgments
Original Story: Omniscient Reader's Viewpoint by Sing Shong.

University: UFMA (Universidade Federal do Maranhão).

Course: Algorithms I.

This is a fan-made educational project.
