# Medical-Diagnosis-Assistant
 Multimodal deep learning system that analyzes chest X-ray images and  corresponding doctor’s notes to predict multiple diseases (e.g., pneumonia,  cardiomegaly) with high precision
This project is a compilation of several sub-projects from the Coursera 3-course IA for Medical Specialization. Its goal is to use a deep learning model to diagnose diseases from Chest X-Rays.

It uses a pretrained DenseNet-121 model capable of identifying 14 conditions, including Cardiomegaly, Mass, Pneumothorax, and Edema. Essentially, the model provides binary predictions for each of these 14 pathologies.

Weight normalization is applied to address the class imbalance in the X-Ray dataset, where some conditions are less common.

Finally, the GradCAM technique is used to visualize the regions the model focuses on when making predictions. This helps in identifying markers, analyzing errors, improving training, and even supporting deployment.
