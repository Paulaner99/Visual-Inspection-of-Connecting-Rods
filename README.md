# Visual Inspection of Motorcycle Connecting Rods 🏍️

In this project we develop a software system aimed at visual inspection of motorcycle connecting rods. The system classifies the rods based on the number of holes (1 or 2) while ignoring distractors. Moreover, for each rod it computes:

-	Position
-	Orientation
-	Length
-	Width 
-	Width at the barycenter
-	And for each hole: position of the centre and diameter size
    
The preprocessing of the image, the analyses of the rods and the related holes have been carried out using standard computer vision methods, such as:

-	Thresholding
-	Morphological operators
-	Filtering
-	Corner detectors
-	Blob analyses
-	Bounding boxes
-	Etc.

The entire process, from the raw image to the final report of the rods, is detailed in the **rods.ipynb** notebook.

![Analyses of Motorcycle Connecting Rods](/resources/rod-analyses.png)
