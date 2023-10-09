# Using-MatPlotLib

This project provides a simple tool to visualize the famous Iris dataset. It allows users to plot any two features against each other and visually differentiate between the three types of irises: setosa, versicolor, and virginica.

## Usage

Run the program in a Python environment:

```
python iris_plotter.py
```

Upon execution, the program will prompt you to enter the file name containing the Iris dataset. Afterward, you can choose any two features to plot against each other. The program will continue to prompt for new plots until you decide to stop.

## Data Format

The expected data file format is space-separated with the following columns:

1. Sepal length
2. Sepal width
3. Petal length
4. Petal width
5. Iris type (setosa, versicolor, or virginica)

Example:

```
5.1 3.5 1.4 0.2 setosa
```

## Functions

- `plot_points(file_name, feature_x, feature_y)`: This function takes in a filename and the indices for the x and y features to be plotted. It reads the data file, segregates the data by the Iris type, and plots the chosen features.

The main execution loop prompts users for their desired features to plot and uses the above function to visualize the data.

## Note

Ensure that the data file is present in the same directory as the script or provide the full path to the data file.
