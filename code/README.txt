
This repository contains all files and code needed to transform legacy data into the format required by template files.
Folder Structure


Instructions to Run
1. Create a Root Folder
Set up a main directory (e.g., code/) on your machine to serve as the root folder.
2. Move Required Folders
Place the following folders inside the root folder:
* code/ (contains the notebook)
* transformed_data/ (will store transformed outputs)
3. Create a data/ Folder
Inside the root folder, create a data/ directory.
Move the supplied folders into it:
* Historic_data/ (containing candidates.presence.latest.csv and Resumes/)
* Templates/ (containing all 4 template Excel files)
4. Run the Notebook
* Navigate to code/ and open code.ipynb
* Restart the kernel and run all cells from the beginning
Notes
* All paths are constructed dynamically to ensure portability.
* Output Excel files will be saved to the transformed_data/ folder using the same filenames as the templates.
* Ensure you have the required packages installed (pandas, openpyxl).




