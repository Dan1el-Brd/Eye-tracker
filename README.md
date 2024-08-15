

# Webcam Disruption Tracker
Automated eye-tracker app, helping track your productivity


## Overview

This project is a Python script that helps monitor focus during work or study sessions by tracking disturbances through webcam analysis. The script automates a website that accesses the webcam, tracks eye movements, collects data, and visualizes concentration levels.

## Features

- **Web Automation**
  - Automates the process of opening [Webcam Test website](https://webcamtests.com/check) and starting a webcam session using Selenium.
  
- **Eye Tracking**
  - Uses OpenCV to detect the user's eyes and monitor whether they are focused on the screen.
  
- **Data Logging**
  - Records instances of disturbances (when the user is not looking at the monitor) in a CSV file or database.
  
- **Data Analysis & Visualization**
  - Analyzes the logged data to calculate focus metrics.
  - Generates graphs to visualize disruptions and concentration levels using Matplotlib or Plotly.

## Tech Stack

- **Python**: Core scripting language.
- **Selenium**: For automating the browser interactions.
- **OpenCV**: For real-time eye detection and tracking.
- **Matplotlib/Plotly**: For data visualization and graph generation.
- **CSV/Database**: For data storage and logging.

## Installation

1. git clone https://github.com/yourusername/webcam-disruption-tracker.git
   cd webcam-disruption-tracker

2. python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. pip install -r requirements.txt

4. python tracker.py
