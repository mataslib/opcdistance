# OPC Distance Calculator

## Overview
The OPC Distance Calculator is a web application that allows users to calculate the distance traveled based on GPS coordinates provided in a CSV format. The application visualizes the route on a map using Leaflet and provides an interactive interface for users to manipulate the data.

## Features
- Upload or drag-and-drop CSV files containing GPS coordinates.
- Calculate the total distance traveled based on the provided coordinates.
- Visualize the route on an interactive map.
- Remove the first or last row of the CSV input for easy data manipulation.

## Project Structure
```
opcdistance
├── index.html         # Main HTML document for the application
├── assets
│   ├── css
│   │   └── styles.css # CSS styles for the application
│   └── js
│       └── script.js  # JavaScript code for interactivity and functionality
├── .gitignore         # Specifies files and directories to be ignored by Git
└── README.md          # Documentation for the project
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/opcdistance.git
   ```
2. Navigate to the project directory:
   ```
   cd opcdistance
   ```
3. Open `index.html` in your web browser to view the application.

## Usage
- Paste or drag-and-drop a CSV file containing GPS coordinates into the designated input area.
- Use the buttons to remove the first or last row of the input if needed.
- Click the "Calculate Distance" button to compute the total distance traveled and visualize the route on the map.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.