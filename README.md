📂 **File Sorter Python Script**

This script moves .csv, .png, and .txt files into dedicated folders within a specified directory.

Features

🗂 Automatically creates folders for CSV, image, and text files if they don’t exist.

📄 Moves files to the correct folder based on file extension.

🔒 Prevents overwriting by checking if the file already exists in the destination folder.
<br/>
<br/>


**Usage**

1. Set the path variable to the directory you want to organize. (E.g. C:/Users/name/Desktop/Data)
2. Run the script
3. The script will create folders named:
  csv files → for .csv files
  image files → for .png files
  txt files → for .txt files

Files in the directory will be moved to the appropriate folder.
<br/>
<br/>

Requirements

Python 3.x
<br/>
No additional libraries required (uses os and shutil modules).
