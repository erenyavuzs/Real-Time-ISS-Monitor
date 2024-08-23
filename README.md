# Real Time ISS Monitor

This project provides a real-time visualization of the International Space Station's (ISS) position using Python's turtle graphics module. In addition to displaying the current location of the ISS on a world map, the project also fetches and shows information about the astronauts currently aboard the station. The ISS's path is dynamically visualized as a line on the screen, continuously updating every 5 seconds, offering an engaging way to track the station's journey around the Earth.

<img width="1274" alt="Screenshot" src="https://github.com/user-attachments/assets/537edca5-13a1-44ec-bb68-6c5e7da8f603">

## Features

- **Astronauts Information**: Fetches and displays the names and crafts of the astronauts currently on the ISS.
- **Real-Time ISS Tracking**: Displays the real-time position of the ISS on a world map using the turtle graphics module.
- **ISS Path Visualization**: Shows the path of the ISS as a line on the screen, updating in real-time.
- **Automatic Updates**: Continuously updates the ISS position every 5 seconds.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/erenyavuzs/Real-Time-ISS-Monitor.git
    cd real-time-iss-monitor
    ```

2. **Install the required Python packages**:
    You can install all the necessary libraries by running:
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare the environment**:
   - Ensure that you have the required images in the `images/` directory:
     - `world-map.gif`: A world map background image.
     - `iss-icon.gif`: An icon representing the ISS.

## Usage

Run the main script to start tracking the ISS and retrieving astronauts' information:
```bash
python main.py
