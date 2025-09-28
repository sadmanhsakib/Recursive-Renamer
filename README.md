# Super-Renamer
This script, written in Python, mass renames multiple folders as per user request. The user can set what files to rename and what the files should be renamed to. 

<h3>How does it work?</h3>
The user must add the "FOLDER_PATH" to the ".env" file. Upon running the script, it prompts the user for inputs. Then, it makes the changes. The user can also make changes in renaming by manually coding. The script that uses recursion to rename all the files in every subfolder inside "FOLDER_PATH".

<h3>How to use?</h3>
0. Download the dotenv library using "pip install dotenv" in PowerShell or CMD. <br> 
1. Download the GitHub repository.<br>
2. Unzip the repository.<br>
3. Create a ".env" file in the same directory and open it. <br>
4. Write: FOLDER_PATH="". Inside the inverted commas, write the folder's path.<br>
5. Run the script whenever you want to mass rename something.