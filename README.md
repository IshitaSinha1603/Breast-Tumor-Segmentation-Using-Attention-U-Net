<h1>Breast Tumor Ultrasound Image Segmentation Using Attention U-Net</h1>
<h3>Problem Statement</h3>
<ul>The outcomes of traditional machine learning techniques in image processing were imprecise and insufficient.</ul>
<ul>Breast cancer patients may be misdiagnosed by clinicians based on ultrasound images due to the variation in tumor appearance.</ul>
<h3>Attention U-Net Model</h3>
<p>The model consists of four layers - encoder, decoder, attention gate and skip connection</p>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/1edb77c1-f5ce-454c-912a-c0988a1b4b76" alt="">
<h3>Datasets</h3>
<p>Link for the dataset: https://drive.google.com/drive/folders/1NYJYBTa60Ms4LRAnRHE_6csuaNgp9b1-?usp=drive_link</p>
<h3>Implementation Details</h3>
<ol>Start</ol>
<ol>Import necessary libraries (numpy, pandas, matplotlib, tensorflow, keras).</ol>
<ol>Set the parameters for reading the datasets.</ol>
<ol>Read the datasets.</ol>
<ol>Create an instance of Attention U-Net with encoding and decoding layers, attention gates and skip connections.</ol>
<ol>Train the Attention U-Net model on a dataset of breast tumor ultrasound images with corresponding ground truth segmentation masks.</ol>
<ol>Perform segmentation on the datasets using Attention U-Net model.</ol>
<ol>Return the segmented image with tumor region highlighted.</ol>
<ol>Stop</ol>
<h3>Flowchart</h3>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/c83ff59e-c262-4e69-9a4d-faaddd3ab741" alt="">
<h3>Result Analysis</h3>
<h4>Preprocessing the Dataset</h4>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/281d6c6a-9ca2-4c6d-b6bc-9b92714b33a4" alt="">
<h4>Training the Model using Sigmoid Activation Function</h4>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/a654c822-b573-4de0-b366-07e303e5d33a" alt="">
<h4>Table of Performance Metrics for the Model: Loss, Accuracy and Intersection over Union</h4>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/acddc980-b8c2-48c9-bff1-258a798ac492" alt="">
<h4>Graph showing model loss, model accuracy and model IoU</h4>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/e43fcf61-6c7a-47b3-977f-17c019c3794d" alt="">
<h4>Images Obtained after Training using Sigmoid Activation Function</h4>
<img src="https://github.com/IshitaSinha1603/Breast-Tumor-Segmentation-Using-Attention-U-Net/assets/143889002/aa27d284-e587-4d09-b0bf-1c9b52d6d1a9" alt="">
<h3>Conclusion</h3>
<p><b>95%</b> accuracy was achieved by using sigmoid activation function.</p>
