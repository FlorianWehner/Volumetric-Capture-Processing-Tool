# Volumetric-Capture-Processing-Tool
The Volumetric Capture Processing Tool is a Python script with a graphical user interface (GUI) built using PySide6 and QT Designer. 
This script facilitates the management and execution of a photogrammetry pipeline using Metashape, helping to automate the processing of hundreds of frames for a volumetric capture datasets.


## Features

- **GUI Interface**: Utilizes PySide6 to create an interactive GUI for user input and status monitoring.
- **Project Folder Creation**: Automatically creates a structured project folder hierarchy.
- **XML Management**: Copies and modifies XML configuration files for project-specific settings.
- **Job-specific Processing**: Generates job-specific JSON files and triggers the Metashape processing.

## Demo Video
To watch a video demo of the project, click here:

[![Video Demo](https://img.youtube.com/vi/DkoWkKtu9sE/0.jpg)](https://youtu.be/DkoWkKtu9sE)





## Requirements

- Python 3.11+
- PySide6
- Metashape (to be installed separately)
- Supported on Windows (additional adjustments required for other platforms)

## Installation

1. Ensure you have Python 3.11 or above installed.
2. Install required Python packages:
import os, shutil, sys, re, json, subprocess
from PySide6.QtCore import QProcess, QObject, Signal  
from PySide6.QtWidgets import QApplication, QMainWindow
from Vocap_GUI import Ui_MainWindow

## Usage

run the script

python main.py

The GUI will appear, allowing you to input project details and configure processing settings.

Click the "Start VOCAP" button to initiate the automated photogrammetry processing pipeline.
