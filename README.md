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
- Install required dependencies using ```pip install -r requirements.txt ``` 

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

## Cloning the Repository
To clone this repository and run the antivirus software locally, follow these steps:
1. Open a terminal or command prompt on your computer.
2. Navigate to the directory where you want to clone the repository.
3. Use the following command to clone the repository:

```py
git clone https://github.com/AyhamAsfoor/Anti_Virus_V1.4
```

Once the repository is cloned, navigate into the project directory:
```
cd <repalce_your_project_directory>
```
> [!TIP]
> Follow the instructions in the How to Use section of the README to install dependencies and execute the antivirus software.
> [!IMPORTANT]
> If you have any issues, please don't be shy to get in touch with me.
## License
This project is licensed under the Apache License 2.0.
You can find the full text of the license in the LICENSE file.
