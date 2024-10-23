# Mail-Merge-Automation-Project
This project automates the process of creating personalized letters by merging a list of invitee names into a template document. The script reads names from a text file, replaces the placeholder in a template letter, and generates individual letters for each invitee, saving them as .docx files in the output folder.

# Project Overview
This Mail Merge Automation project simplifies the process of creating personalized letters. The script reads a list of names, replaces a placeholder ([name]) in a template letter with each individual name, and saves each personalized letter as a .docx file in the output folder.

# File Descriptions
- **main.py:** The Python script that handles reading the names and the template letter, replaces the placeholder with individual names, and generates personalized letters.
- **starting_letter.docx:** The template letter containing the placeholder [name].
- **invited_names.txt:** A text file with a list of names, each on a new line, to be merged into the template letter.
- **Output/ReadyToSend/:** This folder will contain the personalized letters once the script has been run.

# Folder Structure
The project is organized into the following folder structure:
[```
mail-merge/
│
├── Input/
│   ├── Letters/
│   │   └── starting_letter.docx
│   ├── Names/
│   │   └── invited_names.txt
│
├── Output/
│   └── ReadyToSend/
│       └── example.docx
│
├── main.py```]

- **Input:** Contains the template letter and the list of invitee names.
  - Letters/starting_letter.docx: The letter template that contains a placeholder for the names.
  - Names/invited_names.txt: A list of names to be inserted into the letter.
- **Output:** Where the generated letters are saved.
  - ReadyToSend/: The folder where personalized letters are saved with the format letter_for_[name].docx.
  - main.py: The Python script that performs the mail merge process.

# Usage
1. Place the template letter in Input/Letters/starting_letter.docx.
2. Ensure the list of invitee names is in Input/Names/invited_names.txt, with each name on a new line.
3. Run the main.py script to generate personalized letters:
4. After running the script, personalized letters will be saved in the Output/ReadyToSend/ folder with the format letter_for_[name].docx.
