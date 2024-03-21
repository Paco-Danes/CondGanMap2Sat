# CondGanMap2Sat
Repository for Neural Network project 2023/2024, Ai &amp; Robotics, double Conditional PatchGan for map to satellite view generation.
Student: Francesco Danese, 1926188.
The repository contains 3 files:
* CompleteWorkflow.ipynb : please open this with Google Colab since it is formatted in a way that the cells are grouped in sections with titles for a better code organization and a quicker review. This is basically the whole project work, including: data processing (loading, visualization, augmentation), models architecture, training pipelines, evaluations etc etc. Almost all cells eventual output was mantained and it's still visible. You can press: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Paco-Danes/CondGanMap2Sat/blob/main/CompleteWorkflow.ipynb) 
* NNN_project.pdf: This is a short but complete description of the methods and implementations employed in the project. Test results are presented, along with some real examples of the various models' capabilities and generated images.
* TryOut.ipynb: a small notebook where, if you wish, you can try and test the models yourself by the help of the functions provided, by making new random generations using the OpenStreetMap images of the 2 test datasets.

Set-up instructions for running "TryOut.ipynb", since the models were to big (370MB) to load on GitHub:
1. Gain access to this public shared GoogleDrive folder by simply clicking [THIS LINK](https://drive.google.com/drive/folders/1BA7XhZTy5cUg-Tcs4KP3Ay52F6F4Ewju?usp=drive_link). You will find 4 models (.pth) and 2 datasets (.zip).
2. Select all of them and "right-click -> create a copy".
3. Rename the copies as you wish without any blank space in the name and move all of them into your local drive with "right-click -> Organize -> Move" (That is, in your "MyDrive", outside the shared folder)
4. Open TryOut.ipynb with google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Paco-Danes/CondGanMap2Sat/blob/main/TryOut.ipynb) and mount your local drive by running the first cell (or manually through the UI)
5. Replace all the placeholder paths in the 3 commented cells (you can find them easily) with your actual paths of your models and test sets. You can find your file paths by navigating in the file system on the left side, locating your files and "right-click -> copy path". Please be careful to insert the correct path in the corresponding variable.
6. Finally run all the cell in order. Now you can repeatedly use the last two cells to generate new images and see the results and model comparisons from both datasets.

If you decided to try the models but you have encountered any trouble following the instructions, feel free to contact me.




