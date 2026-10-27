Step 1: Open Your Terminal
Mac: Press Cmd + Space, type Terminal, and hit Enter.

Windows: Press the Windows key, type PowerShell or Command Prompt, and open it.

Step 2: Create the Project Folder Structure
Run the following commands one by one to create your main folder, subfolders, and HTML files.

For macOS / Linux / Git Bash:
Bash
# 1. Create and navigate into the main project folder
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1 week-2 week-3

# 3. Create an index.html file inside each week folder
touch week-1/index.html week-2/index.html week-3/index.html
For Windows PowerShell:
PowerShell
# 1. Create and navigate into the main project folder
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each week folder
New-Item week-1/index.html
New-Item week-2/index.html
New-Item week-3/index.html
Step 3: Practice Terminal Navigation, Renaming, and Deleting
To satisfy requirement #5, practice these essential commands:

Check where you are (Print Working Directory):

Bash
pwd  # (Mac/Linux/PowerShell)
List files and folders:

Bash
ls   # (Mac/Linux/PowerShell)
Navigate between folders:

Bash
cd week-1    # Go into week-1
cd ..        # Go back up one level to web-development-practice
Rename a folder or file:

Mac/Linux: mv week-3 week-three

Windows PowerShell: Rename-Item week-3 week-three

Delete a file or folder:

Mac/Linux: rm week-three/index.html or rm -rf week-three

Windows PowerShell: Remove-Item week-three/index.html or Remove-Item -Recurse -Force week-three

(Note: Re-create week-3 or rename it back if you deleted it for your final structure!)

Step 4: Open the Project in VS Code from the Terminal
Make sure you are inside the web-development-practice folder in your terminal, then run:

Bash
code .
This command instantly launches Visual Studio Code with your entire project folder open.

Submission Checklist
Record of Terminal Commands: Copy and save the history of commands you typed during this session.

Screenshot: Take a screenshot of your terminal showing the commands being run, or a screenshot of your VS Code Explorer sidebar showing the web-development-practice folder containing week-1, week-2, and week-3 (each with an index.html file