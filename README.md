

<h2>Predicting Wildfires with Convolutional Neural Networks (CNNs)</h2>

<p>Wildfires pose a significant threat to ecosystems, wildlife, and human lives, making early detection and prediction crucial for effective wildfire management. Convolutional Neural Networks (CNNs) have emerged as a powerful tool for predicting wildfires due to their ability to extract complex patterns from spatial data, such as satellite images and weather data. CNNs can analyze various factors that contribute to wildfire risk, including vegetation density, temperature, humidity, and wind speed. By training CNNs on historical wildfire data and environmental factors, these models can learn to identify patterns indicative of potential wildfire outbreaks. One of the key advantages of using CNNs for wildfire prediction is their ability to process large-scale, high-resolution satellite imagery quickly. This allows for real-time monitoring of wildfire-prone areas, enabling early detection and timely deployment of firefighting resources.</p>

<br>

<p>Additionally, CNNs can improve the accuracy of wildfire prediction models by integrating data from multiple sources, such as satellite imagery, weather stations, and historical fire records. This holistic approach provides a comprehensive view of wildfire risk factors, leading to more reliable predictions.</p>

<br>

<h2>Wildfire Prediction Dataset</h2>

  <p>This dataset consists of satellite images with a resolution of 350x350 pixels, categorized into two classes: Wildfire and No Wildfire. The dataset contains a total of 42,850 images, with 22,710 images belonging to the Wildfire class and 20,140 images belonging to the No Wildfire class. To facilitate model training and evaluation, the dataset has been divided into three subsets: training, testing, and validation. The distribution of images among these subsets is as follows:</p>  

<ul>

<li><b>Training Set:</b> Approximately 70% of the dataset, used for training the model.</li>

<li><b>Testing Set:</b> Approximately 15% of the dataset, used for evaluating the model's performance.</li>

<li><b>Validation Set:</b> Approximately 15% of the dataset, used for fine-tuning hyperparameters and validating the model's performance.</li>

</ul>  

<p>Each image in the dataset represents a snapshot of the Earth's surface, captured by satellite imagery. These images contain valuable information about vegetation, land cover, and other environmental factors that can be used to predict the likelihood of wildfires.</p>  

<br>  

<h2>Objectives</h2>  

<p>Using <i>longitude</i> and <i>latitude</i> coordinates for each wildfire spot <i>(> 0.01 acres burned)</i> found on the dataset above we extracted satellite images of those areas using MapBox API to create a more convenient format of the dataset for <i>deep learning</i> and building a model that can predict whether an area is at risk of a wildfire or not. <b>Models created with this dataset predict where a fire could potentially occur. It was created on this basis by the Canadian state. This inference was made only through RGB bands. This should be taken into account.</b></p> 

<br>  

<p>To download the dataset from Kaggle, you need to have a kaggle account.</p>



<h2>Keywords</h2>
<ul>
  <li>Wildfire</li>
  <li>Earth Science</li>
  <li>Classification</li>
  <li>Class Activation Maps</li>
  <li>Deep Learning</li>
  <li>Satellite Imagery</li>
  <li>VGG-16</li>
</ul>





<br>



