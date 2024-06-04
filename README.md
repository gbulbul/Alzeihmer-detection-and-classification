# Alzeihmer-detection-and-classification
Alzeihmer detection and classification are two different and essential tasks to take precautions for prevention and improve its treatment. DL and ML approaches are used to achieve both tasks. In this context, detection refers to discover whether a patient is demented or not. On the other hand, classification task aims to assign a patient into a correct group of alzeihmer to specify treatment while there are 4 groups defined. 


![dementia classes](https://github.com/gbulbul/Alzeihmer-detection-and-classification/assets/79763247/c4a92c22-7aee-4195-b933-6ecdab837ad8)

The above figure shows the four groups of dementia. The dementia classes can be codified like this NonDemented:0, ModerateDemented:1, MildDemented:2, VeryMildDemented:3. Similarly, in the detection procedure, there should be two classes like NonDemented:0, Demented:1.



The input for the deep learning methods are MRI images to achieve two tasks: detection & classification. 

![alzheimer images minmin](https://github.com/gbulbul/Alzeihmer-detection-and-classification/assets/79763247/a754f5de-0d4a-42ac-9fe0-f8d3da24d7ab)

7 deep learning models were compared in terms of accuracy for both tasks. From the given table below, it looks like ResNet outperformed others with respect to accuracy for both tasks. 

![Screenshot 2024-06-04 181028](https://github.com/gbulbul/Alzeihmer-detection-and-classification/assets/79763247/4315d274-fb47-4f5b-8d7e-6d290c723437)





Note on training/testing procedure: each model was trained with 5121 MRI images, then tested with 1279 MRI images.

