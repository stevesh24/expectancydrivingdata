# expectancydrivingdata

This data set gives the raw data to create expectancy heat maps of driving targets in driving images.  In an online study, 172 observers viewed 150 greyscale images of driving scenes taken in 2012 in Birmingham, UK.  For each image, the observers were given a driving target (e.g., pedestrian, sign, car) specific to that image and were asked to select (by mouse click) one location where they would expect that target to appear.  

There are 3 zipped files (“driving images 1.zip”, “driving images 2.zip”, “driving images 3.zip”).  Each zipped file has 50 jpg images, named “img” + image_id (from 1 to 150).  Images are 1280 x 1024, except for image id's 28 and 65, which are 2202 x 1645.

The file ”questions.pdf” contains the question for each image, in order, giving the observer the driving target to place in the scene.

The file “heat map data.txt” contains the valid responses of 172 online observers, numbered from 1 to 319.  Each row has the following format, separated by spaces: <br>
observer_id   image_id   x   y

Analyses of these data has been presented at Vision Sciences Society, May 2015, St. Petes Beach, FL (handout.pdf): <br>
Shimozaki, S. S., Hutchinson, C. V., Swan, E. , & Mahal, J. (2015). Aging effects on expectancy use in driving scenes as assessed by the ideal observer. 

"Expectancy map.jpg" gives an example of one expectancy map when observers were asked to indicate where they expect a sign for directions.

"Fits to models.jpg" give the fits for younger and older observers to a Bayesian model for this task.  A fit to the weighted model indicates optimal use of expectancy information, and a fit the equal models indicates no use of expectancy information.  The results suggest that younger observers use expectancy, but the older observers did not.  See the poster in "handouts.jpg" for more information.

Python code to create heatmaps for these data can be found in "heat_maps.py"

Any questions about the dataset may be sent to: ibshimo2@gmail.com

