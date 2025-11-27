# Slope-Curves---Jupyter-Notebook
This repository contains a Jupyter Notebook, which is freely available. The notebook is intended for researchers interested in investigating non-adiabatic AC calorimetry data for instrument issues and non-linear heat losses.
The notebook is created such that it should be possible for users without programming experience to use the notebook to perform analysis on their own AC calorimetric data. 

In the text below, it is described how to download and install everything needed to run the Jupyter Notebook. It is also described how JupyterLab is opened and how to run the script once the installations are completed. 

To understand the need for slope curve analysis and how to understand such plots, see these articles: 
* [The Impact of Sample Insulation on Estimating the Heating Power of Magnetic Nanoparticles by AC Calorimetry](http://dx.doi.org/10.1109/LMAG.2023.3279778)
* [Link to article pending](TODO!!!)

# Download and install Python and JupyterLab
To run the script, you need to install both Python (the programming language used in the script) and JupyterLab (the graphical user interface where you will run and edit the script). 

The following videos can be used to help you install both Python and JupyterLab:  
* **Windows**:  [https://www.youtube.com/watch?v=LQ47rIO5bTw](https://www.youtube.com/watch?v=LQ47rIO5bTw).  
* **MacOS**: [https://www.youtube.com/watch?v=z7zOkRubIrU](https://www.youtube.com/watch?v=z7zOkRubIrU). This video is for installing Jupyter notebook, which would also work fine. However, I would recommend JupyterLab. Thus, whenever you are asked to type something with `... notebook` in your terminal, instead type `... jupyterlab` ( e.g., when asked to type `pip3 install notebook`, instead type `pip install jupyterlab`). 

Additionally, the steps are described below.  
1. Download the Python installer:  
   Go to the official Python homepage: [https://www.python.org/downloads/](https://www.python.org/downloads/).  
   Download the newest version of Python.  
3. Run the Python installer that you have downloaded. Choose to add python.exe to PATH when asked by the installer.  
4. Confirm correct installation:  
   Open the terminal and type `python`.  
   Hereafter, you should get an output similar to the text shown below
   <img width="1460" height="115" alt="image" src="https://github.com/user-attachments/assets/b74b2335-0166-4177-8e73-3743a5dcc493" />
   Close the terminal.
6. Install JupyterLab.  
   Open the terminal again.  
   Windows: type `python -m pip install jupyterlab`     
   MacOS: `pip install jupyterlab`  
   `pip` is a program used to install Python packages.  
   After the installation has finished, close the terminal.  
7. Open JupyterLab:  
   Open the terminal again.  
   Windows: type `python -m jupyter lab`  
   MacOS: type `jupyter lab`  
   Wait for the program to open in a browser window.
8. Success, you have installed both Python and Jupyter :sunglasses:

# Install widget package (Optional):  
The plots in JupyterLab can be made interactive so you can zoom into selected regions. I personally find this very useful, and thus I recommend following this optional step. 
1. Close the JupyterLab tab in your browser.
2. Close the terminal.
3. Open a new terminal and type:  
   Windows: `python -m pip install ipympl`  
   MacOS: `pip install ipympl`  
   Wait for the installation to finish.  
   If you want more information on the ipympl package, visit [https://matplotlib.org/ipympl/](https://matplotlib.org/ipympl/).  
   

# Download and open the Slope-curves repository in JupyterLab:  
To download the Slope curves repository, go to [https://github.com/LiseHanson/Slope-Curves---Jupyter-Notebook](https://github.com/LiseHanson/Slope-Curves---Jupyter-Notebook) and click *<>code -> Download ZIP* as shown below. 
<p align="center">
<img style="width:85%; height:auto;" alt="image" src="https://github.com/user-attachments/assets/e26cf826-e5c8-4c46-a49c-ade4e36c7ccc" />
</p>



1. Extract the downloaded zip folder.  
2. Open JupyterLab from the terminal (Windows: type `python -m jupyter lab` or in macOS: type `jupyter lab`).  
3. In JupyterLab, navigate to the extracted folder in the menu on the left. When you have found the correct folder, it should look similar to what is seen below
   <img width="1923" height="1167" alt="image" src="https://github.com/user-attachments/assets/40df1e4b-9a6b-4340-9df6-513257fd47aa" />
4. Double-click on the file *"Slope Curves.ipynb"* (marked with yellow above). 
5. Your browser window should now look similar to the image below. To run a single cell, click on :arrow_forward: as marked with yellow. To run the entire script, click on :fast_forward: as marked with orange. 
   <img width="2278" height="1146" alt="image" src="https://github.com/user-attachments/assets/0435d590-98e7-4e0d-9b13-9513485529fd" />

# Run and edit the script: 
Congratulations, you are now ready to run and edit the script. All the instructions on running and adapting the script are given inside *"Slope Curves.ipynb"*, and thus, from here you will continue with the instructions seen in JupyterLab.  
- Good luck :partying_face:
