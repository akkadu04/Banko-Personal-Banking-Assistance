
<h1 align="center">Banko:Personal Banking Navigator</h1>

<div align= "center">
  <h4>A Socket Programming architecture based terminal based system </h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/issues)
[![Forks](https://img.shields.io/github/forks/dheerajsharma0401/Chest-Xrays-Pneumonia-Predictionsvg?logo=github)](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/network/members)
[![Stargazers](https://img.shields.io/github/stars/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction.svg?logo=github)](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/stargazers)
[![Issues](https://img.shields.io/github/issues/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction.svg?logo=github)](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/issues)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/dheeraj-sharma-142bb0190/)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<p align="center"><img src="https://github.com/akkadu04/Banko-Personal-Banking-Assistance/blob/main/Outputs/logo.png" width="700" height="400"></p>
<p align="center"><b>Banko-Your Personal Banking Navigator</b></p>

## :innocent: Motivation
It is very difficult for an individual to find a bank in a new city to which he/she is completely stranger.
Many people from villages come to cities for investing or creating a bank account in order to save their earnings.The people who are not much aware of technology might find it difficult to use fancy Apps. In order to build a bridge between a city and a person who is unknown to the city ,there must be some system which must act as a guide.
So, we came up with an idea in which we ask the person the nearby famous landmark in the city. The system is designed in such a way that it will take user input and display the information about bank ,this information include Bank name,address,Weekly timetable of Bank(in hrs) ,Phone number of branch also detail about availability of ATM machine and Deposit machine.In this way a our proposed system can be helpful to people. 

</br></br> This is a terminal Based application that is made using client server architecture.




<!---Unable to communicate verbally is a disability. In order to communicate there are many ways, one of the most popular methods is the use of predefined sign languages. The purpose of this project is to bridge the __research gap__ and to contribute to recognize __American sign languages(ASL)__ with maximum efficiency. This repository focuses on the recognition of ASL in real time, converting predicted characters to sentences and output is generated in terms of voice formats. The system is trained by convolutional neural networks for the classification of __26 alphabets__ and one extra alphabet for null character. The proposed work has achieved an efficiency of __99.88%__ on the test set.--->


## ⚠: FlowChart

<p align="center"><img src="https://github.com/akkadu04/Banko-Personal-Banking-Assistance/blob/main/Outputs/ClientFlow.png" width="781" height="794"></p>

<p align="center"><b>ClientSide Flowchart</b></p>


<p align="center"><img src="https://github.com/akkadu04/Banko-Personal-Banking-Assistance/blob/main/Outputs/ServerFlow.png" width="724" height="743"></p>

<p align="center"><b>ServerSide Flowchart</b></p>


## :star: Algorithm

STEP 1:START<br>
STEP 2: Establish secure connection between client sever(Enter proper ip address)<br>
STEP 3:Fix errors(if any) while establishing connection.<br>
STEP 4:After establishing connection ask (user)client side to enter the choice.<br>
STEP 5: On client side, check if the choice is valid or not.<br>
If( not valid)<br>
 ask user to enter a valid choice<br>
Else<br>
  Send choice to server
STEP 6:Server Side Recieve the choice sent by client<br>
STEP 7:Load the contents of file associated with the choice into buffer and send it to client side.<br>
STEP 8:The result is displayed on the client side to the user (as soon as buffer arrives on the client side)<br>
STEP 9:END<br>





## :file_folder: Data Distribution
The dataset used can be downloaded here - [Click to Download](https://drive.google.com/drive/folders/1f6QGKHQ2rJD3jCrumAKXPbUg_Q8TenFz?usp=sharing)

This dataset consists of __images__ belonging to 2 classes:
<!---*	__Training Set: 12845 images__<br />
<p align="center"><img src="https://github.com/beingaryan/Sign-To-Speech-Conversion/blob/master/Analysis/train_data_distribution.png" ></br><b>Train Data Statistics</b></p>
<!---<br />![](Analysis/train_data_distribution.png)<br />--->

<!---*	__Test Set: 4368 images__<br />
<p align="center"><img src="https://github.com/beingaryan/Sign-To-Speech-Conversion/blob/master/Analysis/test_data_Distribution.png" ></br><b>Test Data Statistics</b></p>
<!---<br />![](Analysis/train_data_distribution.png)<br />--->



## :star: Features
Our model is capable of predicting Pneumonia from chest x-ray images with high efficiency. These __predicted images__ are converted to grayscale version for predictions.</br></br>
The model is efficient, since we used a compact __CNN-based architecture__, it’s also computationally efficient and thus making it easier to deploy the model to servers.
<!---
## 🎨 Feature Extraction
* Gaussian filter is used as a pre-processing technique to make the image smooth and eliminate all the irrelevat noise.
* Intensity is analyzed and Non-Maximum suppression is implemented to remove false edges.
* For a better pre-processed image data, double thresholding is implemented to consider only the strong edges in the images.
* All the weak edges are finally removed and only the strong edges are consdered for the further phases. <br />
<br />![](Analysis/fe.png)<br />
The above figure shows pre-processed image with extracted features which is sent to the model for classification.--->


## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/blob/main/requirements.txt)

## 🚀&nbsp; Installation
1. Start and fork the repository.

2. Clone the repo
```
$ git clone https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction.git
```

3. Change your directory to the cloned repo and create a Python virtual environment named 'test'
```
$ mkvirtualenv test
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## :bulb: Working

1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 jupyter
```

2. To train the model, open the [Pneumonia_Prediction](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/blob/main/PNEUMONIA_DETECTION.ipynb) file in jupyter notebook and run all the cells </br>

</br></br>
## :key: Results 
#### Our model gave 98.51% accuracy for validation set of Pneumonia Detection via <code>tensorflow-gpu==2.0.0</code>
<br />
* The model has been trained on a python based environment on Jupyter platform.
* The model is iterated for a total epoch of 12. 
* The model has attained an accuracy of __98.51 %__ accuracy on the Validation set.

#### We got the following accuracy vs. epochs curve plot
![](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/blob/main/Outputs/accuracy%20vs%20epochs.png)<br />
#### The above figure shows the Accracy plot of the model throughout it's training journey. 

<br /><br />![](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/blob/main/Outputs/loss%20vs%20epochs.png)<br/>
#### The above figure shows the Loss plot of the model throughout it's training journey. 


## :clap: And it's done!
Feel free to mail me for any doubts/query 
:email: dheeraj.sharma18@vit.edu



## :handshake: Contribution
Feel free to **file a new issue** with a respective title and description on the the [Pneumonia_Detection](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**!


## :heart: Owner
Made with :heart:&nbsp;  by [Dheeraj Sharma](https://github.com/dheerajsharma0401)


## :+1: Credits
* [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)
* [https://opencv.org/](https://opencv.org/)


## :handshake: Our Contributors
[CONTRIBUTORS.md](/CONTRIBUTORS.md)

## :eyes: Code of Conduct

You can find our Code of Conduct [here](/CODE_OF_CONDUCT.md).


## :eyes: License
MIT © [Dheeraj Sharma](https://github.com/dheerajsharma0401/Chest-Xrays-Pneumonia-Prediction/blob/main/LICENSE)








