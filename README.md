### Bachelor_Project_Thesis_2023

**Link for our thesis 📑:** 

https://docs.google.com/document/d/1ZtumNrfg70z-JFL2MlC93SCOuWX6MHne/edit?usp=sharing&ouid=100846801129201061088&rtpof=true&sd=true


**Link for our Defense Presentation👩‍🏫:** 

https://docs.google.com/presentation/d/1YvtJh6l1Gs0jVcfTxuw5XULXHRJjlI55bLmxg_Ptv-8/edit?usp=sharing

# **ERROR ANALYSIS OF DEEP LEARNING-BASED OBJECT DETECTION IN MEDICAL IMAGES ⚒️**


<div align="center">
<img width="400" alt="image" src="https://github.com/JayeonKangNature/Bachelor_Project_Thesis_2023/assets/143944699/7e80c045-3a29-4962-99e9-1c797bbbcab8">
</div>


### **Summary of this Project**

As a Deep Learning (DL) based computer vision task, Object Detection(OD) is a critical component in gastrointestinal cancer endoscopy,
facilitating early diagnosis and improved treatment outcomes. However, further improvement is required due to the possible fatal consequences of misdetection. 
This study presents a comprehensive error analysis for OD models with Toolkit for Identifying Detection Errors (TIDE) specifically tailored for gastrointestinal cancer endoscopy.
The study aims to provide insights into annotations and enable better model comparisons through detailed error analysis. By comprehensively examining the errors classified by the TIDE, the study offered valuable insights into the strengths and limitations of the models for accurate diagnosis. Analyzed results have proven their effectiveness by tracing back to point out dataset problems and measrument for IoU. The findings provide guidance for improving annotation practices and enable more informed model comparisons based on comprehensive error analysis. The ultimate goal is to enhance the development and selection of object detection models for gastrointestinal cancer endoscopy, leading to more accurate and reliable diagnosis and improved patient outcomes.

## **What is TIDE?**

TIDE is Tool Kit Identify Detection Error as alyzing errors in results of predicted detection (like boudning box and classification).
You can see example below:

<img width="958" alt="image" src="https://github.com/JayeonKangNature/Bachelor_Project_Thesis_2023/assets/143944699/eb9d40cb-8ac4-46dc-8b4e-5773b7fc0eaf">





## **Visual Abstract of Our Project**

### **Step 1**

Natural Dataset Analysis to Gain Insight into the Object Detection Processes of YOLOv7 and Faster R-CNN, and Formulating Hypotheses for Their Performance on Medical Datasets
<div align="center">
<img width="600" alt="image" src="https://github.com/JayeonKangNature/Bachelor_Project_Thesis_2023/assets/143944699/a60f1045-8f09-44af-b96c-3d05f275eb83">
</div>


### **Step 2**

Medical Datasets Analysis to Verify Hypotheses and Investigate Error Patterns in the Medical Dataset
<div align="center">
<img width="600" alt="image" src="https://github.com/JayeonKangNature/Bachelor_Project_Thesis_2023/assets/143944699/e46f29f3-b6ed-47f6-ae1d-816fe89f47e0">
</div>

## What I do during this project?

* Developed code to train YOLOv7 and Faster RCNN models on the medical set
* Studied the architectures of both models and conducted expectation of OD predictions on the natural dataset, supported by relevant research papers
* Acquired expertise in current performance evaluation methods (IoU and mAP) for OD models
* Analyzed and understood TIDE framework and its underlying methodology through research paper about TIDE
* Performed a comparative analysis of model performance using TIDE, providing interpretation of results
