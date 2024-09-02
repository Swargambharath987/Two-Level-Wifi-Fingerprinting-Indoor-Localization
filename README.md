# Two-Level Indoor Localization using Wi-Fi Fingerprints

## Overview
Indoor localization is critical for first responders in disaster and emergency situations. This project explores the effectiveness of fingerprint-based indoor localization using Wi-Fi signals, particularly in scenarios where the environment remains relatively stable post-incident. With the proliferation of smartphone users, leveraging Wi-Fi fingerprints for indoor localization has garnered significant research interest. This method utilizes measured Wi-Fi signal strength to infer user distribution within indoor spaces.

## Motivation
In disaster and emergency scenarios, fast and accurate localization services are essential. However, traditional fingerprint-based methods often face challenges in balancing accuracy and response time, especially as the number of floors and reference points increases.

## Approach
To address this challenge, we propose a two-level localization approach to enhance both accuracy and response time. The localization process involves two main steps: floor prediction and reference point prediction. 
- **Floor Prediction:** We employ the K-Nearest Neighbors (KNN) classification algorithm to predict the floor.
- **Reference Point Prediction:** On the predicted floor, various machine learning models such as Random Forest, Decision Tree, and Support Vector Machine are utilized for reference point prediction.

## Dataset
The dataset used in this study comprises two files with different floor numbers. 
1. Energy-Efficient Indoor Localization Wifi-Fingerprint Dataset by Dataport 
2. WLAN (WiFi) RSS database for fingerprinting positioning by Tampere University

## Results
Experimental results demonstrate that the Random Forest model achieves the highest accuracy of 96.1% among the tested machine learning models. Consequently, the two-level localization method proves superior to single-level approaches in terms of both localization accuracy and speed.

## Usage
Feel free to explore the codebase to gain insights into our two-level localization approach. You can run experiments with your own datasets or contribute to the project by enhancing the existing algorithms or proposing novel methods.

## Contact
For any inquiries, feedback, or collaboration opportunities, please contact swargambharath987@gmail.com

## Citations

If you use our methodology or findings in your work, please cite the following conference paper:

@inproceedings{10.1145/3571306.3571429,
author = {Swargam, Bharath Kumar and Yadav, Ram Narayan and Chaturvedi, Manish},
title = {Two Level Wi-Fi Fingerprinting based Indoor Localization using Machine Learning},
year = {2023},
isbn = {9781450397964},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = { https://doi.org/10.1145/3571306.3571429 },
doi = {10.1145/3571306.3571429},
booktitle = {Proceedings of the 24th International Conference on Distributed Computing and Networking},
pages = {324–329},
numpages = {6},
keywords = {indoor localization, Wi-Fi fingerprint, Random Forest, ML models, K-Nearest Neighbour, Disaster management},
location = {<conf-loc>, <city>Kharagpur</city>, <country>India</country>, </conf-loc>},
series = {ICDCN '23}
}
