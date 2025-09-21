Despite recent advancements in Machine Learning (ML) and Deep Learning (DL) methods for the classification and segmentation of brain tumours using MRI, there remains a gap in research regarding the integration of these methods for the most common types of brain tumours: gliomas, meningiomas, pituitary, and non-tumours. Furthermore, the impact of segmentation on classification results, particularly in this context, has not been fully explored. This project aims to bridge this gap by exploring the combination of classification and segmentation models for brain tumour diagnosis. The primary aim was to build an automated framework that integrates pre-trained models, including GoogLeNet for classification and U-Net for segmentation, to enhance diagnostic accuracy and accelerate clinical decision making in real-world medical settings. This research explored the benefits in the performance of transfer learning, hyperparameter optimisation, and data augmentations, as well as various loss functions, through careful testing and evaluation. Results of individual models indicate strong performance, with an overall classification accuracy of 98.34%, and overall Dice similarity coefficient of 0.81. However, the direct integration of segmentation into the classification pipeline led to a decrease in classification performance, prompting a shift in the pipeline design. Despite this, the project successfully met its objectives, and with further research and additional resources, remains flexible and open to future enhancements.

<p align="center">
  <img alt="pipeline_outputs" src="https://github.com/user-attachments/assets/3aa15b22-5ae6-4117-8d3c-07eee353ed9a" width="628"><br>
  <em>Outputs of the pipeline, with Glioma case on the left and No-tumour case on the right.</em>
</p>

<p align="center">
  <img alt="figshare_comp" src="https://github.com/user-attachments/assets/53107678-189e-41d5-bed7-93d51bc29a93" width="628"><br>
  <em>Comparison of brain tumour segmentation predictions between BraTS2021-trained model, and Figshare fine-tuned model.</em>
</p>

<p align="center">
  <img alt="pipeline design" src="https://github.com/user-attachments/assets/4a788ad5-fa70-47c9-ab4b-4c7b3e2a4b28" width="628"><br>
  <em>Flow Diagram of the Pipeline Design.</em>
</p>
