# SelfDrivingCar Using CNN + LSTM

Find the complete code, dataset and Reference by <b><a href="https://drive.google.com/drive/folders/1I31SxLuFwDE_GV-ozzMdP4Hd6Tk786ub?usp=sharing">CLICKING HERE</a></b>

<img src="https://github.com/iamrudra-narayan/SelfDrivingCar/blob/master/car.jpg">
<br>
<h2><b>INTRODUCTION</b></h2>
<br>
<ul>
  <li>Used convolutional neural networks (CNNs) to map the raw pixels from a front-facing camera to the steering commands for a self-driving car. This powerful end-to-end approach means that with minimum training data from humans, the system learns to steer, with or without lane markings, on both local roads and highways. The system can also operate in areas with unclear visual guidance such as parking lots or unpaved roads.</li>

<li>The system is trained to automatically learn the internal representations of necessary processing steps, such as detecting useful road features, with only the human steering angle as the training signal. We do not need to explicitly trained it to detect, for example, the outline of roads.</li>

<li>End-to-end learning leads to better performance and smaller systems. Better performance results because the internal components self-optimize to maximize overall system performance, instead of optimizing human-selected intermediate criteria, e. g., lane detection. Such criteria understandably are selected for ease of human interpretation which doesn’t automatically guarantee maximum system performance. Smaller networks are possible because the system learns to solve the problem with the minimal number of processing steps.</li>
</ul>
<br>
<br>
<h2><b>ABOUT DATASET</b></h2>
<br>
<b>Find the Complete Dataset by <a href="https://drive.google.com/drive/folders/1WLNHqePrioUnpowv6xpu6l0Cb0VQ27BB?usp=sharing">CLICKING HERE</a></b>
<br>
<h4><i><p>For a self-driving car project, your dataset seems to contain images along with their corresponding file paths and angles in degrees. This dataset is likely used for training a model to predict steering angles based on the images captured by the car's sensors.</p></i></h4>
<br>
<ol>
  <li>
    <h5><b>ImageId: </b></h5> This column likely contains unique identifiers or names for each image in your dataset. These could be numerical IDs, alphanumeric codes, or any other unique identifier assigned to each image.
  </li>
  <li>
    <h5><b>ImagePath: </b></h5> This column contains the file paths to the images in your dataset. These paths specify the location of each image file on your filesystem. They could be absolute paths or relative paths depending on how your dataset is structured.
  </li>
  <li>
    <h5><b>Angles: </b></h5> This column contains the steering angles corresponding to each image in your dataset, represented in degrees. These angles indicate the direction in which the vehicle should steer at the time the image was captured. Positive angles may correspond to turning right, while negative angles may correspond to turning left.
  </li>
</ol>
<br>
<br>
<h2><b>CONCLUSION</b></h2>
<br>
<ul>
  <li>
    In conclusion, our self-driving car project employing a CNN+LSTM architecture marks a significant stride toward autonomous vehicle development. Through meticulous experimentation and analysis, we've demonstrated the efficacy of our model in accurately predicting steering angles based on input images. Leveraging the complementary strengths of convolutional neural networks and long short-term memory networks, we've effectively captured spatial and temporal dependencies in the driving environment. Our findings underscore the potential of interdisciplinary collaboration and continuous innovation in advancing self-driving technology. Looking forward, further research focusing on robustness, real-time sensor integration, and ethical considerations will be crucial for the widespread adoption of autonomous vehicles, reshaping the future of transportation.
  </li>
</ul>
<br>
<br>
<h2><b>REFERENCES</b></h2>
<br>
<ol>
    <li><b>Github:</b>  https://github.com/PankajKarki/Self-Driving-Car/tree/master</li>
    <li><b>Research paper:</b> End to End Learning for Self-Driving Cars by Nvidia[https://arxiv.org/pdf/1604.07316.pdf]</li>
    <li><b>Nvidia blog:</b> https://devblogs.nvidia.com/deep-learning-self-driving-cars/</li>
</ol>
<br>
<br>
<h1><b>THANK YOU</b></h1>
