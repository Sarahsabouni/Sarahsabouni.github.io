### Professional Summary

Hello! I’m Sarah Sabouni, a seasoned BI Developer and Data Analyst based in Ontario, Canada. With a strong track 

# Sarah Sabouni's Portfolio

Hello! I'm Sarah Sabouni, a seasoned BI Developer and Data Analyst based in Ontario, Canada. With a strong passion for data science and software engineering. Welcome to my public portfolio, where I showcase my skills and share my journey in the realm of data.

## Contact Information

Feel free to reach out to me at: sarahsabouni1@outlook.com

## Key Skills and Experience

* **Data-Driven Approach**: I am committed to leveraging my skills to drive impactful results for organizations, utilizing a data-driven approach in decision-making.

* **Cross-Functional Collaboration**: I've successfully collaborated with cross-functional teams to develop and deploy software solutions, conduct data analysis, and create data-driven models that inform research decisions.

* **Technical Proficiency**: Proficient in Python and other data analysis tools, I've developed robust simulations, conducted statistical analysis, and built predictive models.

## Portfolio Highlights

Explore my portfolio to find my CV and a collection of personal projects that implement state-of-the-art Data Science techniques. I am continually excited to bring my technical and analytical skills to a data science role where I can learn, grow, and make a meaningful impact.


## [Project 1: Generative AI Data Augmentation Tool](https://github.com/SantMiro/AI_Data_Augmentation_Tool)

This repository contains a data augmentation tool that utilizes a Generative Adversarial Network (GAN) to synthesize tabular data, specifically tailored for the detection of credit card fraud. The primary goal of this project is to tackle the issue of class imbalance in fraud detection datasets by generating realistic synthetic data, improving the robustness of predictive models.

![GAN Model](https://github.com/SantMiro/AI_Data_Augmentation_Tool/blob/main/notebooks/pipelines.png?raw=true)

## Features
* Generative Adversarial Network (GAN): A GAN trained to generate synthetic credit card transaction data while preserving critical patterns.
* Data Augmentation: This tool generates additional fraud and non-fraud samples, balancing the dataset and improving model performance.
* Flask Web Application: The app provides a user-friendly interface for generating synthetic data and integrating it with existing datasets.
* Containerized Deployment: Dockerized for easy deployment on cloud platforms or local environments.

## [Project 2: Bird Song Classification App](https://github.com/SantMiro/Song_Bird_App)

This repository contains all the files used for building a bird song classification model and web app using Flask.

The purpose of this application is to develop and train a CNN model for classification of bird songs between different type of species. The test accuracy of the trained data was 84%.

The web app can be accessed [here](https://bird-song-app-eb9e15e2fa87.herokuapp.com/).

At this moment there are only five birds in the training catalogue:

<div style="display: flex; flex-wrap: wrap; justify-content: center;">

<div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.allaboutbirds.org/guide/American_Robin/photo-gallery" target="_blank">
    <img src="https://github.com/SantMiro/Song_Bird_App/raw/main/static/images/american_robin.jpg" alt="Bird 1" style="width: 100px; height: auto;">
  </a>
  <h3 style="font-size: 14px;">American Robin</h3>
  <p class="author" style="font-size: 12px;">Author: 
    <a href="https://www.allaboutbirds.org/guide/American_Robin/photo-gallery#" target="_blank">Alex Eberts</a>
  </p>
</div>

<div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.allaboutbirds.org/guide/Bewicks_Wren/photo-gallery" target="_blank">
    <img src="https://github.com/SantMiro/Song_Bird_App/raw/main/static/images/bewicks_wren.jpg" alt="Bird 2" style="width: 100px; height: auto;">
  </a>
  <h3 style="font-size: 14px;">Bewick's Wren</h3>
  <p class="author" style="font-size: 12px;">Author: 
    <a href="https://www.allaboutbirds.org/guide/Bewicks_Wren/photo-gallery" target="_blank">Michael Stubblefield</a>
  </p>
</div>

<div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.allaboutbirds.org/guide/Northern_Cardinal/photo-gallery" target="_blank">
    <img src="https://github.com/SantMiro/Song_Bird_App/raw/main/static/images/northern_cardinal.jpg" alt="Bird 3" style="width: 100px; height: auto;">
  </a>
  <h3 style="font-size: 14px;">Northern Cardinal</h3>
  <p class="author" style="font-size: 12px;">Author: 
    <a href="https://www.allaboutbirds.org/guide/Northern_Cardinal/photo-gallery" target="_blank">Suzie McCann</a>
  </p>
</div>

<div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.allaboutbirds.org/guide/Northern_Mockingbird/photo-gallery" target="_blank">
    <img src="https://github.com/SantMiro/Song_Bird_App/raw/main/static/images/northern_mockingbird.jpg" alt="Bird 4" style="width: 100px; height: auto;">
  </a>
  <h3 style="font-size: 14px;">Northern Mockingbird</h3>
  <p class="author" style="font-size: 12px;">Author: 
    <a href="https://www.allaboutbirds.org/guide/Northern_Mockingbird/photo-gallery" target="_blank">Jay McGowan</a>
  </p>
</div>

<div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.allaboutbirds.org/guide/Song_Sparrow/photo-gallery" target="_blank">
    <img src="https://github.com/SantMiro/Song_Bird_App/raw/main/static/images/song_sparrow.jpg" alt="Bird 5" style="width: 100px; height: auto;">
  </a>
  <h3 style="font-size: 14px;">Song Sparrow</h3>
  <p class="author" style="font-size: 12px;">Author: 
    <a href="https://www.allaboutbirds.org/guide/Song_Sparrow/photo-gallery" target="_blank">Jonathan Irons</a>
  </p>
</div>

</div>

 

The data was obtained from [Kaggle](https://www.kaggle.com/datasets/vinayshanbhag/bird-song-data-set) and sourced from [xeno-canto](https://www.xeno-canto.org/).

## [Project 3: Image Classifier](https://github.com/SantMiro/Image_Classifier)

This GitHub project is a personal endeavor aimed at exploring the classification of AI-generated images using a Convolutional Neural Network (CNN). The CNN is trained to discern between three distinct classes:  DALL-E-2 - generated images, Stable Diffusion-generated images, and Human-made images. 

The DALL-E-2 - generated images were scraped from the source [DALL-E 2 Gallery](https://dalle2.gallery).
The Stable Diffusion-generated images were accessed from [DB Stable Diffusion](https://huggingface.co/datasets/poloclub/diffusiondb).
The Human-generated images were both scraped from google and accessed from the source [DB Human Generated](https://huggingface.co/datasets/poloclub/diffusiondb).

<p align="center">
<img src="./Images/combined_figure.png" width="570" height="230" />
</p>

## [Project 4: International Space Station Distance Calculator](https://github.com/SantMiro/ISS-Distance)


This Flask app calculates the distance from your location to the International Space Station (ISS). Deployed on Google Cloud Platform (GCP), the app retrieves the current position of the ISS via its open API. It then asks the user to provide a valid address, which is converted to coordinates using GCP API credentials. The app calculates the distance between the user's coordinates and the ISS using the Haversine formula.

As an additional feature, if the ISS and the user are in the same country, the app estimates the driving time to the projected position of the ISS.

<div style="display: flex; flex-wrap: wrap; justify-content: center;">
  <div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.nasa.gov/international-space-station/" target="_blank">
    <img src="./Images/iss.jpg" alt="ISS" style="width: 160px; height: 100;">
  </a>
  </div>
  <div style="margin: 10px; text-align: center; flex-basis: 20%;">
  <a href="https://www.linkedin.com/pulse/haversine-formula-firebird-sql-calculate-distance-between-revelli/" target="_blank">
    <img src="./Images/haversine.png" alt="Haversine" style="width: 100px; height: auto;">
  </a>
  </div>
</div>




## [Project 5: Metabolomic Analysis in Pediatric Crohn's Disease Patients: A Machine Learning Approach](https://github.com/SantMiro/Metabolomics_Analysis)


The objective of this work is to perform an exploratory data analysis on serum metabolomics from 56 pCD patients. Samples were collected twice: once at study initiation (Visit One) and again for completion (Visit Four). The collected serum underwent liquid chromatography followed by mass spectrometry to identify 131 compounds.

Serum metabolites are analyzed using Unsupervised (U.ML) and Supervised (S.ML) Machine Learning algorithms. U.ML is used to reduce the dimensionality of the data and identify clusters, while S.ML is used to develop regression and classification algorithms to assess the correlation between metabolites and disease activity.

Results show that Tryptophan is the metabolite that ranks the highest in feature importance scoring. Histidine is another metabolite that correlates well with the severity of the disease. In the regression analysis, it was observed that Partial Least Squares (PLS) with LOL reduction setting incurred the least Mean Squared Error (MSE) of 0.8806. In the classification process, Random Forest with Linear Discriminant Analysis (LDA) setting achieved the least False Negative rate of 0.53, and K-Nearest Neighbors (KNN) with Principal Component Analysis (PCA) setting yielded the highest accuracy score of 63. 

See full paper [here](https://github.com/SantMiro/Metabolomics_Analysis/blob/main/Metabolomics_Analysis.pdf).

## [Collection of 100 Python Projects](https://github.com/SantMiro/python_100_projects)

This repository will contain a collection of 100 python projects from begginer level to advanced.
