# NodeOfRanvier
Files for measuring node properties 

NodeLengthMeasurement
Code used for measuring nodal length by Arancibia-Carcamo, Ford, Cossell, Ishida, Tohyama & Attwell (2017, eLife).
Written by Lorena Arancibia-Cárcamo, Anna Krasnow, David Attwell.
This code requires the following MATLAB files (available in this repository):
(1)	intersections.m
(2)	nodelengthcalculatorLIVE.m
(3)	nodelength.m
Save the 3 files within the same folder. 
The size of the node is calculated by running the MATLAB (The MathWorks, Inc.) script nodelength.m which measures the distance between the half maximum intensity for each GFP- or antibody labelled paranode.
#Create a Plot Values.csv file in Image J
Open the image in Image J (files with multiple images are allowed but you need to draw a line on the node in each image)
Draw a line crossing both paranodes (the line thickness should be almost as thick as the paranode fluorescence labelling thickness). Along the axis of the axon, the line needs to extend further than the paranodes, thereby incorporating background values on either side of the nodes. 
Plot the intensity profile graph (Analyse/Plot Profile) and save the data (List) as Plot Values.csv to be processed in a new folder.
#Run MATLAB
Open nodelength.m and select Run
A pop up window will appear asking for the directory to analyse
Select the folder in which Plot Values.csv was saved 
A file “noderesults.csv” and accompanying graph (.png) will be generated and automatically saved in the specified directory.

