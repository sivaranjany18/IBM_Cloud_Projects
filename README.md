# IBM_Cloud_Projects
This project focuses on building a machine learning model to predict the most appropriate National Social Assistance Programme (NSAP) scheme for individuals based on their socio-economic data. The project leverages IBM Watson Studio's AutoAI feature to automate the entire ML pipeline, from data preprocessing to model deployment.

# NSAP Eligibility Prediction Using IBM AutoAI

This project uses IBM Watson Studio's AutoAI to predict the most suitable NSAP scheme (IGNOAPS, IGNWPS, IGNDPS) for an applicant based on socio-economic data.

## Tools Used
- IBM Watson Studio
- AutoAI
- Watson Machine Learning
- Python
- GitHub

## Dataset Source
[AI Kosh - NSAP Pension Data](https://aikosh.indiaai.gov.in/...)

## Features
- Gender-wise counts
- Caste category distribution
- Aadhaar/mobile availability
- Total beneficiaries

## ⚙️ Project Workflow
1. Data Collection: District-wise NSAP beneficiary data.
2. Data Preprocessing: Cleaning, encoding, normalization.
3. Model Building: AutoAI-generated pipelines using Snap Random Forest Classifier.
4. Deployment: Deployed model using Watson Machine Learning with REST API.
5. Testing: Real-time prediction via UI and CSV input.

## Deployment
Model deployed using IBM Watson ML with an API endpoint for live predictions.



