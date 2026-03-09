# Virtual-Drawing-Board-
Air Canvas An Virtual Drawing Board is Interactive Digital art Project which can draw in Air by capturing hand motion from camera Captures hand gestures using a camera, allowing you to draw on the canvas simply by waving your fingertip in the air


## Overview

This repository contains a Virtual Drawing Board project that allows users to draw on a digital canvas using a variety of tools and colors. The application is built using Python and OpenCV, providing an intuitive interface for freehand drawing.

## Features

- **Freehand Drawing**: Use the mouse or a drawing tablet to draw on the canvas.
- **Color Selection**: Choose from a palette of colors to customize your drawings.
- **Drawing Tools**: Select different tools such as pens, brushes, and erasers.
- **Undo/Redo**: Easily undo or redo your actions to correct mistakes.
- **Save Artwork**: Save your drawings as image files.

## Getting Started

### Prerequisites

- Python 3.x
- A webcam

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/vippagowthami/Virtual-Drawing-Board.git
    cd Virtual-Drawing-Board
    ```

2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. **Run the Application**:
    ```sh
    python Ai_virtual_painter.py
    ```

2. **Using the Drawing Board**:
    - **Selection Mode**: Hold up your **index and middle fingers** together to enter selection mode.
    - **Drawing Mode**: Hold up only your **index finger** to draw on the canvas.
    - **Color Selection**: In selection mode, move your index finger into the toolbar at the top of the screen to pick a color (Purple, Blue, or Green).
    - **Eraser**: Select the **ERASER** tool from the toolbar in the same way.
    - **Clear Canvas**: In selection mode, move your hand over the **CLEAR** button (top-left) to wipe the canvas.

## Folder Structure

- `Ai_virtual_painter.py`: Main script to run the virtual drawing board.
- `HandTrackingModule.py`: Helper module for hand detection and landmark tracking.
- `Header/`: Toolbar images displayed at the top of the drawing window.
- `requirements.txt`: List of Python dependencies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

