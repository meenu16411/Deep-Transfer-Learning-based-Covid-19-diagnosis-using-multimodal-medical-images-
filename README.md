# Deep-Transfer-Learning-based-Covid-19-diagnosis-using-multimodal-medical-images
This project aims to analyze two modalities of medical images CT-scans and X-Ray of lungs for screening of individuals as covid positive or covid-Negative using Deep Transfer learning techniques.




Project Description

This project aims to develop a deep learning-based model for automated COVID-19 screening using chest X-ray and CT-scan images. Deep transfer learning leverages pre-trained convolutional neural networks (CNNs) to reduce training time and improve performance on smaller datasets like this one.

Motivation

Early detection of COVID-19 is crucial for patient management and disease control. Radiological imaging can be a valuable tool in this process, but manual analysis by healthcare professionals is time-consuming and prone to human error. Automating the diagnosis using deep learning techniques offers the potential to:

Reduce the burden on healthcare professionals by automating the analysis of radiological images.

Lower the cost of diagnosis by eliminating the need for certain manual procedures.

Methodology

This project employs deep transfer learning to classify individuals infected with COVID-19 based on CT-scan and X-ray images. We experiment with pre-trained models like VGG19, Xception-Net, and ResNet-50, fine-tuning them on the provided dataset.

Dataset

The dataset for this project consists of 17,099 images of both healthy individuals and those infected with COVID-19, sourced from the Mendeley Data platform: https://bit.ly/4hhYlSu

Image modalities: X-ray and CT-Scan

Total images: 17,099

Breakdown:

X-ray: 9,544 images (5,500 healthy, 4,044 COVID-19)

CT-Scan: 7,555 images (2,628 healthy, 5,427 COVID-19)

Results

Our experiments revealed that the VGG19 model achieved the best performance on both image modalities:
CT-Scan Accuracy: 95%
X-Ray Accuracy: 89%
This finding aligns with the expectation that CT-scans, offering more detailed lung information due to their 3D nature, can lead to better model performance.

Publication

The work related to CT-scan data has been accepted as a book chapter in "Blockchain Applications for Healthcare Informatics: Beyond 5G," published by Academic Press, imprint of Elsevier:

Title: "Covid-19 identification and analysis using CT-scan images: Deep transfer learning based approach"

url: <https://www.sciencedirect.com/science/article/pii/B9780323906159000116>



License

This project is licensed under the MIT License.

Disclaimer

This project is for research purposes only and should not be used for clinical decision-making without further validation and regulatory approvals.
