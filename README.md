# PyKnight ![Python](https://img.shields.io/badge/python-3.13-blue) ![Pygame](https://img.shields.io/badge/pygame-2.6.1-blue)

![PyKnight](assets/brand/logo256.png)

A complete & customizable **chess game**, written from scratch in Python; including legal move validation, game-state management, save & load functionality, and a clean Pygame GUI with interactive controls. 

This project focuses on designing & implementing a complete chess engine - without using external chess libraries.

![PyKnight](assets/images/image1.png)

## ✔️ Features

### 🎮 Game UI
- Two boards (both perspectives) 
- Clean Pygame UI with interactive controls
- Multiple piece sets
- Multiple board palettes

### ⚙️ Engine
- Legal move validation for all pieces
- Check, checkmate, stalemate
- Pawn promotion
- Castling
- En passant
- Undoing moves
- Save & load functionality

## 🛠️ Built With
- `Python 3.13`
- `Pygame 2.6.1`

## How to Run
1. Click **Code → Download ZIP** on this repository.
2. Extract the ZIP file to a folder.
3. Open the folder and run `main.py`.

## How to Run (Alternative)
1. Clone the repository: `git clone https://github.com/Leshiro/py-knight`
2. Navigate into the project folder: `cd py-knight`
3. Run the game: `python main.py`

## 📁 Project Structure
```
py-knight/
├── assets/      # Images & audio files
├── data/        # Save data
├── engine/      # Game engine
├── ui/          # Pygame UI
├── main.py      # Launcher
└── main.pyw     # Launcher without terminal (Windows only)
```
