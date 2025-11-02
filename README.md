🗂️ File Organizer Project

📖 Overview
The File Organizer Project is a Python-based automation tool that helps users organize the files in a given folder path. 
It automatically sorts files into categorized folders (like Images, Documents, Videos, etc.) based on their file types — keeping your workspace clean and clutter-free.
This project is built using Python in Jupyter Notebook and is designed for beginners and tech enthusiasts who want to automate their daily file management tasks.

🚀 Features
Automatic Sorting: Organizes files into subfolders based on their extensions (.png, .jpg, .pdf, .mp4, etc.). 
User Input Friendly: Accepts any folder path directly from the user. 
Custom Folder Creation: Automatically creates categorized folders (Images, Documents, Audio, etc.) if they don’t exist. 
Error Handling: Skips invalid or inaccessible files safely. 
Beginner Friendly: Simple logic and easy to understand code written in Python.

⚙️ Technologies Used 
Python 3 
Jupyter Notebook 
OS Module 
Shutil Module

🧠 How It Works 
1.The user provides the folder path. 
2.The script scans all files within that folder. 
3.It identifies the file type based on its extension. 
4.It automatically moves each file into a corresponding category folder such as:
  📸 Images → .png, .jpg, .jpeg 
  📄 Documents → .pdf, .docx, .txt 
  🎵 Audio → .mp3, .wav 
  🎬 Videos → .mp4, .mkv 
  📦 Others → Any uncategorized files

🧩 Example

If your folder contains these files:

photo1.png
report.pdf
song.mp3
video.mp4
notes.txt
After running the script, it will automatically create folders and organize them like this:

Images/photo1.png
Documents/report.pdf
Audio/song.mp3
Videos/video.mp4
Documents/notes.txt

🪄 Future Improvements 
1.Add a simple GUI (Graphical Interface) for easier folder selection 
2.Include progress bar and summary report after organizing 
3.Add support for cloud storage paths (Google Drive, Dropbox, etc.)

💬 Author 
Developed by Manu Chauhan — a data science aspirant with an interest in Python automation and real-world problem solving.
