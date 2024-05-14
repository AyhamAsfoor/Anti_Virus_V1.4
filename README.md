# Anti Virus
## Overview
This project is a robust antivirus software implemented in Python. It leverages YARA rules to detect malicious files within the system and provides options to quarantine, delete, or move them to a specified folder.

## What is this project?
This project is a comprehensive antivirus tool designed to scan directories, files, and drives for potential threats using YARA signatures. It offers essential functionalities such as quarantine and deletion of identified malicious files, all through a simple command-line interface.

## Key Features
- YARA Rule-Based Scanning: Utilizes custom YARA rules to identify malicious files based on defined signatures.
- Quarantine Functionality: Moves detected threats to a designated quarantine folder for further analysis or removal.
- Command-Line Interface: Provides an intuitive CLI for users to initiate scans and manage detected threats.
- Periodic Scanning: Supports automated periodic scans based on user-configurable settings.
  
## How to Use
### 1) Installation:
- Ensure Python is installed on your computer.
- Install required dependencies using <sup> pip install -r requirements.txt. </sup>

### 2) Execution:
Follow the command-line prompts to select scanning options and directories.

### 3) Configuration:
Customize periodic scan settings by modifying variables in the main script.
## Dependencies
- YARA: For malware signature detection in files.
- colorama: For adding colors to the command-line interface.
- progressbar: For displaying progress bars during the scanning process.
- PyFiglet: For rendering stylized text in large fonts.
## Credits
- YARA: Malware detection engine using custom rules.
- colorama: Library for terminal text coloring.
- progressbar: Tool for displaying progress bars in the console.
- PyFiglet: Library for generating ASCII art text.
## License
This project is distributed under Apache 2.0. Feel free to use and modify it according to your needs.
