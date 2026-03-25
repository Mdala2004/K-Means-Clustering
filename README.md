# K-Means Clustering
## What The Project Does
This project explores the application of K-Means clustering on a dense network topology
consisting of hundreds of interconnected nodes. Each node is assigned spatial coordinates and
an associated energy level, simulating real-world systems such as wireless sensor networks or
IoT environments.

## Objectives
- Apply K-Means clustering using a predefined function (KMeans)
- Analyse a dense network topology (600+ nodes)
- Interpret clustering results using data-driven reasoning
- Visualize data using 2D network graphs and 3D surface plots
- Extract insights from node energy distributions

## Technologies Used
### Language
- Python

### Libraries
- Pandas
- NumPy
- NetworkX
- MatPlotLib
- SciKit Learn

## Project Structure
- A Results folder that includes experiments using different values of k, such as k = 2, k = 5 and k = 7.
- A Python script, kmeans.py, that when executed, shows the different results in 3 seperate graphs.

## How to run the program
### For Windows
1. Open Command Prompt on your desktop
2. Write cd (change directory), then add in the path from where you've saved the work
3. Run the kmeans.py file by using: python kmeans.py
4. The program will run, displaying different graphs according to what you've set as k.

### How to Run (macOS / Linux)
1. Open Terminal
2. Navigate to the project folder:
   cd path/to/project
3. (Optional) Create a virtual environment:
   python3 -m venv venv
4. Activate the virtual environment:
   source venv/bin/activate
5. Install dependencies:
   pip3 install -r requirements.txt
6. Run the program:
   python3 main.py

## Known issues
The program does not accept a k > 7. If this is entered, it may give a KeyError.


