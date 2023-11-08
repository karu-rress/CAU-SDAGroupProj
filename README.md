# Security Data Analysis Group Project

## About this project

Our team project aims to develop a model for detecting Android malware. The problem we seek to solve is the accurate classification of Android applications into either malicious or non-malicious applications. More accurately divide them between one of four categories: Android Adware, Android Scareware, Android SMS Malware, or Benign. 

Chosen data set: [Android Malware Detection](https://www.kaggle.com/datasets/subhajournal/android-malware-detection)

Data Source:
The dataset used for our project contains 355,630 entries (instances or rows) and is characterized by 86 columns. The labels within the dataset are divided into four categories:

- Android Adware: 147,443 instances - This category includes applications that display intrusive and unwanted advertisements to users. They may collect user data for targeted advertising, leading to privacy concerns.
- Android Scareware: 117,082 instances - These use deceptive tactics to trick users into taking certain actions, such as purchasing fake security software. These apps often create a sense of urgency or fear to manipulate users.
- Android SMS Malware: 67,397 instances - These applications are designed to send unauthorized and potentially costly text messages from the user's device. 
- Benign: 23,708 instances - These are considered safe and non-malicious. These are legitimate and harmless Android applications that do not pose any security or privacy threats to the users' devices.

The data we will be working with includes various features related to the applications, such as permissions requested, API calls made, network activity, and more. We aim to build a model that can effectively identify and classify new Android applications into one of these categories, distinguishing between malicious and non-malicious apps. The outcome of this project will contribute to protecting users from potentially harmful applications.

## Notice
In order to use *.ipynb files here, you need to place the dataset file ```Android_Malware.csv``` into cloned directory.
