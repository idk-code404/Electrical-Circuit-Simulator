Electrical Circuit Simulator
An interactive web-based electrical circuit simulator that allows you to build and test circuits with common electronic components. Perfect for learning electronics concepts or prototyping simple circuits.

https://img.shields.io/badge/Status-Active-success https://img.shields.io/badge/License-MIT-blue

Features
🧩 Drag & Drop Components - Easily place components on the canvas

🔌 Realistic Wiring - Connect components with wires for current flow

🎨 Dark/Light Mode - Toggle between themes (dark mode by default)

⚡ Live Simulation - See real-time circuit behavior

🔄 Interactive Components - Rotate, move, and configure components

🎯 Connection Points - Precise wiring with visual connection points

📊 Circuit Analysis - Get detailed simulation results

💡 Visual Feedback - Components light up when powered

Components Available
Battery - Power source (9V default)

Resistor - Current limiting component

Capacitor - Energy storage component

Inductor - Magnetic energy storage

LED - Light emitting diode with color options

Switch - Toggle current flow (open/close)

Quick Start
Clone or download this repository

Open index.html in your web browser

Start building your circuits!

No installation or dependencies required - it's a single HTML file that runs in any modern browser.

How to Use
Building Circuits
Add Components: Drag components from the left panel to the canvas

Connect Components:

Click "Wire Mode"

Click on orange connection points to create wires

Click "Select Mode" when done wiring

Configure Components:

Click on any component to select it

Edit properties in the right panel

Use "Open/Close" buttons for switches

Component Controls
Click: Select component

Drag: Move component

Shift+Click: Rotate component (90° increments)

Double-click: Toggle switch state

Delete: Remove selected component

Simulation
Build your circuit with proper wiring

Click "Simulate Circuit" to analyze

View results in the simulation panel

Components will light up when powered

Example Circuits
Try these simple circuits to get started:

Basic LED Circuit
text
Battery → Resistor → LED
Connect 9V battery to 100Ω resistor

Connect resistor to LED

Connect LED back to battery

Click simulate to light up the LED

Switch-Controlled Circuit
text
Battery → Switch → Resistor → LED
Add a switch between battery and resistor

Close the switch to complete the circuit

Open the switch to break the circuit

Technical Details
Pure HTML - No external dependencies

Canvas-based rendering - Smooth component visualization

Responsive design - Works on desktop and mobile

Dark theme optimized - Easy on the eyes during long sessions

Browser Compatibility
✅ Chrome 60+

✅ Firefox 55+

✅ Safari 12+

✅ Edge 79+

Project Structure
text
circuit-simulator/
├── index.html          # Main application file
├── README.md           # This file
└── (no other dependencies)
Contributing
Contributions are welcome! Here are some ways you can help:

Report Bugs - Open an issue with detailed description

Suggest Features - Share your ideas for improvements

Improve Code - Submit pull requests for bug fixes or enhancements

Documentation - Help improve this README or add tutorials

Development
Since this is a single HTML file, development is straightforward:

Fork the repository

Make your changes to index.html

Test thoroughly in multiple browsers

Submit a pull request

Educational Use
This simulator is excellent for:

Electronics courses - Visualize circuit concepts

STEM education - Introduce students to circuits

Personal learning - Experiment without physical components

Circuit prototyping - Test ideas before building

Related Projects
CircuitJS - More advanced circuit simulator

Falstad Circuit Simulator - Java-based simulator

EveryCircuit - Mobile circuit simulator
Happy Circuit Building! 🚀

Built with ❤️ for the electronics education community
