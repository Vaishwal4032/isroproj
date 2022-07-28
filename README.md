# isroproj

This project is made during my Internship at ISRO with my group partner https://github.com/Harsh7300. This Machine Learning Model basically detects the manufacturer and model of a vehicle. We match it by it's number plate. If they matches it's a legal number plate otherwise it's fake.Now here we present you the second part of the project.<br>


# Requirements

numpy<br>
panda<br>
keras<br>
opencv<br>
tensorflow<br>
matolotlib<br>
scipy

# Usage
<br>
First, if you have no resnet152 model trained and you need from scratch to do it you need to:<br><br>

* download dataset<br>
* preprocess the dataset<br>
* train the model<br>
Afterward you can try a new sample.

 ## download dataset
 
 I suggest using http://vmmrdb.cecsresearch.org/ as a dataset, it's free and full of labeled    images for car model recognition instead of detection (most datasets are for this).
 
 ## preprocess the dataset
 
 I have made directories using mkdir and copied dataset to train in my main file
 
 ## Train the model
 Before the training process, modify the EPOCS ,usually I have used 7 classes30-60 EPOCS that's enough then we she the curve and we check blue curve is stable.
