---
name: Dehazer
tools: [Flask, Python]
image: https://raw.githubusercontent.com/therrshan/therrshan.github.io/main/assets/img/deh.png
description: This app was developed using the Flask web app framework of python language and was optimized for deployment.
---

# DEHAZER
<br>
<br>

<p style='text-align: justify;'> The project is build using Flask library of python for web development. The frontend of the application is responsive and built using HTML, CSS and Bootstrap. The project uses the custom model built in the Fog Removal project. It takes an image and removes the fog from it and there is also an option to generate a depth map from the image using the custom Depth Prediction model. </p>

<br>
<img alt="UI" src="https://raw.githubusercontent.com/therrshan/Dehazer/master/diagrams/Landing.png"/>
<br>

## How to run
The code runs on Python 3.6+, Pytorch 0.4.1 and has a couple of other requirements which are specisified in the 'requirements.txt' which can be easily installed on a fresh virtual enviornment using the pip command.

```shell
pip install -r Requirements.txt
```

The project directory consists of the models and their files in the respective folders which are used by the app backend to predict and display the results. The main backend runs from the app.py in the root directory, thus to run the application on the local host just execute the following after sucessfull creation of the envioenment with the requirements.

```shell
python3 app.py or flask run
```
<br>

### The UI of the application

<img alt="UI Fog" src="https://raw.githubusercontent.com/therrshan/Dehazer/master/diagrams/form_a.png"/>
<img alt="UI Depth" src="https://raw.githubusercontent.com/therrshan/Dehazer/master/diagrams/form_b.png"/>

<br>

{% include elements/button.html link="https://github.com/therrshan/Dehazer" text="GitHub" block=true %}