# Automatic File Sorter in File Explorer

## Description

The Automatic File Sorter is a Python-based project that automatically organizes files in a folder into separate categories based on their file extensions.

It helps keep the File Explorer organized by moving files into appropriate folders such as Excel files, image files, and document files.

## Features

- Automatically identifies files based on their extensions.
- Creates required folders automatically.
- Moves Excel files into the `excel files` folder.
- Moves images into the `image files` folder.
- Moves documents into the `document files` folder.
- Can be configured to run continuously at regular intervals.

## File Types Supported

### Excel Files
- `.xlsx`
- `.xls`

### Image Files
- `.jpg`
- `.png`
- `.jpeg`

### Document Files
- `.pdf`
- `.docx`
- `.pptx`
- `.txt`

## Technologies Used

- Python
- OS module
- Shutil module
- Time module

## How It Works

1. The program checks the selected folder.
2. It identifies files based on their extensions.
3. Required category folders are created if they don't already exist.
4. Files are moved to their respective folders automatically.
5. The program can be configured to repeat the process at regular intervals.

## Example

Before running the program:

```text
My Folder
│
├── report.xlsx
├── photo.jpg
├── resume.pdf
└── notes.txt
