<img src="logo2.png" alt="Eco" width="400"/>

Please reach out to john.docter@colorado.edu with any questions 

Introduction
============
EcoGenoRisk is a risk assessment software for managing synthetic biology in the environment

GUI_Package is the software for running analyses on your local machine. 

High level and custom analyses can be done using the full code, located in the EcoDr repository, Eco_V2 branch. 

Instructions
============
1. Download or git pull GUI_Package from the repository. 
2. Ensure all python libraries and packages in EcoGenoRisk.py (Main script) and Functions.py (Custom functions) are installed
3. Navigate to working directory, or where GUI_Package is downloaded
4. In the terminal, run 'streamlit run EcoGenoRisk.py'
5. A webpage should open and the program should be running. 
6. Follow all prompts to output a threat assessment. 

Useful Tips
===========
"EC_List_For-Parsing.txt" needs to stay where it is relative to the main script. 

"Post Processing Scripts" are for going outside the bounds of the GUI. There are scripts for cleaning data downloaded from JGI (for custom analyses) as well as analyzing the data that comes out of the program and visualizing it. The program will run fine without these, they are there as a "might be useful". 
