# Research Conceptual Model Builder

A web-based tool for creating and visualizing research conceptual models with variable relationships.

## Overview

The Research Conceptual Model Builder helps researchers, students, and academics create visual representations of research models. It allows you to:

- Add different types of variables (independent, dependent, moderator/mediator, control)
- Create connections between variables
- Adjust moderator strength (including mediator functionality)
- Save, load, and export your models

## Table of Contents

- [Research Conceptual Model Builder](#research-conceptual-model-builder)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Adding Variables](#adding-variables)
  - [Moderator Strength \& Mediators](#moderator-strength--mediators)
  - [Creating Connections](#creating-connections)
  - [Managing Your Model](#managing-your-model)
    - [Saving Your Model](#saving-your-model)
    - [Loading a Model](#loading-a-model)
    - [Exporting as Image](#exporting-as-image)
    - [Clearing the Canvas](#clearing-the-canvas)
  - [Additional Features](#additional-features)
    - [Variable Manipulation](#variable-manipulation)
    - [Canvas Navigation](#canvas-navigation)
    - [Trash Zone](#trash-zone)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Troubleshooting](#troubleshooting)
  - [Technical Details](#technical-details)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)
  - [Overview](#overview-1)
  - [Table of Contents](#table-of-contents-1)
  - [Getting Started](#getting-started-1)
  - [Adding Variables](#adding-variables-1)
  - [Moderator Strength \& Mediators](#moderator-strength--mediators-1)
  - [Creating Connections](#creating-connections-1)
  - [Managing Your Model](#managing-your-model-1)
    - [Saving Your Model](#saving-your-model-1)
    - [Loading a Model](#loading-a-model-1)
    - [Exporting as Image](#exporting-as-image-1)
    - [Clearing the Canvas](#clearing-the-canvas-1)
  - [Additional Features](#additional-features-1)
    - [Variable Manipulation](#variable-manipulation-1)
    - [Canvas Navigation](#canvas-navigation-1)
    - [Trash Zone](#trash-zone-1)
  - [Keyboard Shortcuts](#keyboard-shortcuts-1)
  - [Troubleshooting](#troubleshooting-1)
  - [Technical Details](#technical-details-1)
  - [License](#license-1)
  - [Acknowledgements](#acknowledgements-1)

## Getting Started

1. Access the tool through your web browser
2. The canvas area is where your model will be built
3. Use the toolbar at the top to add variables
4. Use the connection mode to create relationships between variables

## Adding Variables

1. Enter a variable name in the "Variable Name" field
2. Select a variable type from the dropdown:
   - **Independent Variable**: Typically manipulated or controlled in a study
   - **Dependent Variable**: The outcome being measured
   - **Moderator**: A variable that affects the strength of relationship between other variables
   - **Control**: Variables held constant to avoid confounding effects
   - **Custom**: User-defined variable type with custom color

3. For moderator variables, use the strength slider to set its influence (0-100)
4. Click the "Add" button to place the variable on the canvas
5. Drag variables to position them in your model

## Moderator Strength & Mediators

This tool combines moderators and mediators into a single variable type with adjustable strength:

- **Moderator (strength > 0)**: A variable that influences the relationship between independent and dependent variables
- **Mediator (strength = 0)**: A variable that explains the relationship between independent and dependent variables

To adjust a moderator's strength:
- **Double-click** on any moderator variable to open the strength editor
- **Right-click** on any moderator variable to open the strength editor
- Set the slider to 0 to make it function as a mediator (it will appear with reduced opacity)
- Set the slider to values 1-100 to make it function as a moderator

## Creating Connections

1. Click the connection mode button (↔️) in the bottom right
2. Click on the first variable you want to connect
3. Click on the second variable to create the connection
4. The arrow will point from the first selected variable to the second
5. Double-click on any connection line to remove it
6. Click the connection mode button again to exit connection mode

## Managing Your Model

### Saving Your Model
1. Click the "Save Model" button
2. The model will be saved as a JSON file to your computer
3. This file contains all variable information, positions, and connections

### Loading a Model
1. Click the "Load Model" button
2. Select a previously saved JSON model file
3. Your model will be restored with all variables and connections

### Exporting as Image
1. Click the "Export as PNG" button
2. A PNG image of your current model will be downloaded

### Clearing the Canvas
1. Click the "Clear Canvas" button to remove all variables and connections
2. This action cannot be undone

## Additional Features

### Variable Manipulation
- **Drag**: Click and hold to move variables around the canvas
- **Double-click**: Minimize a variable or adjust moderator strength
- **Right-click** on moderators: Adjust moderator strength
- **Delete**: Click the × on any variable to remove it and its connections

### Canvas Navigation
- Use the zoom controls (+ and -) in the bottom left of the canvas
- Reset zoom with the reset button

### Trash Zone
- Drag any variable to the bottom of the screen to delete it
- The trash zone appears when dragging a variable

## Keyboard Shortcuts

- **Escape**: Exit connection mode
- **Delete/Backspace**: Delete selected variable (when clicked)
- **Ctrl/Cmd + S**: Save model
- **Ctrl/Cmd + O**: Open model loader

## Troubleshooting

**Issue**: Variables can't be connected
- **Solution**: Make sure connection mode is active (red button in bottom right)

**Issue**: Can't adjust moderator strength
- **Solution**: Double-click or right-click directly on a moderator variable

**Issue**: Connections aren't showing properly
- **Solution**: Try refreshing the page or adjusting the zoom level

---

## Technical Details

This tool runs entirely in the browser and doesn't require a server to function. Data is stored locally in your browser and on your computer when you save.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

Developed by [Your Name/Organization]# Research Conceptual Model Builder

A web-based tool for creating and visualizing research conceptual models with variable relationships.

## Overview

The Research Conceptual Model Builder helps researchers, students, and academics create visual representations of research models. It allows you to:

- Add different types of variables (independent, dependent, moderator/mediator, control)
- Create connections between variables
- Adjust moderator strength (including mediator functionality)
- Save, load, and export your models

## Table of Contents

- [Getting Started](#getting-started)
- [Adding Variables](#adding-variables)
- [Moderator Strength & Mediators](#moderator-strength--mediators)
- [Creating Connections](#creating-connections)
- [Managing Your Model](#managing-your-model)
- [Additional Features](#additional-features)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Troubleshooting](#troubleshooting)

## Getting Started

1. Access the tool through your web browser
2. The canvas area is where your model will be built
3. Use the toolbar at the top to add variables
4. Use the connection mode to create relationships between variables

## Adding Variables

1. Enter a variable name in the "Variable Name" field
2. Select a variable type from the dropdown:
   - **Independent Variable**: Typically manipulated or controlled in a study
   - **Dependent Variable**: The outcome being measured
   - **Moderator**: A variable that affects the strength of relationship between other variables
   - **Control**: Variables held constant to avoid confounding effects
   - **Custom**: User-defined variable type with custom color

3. For moderator variables, use the strength slider to set its influence (0-100)
4. Click the "Add" button to place the variable on the canvas
5. Drag variables to position them in your model

## Moderator Strength & Mediators

This tool combines moderators and mediators into a single variable type with adjustable strength:

- **Moderator (strength > 0)**: A variable that influences the relationship between independent and dependent variables
- **Mediator (strength = 0)**: A variable that explains the relationship between independent and dependent variables

To adjust a moderator's strength:
- **Double-click** on any moderator variable to open the strength editor
- **Right-click** on any moderator variable to open the strength editor
- Set the slider to 0 to make it function as a mediator (it will appear with reduced opacity)
- Set the slider to values 1-100 to make it function as a moderator

## Creating Connections

1. Click the connection mode button (↔️) in the bottom right
2. Click on the first variable you want to connect
3. Click on the second variable to create the connection
4. The arrow will point from the first selected variable to the second
5. Double-click on any connection line to remove it
6. Click the connection mode button again to exit connection mode

## Managing Your Model

### Saving Your Model
1. Click the "Save Model" button
2. The model will be saved as a JSON file to your computer
3. This file contains all variable information, positions, and connections

### Loading a Model
1. Click the "Load Model" button
2. Select a previously saved JSON model file
3. Your model will be restored with all variables and connections

### Exporting as Image
1. Click the "Export as PNG" button
2. A PNG image of your current model will be downloaded

### Clearing the Canvas
1. Click the "Clear Canvas" button to remove all variables and connections
2. This action cannot be undone

## Additional Features

### Variable Manipulation
- **Drag**: Click and hold to move variables around the canvas
- **Double-click**: Minimize a variable or adjust moderator strength
- **Right-click** on moderators: Adjust moderator strength
- **Delete**: Click the × on any variable to remove it and its connections

### Canvas Navigation
- Use the zoom controls (+ and -) in the bottom left of the canvas
- Reset zoom with the reset button

### Trash Zone
- Drag any variable to the bottom of the screen to delete it
- The trash zone appears when dragging a variable

## Keyboard Shortcuts

- **Escape**: Exit connection mode
- **Delete/Backspace**: Delete selected variable (when clicked)
- **Ctrl/Cmd + S**: Save model
- **Ctrl/Cmd + O**: Open model loader

## Troubleshooting

**Issue**: Variables can't be connected
- **Solution**: Make sure connection mode is active (red button in bottom right)

**Issue**: Can't adjust moderator strength
- **Solution**: Double-click or right-click directly on a moderator variable

**Issue**: Connections aren't showing properly
- **Solution**: Try refreshing the page or adjusting the zoom level

---

## Technical Details

This tool runs entirely in the browser and doesn't require a server to function. Data is stored locally in your browser and on your computer when you save.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

Developed by [Your Name/Organization]