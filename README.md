# Pedestrian Detection
### Using OpenCV
This notebook detects the total pedestrian present in a given frame of a video file.
<ul>
  <li>we have two folders named <b>'images'</b> and <b>'detected'</b>.</li>
<li>The <b>'images'</b> folder contains the frames of a video file, so when you will give the path to a video file, it will extract frames from it and place it in it, but not all, it is programmed to fetch only 1 frame per second irrespective of the frame rate of video. this is to reduce the computation power.</li>
<li>The <b>'detected'</b> folder consist of the images with bounding boxes around the pedestrian. furthermore the images are scaled, to improve the efficiency.</li>
  <li>You'll also see a <b>"information.txt'</b> file, it contains the information like how many pedestrian were detected in a particular frame, it can come handy sometimes.</li>
  <li>This project includes an virtualenv environment called <b>"env"</b> activate it before running the notebook, it contains all the essential library needed to run the project.</li>
  </ul>
