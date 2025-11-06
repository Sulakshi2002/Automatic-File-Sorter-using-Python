# Automatic-File-Sorter-using-Python
📖 Overview

This Python project automatically organizes files in a folder based on their file types — without needing to drag and drop manually.
It sorts files like .pdf, .png, .xlsx, and .webp into their specific folders automatically.

⚙️ How It Works

The program looks inside a specific folder (you can set your own path).

It checks for common file types — Excel, Images, PDFs, and WebP files.

If folders for those types don’t exist, it creates them.

Then it moves each file into the right folder automatically.

📁 Example Folder Structure

Before running:

ex folder for automatic file sorter/
│
├── bow.webp
├── ICT22952_Lab01_CS.pdf
├── ICT22952_Magazine innerpages.png
├── report.xlsx


After running:

ex folder for automatic file sorter/
│
├── excel files/
│   └── report.xlsx
│
├── image files/
│   └── ICT22952_Magazine innerpages.png
│
├── pdf files/
│   └── ICT22952_Lab01_CS.pdf
│
├── webp files/
│   └── bow.webp

🧠 Requirements

Python 3.x

Modules:

import os
import shutil


These modules come pre-installed with Python — no extra setup needed.

🚀 How to Use

Copy the project code into a Python file (e.g., file_sorter.py).

Change the folder path in the script:

path = r"C:/Users/HP/Desktop/Projects/Python/ex folder for automatic file sorter/"


Run the script:

python file_sorter.py


Done! Your files will be sorted automatically.

🧩 Supported File Types

.xlsx → Excel files

.png → Image files

.pdf → PDF files

.webp → WebP files

✨ Features

✅ Automatically creates folders if they don’t exist
✅ Moves files into the right folders
✅ Simple and easy to customize
✅ No need for manual sorting
