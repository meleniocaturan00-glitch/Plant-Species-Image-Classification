# Plant-Species-Image-Classification

#Exported model files https://drive.google.com/drive/folders/1ZQeKdOQdZI_aq6WwPuKjTWgirQwwszgj?usp=drive_link
DATA SET SCREENSHOT
<img width="1861" height="1024" alt="Screenshot 2026-02-16 015315" src="https://github.com/user-attachments/assets/572167cf-ed18-417d-8db5-ecc1c01beab0" />


#Brief description of the project

This project focuses on creating a comprehensive image dataset of herbal plants for research and educational purposes. Each class contains 250 high-quality images, and the dataset includes a total of 5,000 images. The collection aims to support tasks such as plant identification, classification, and analysis using machine learning and computer vision techniques. By providing a balanced and well-organized dataset, this project helps improve the accuracy and reliability of herbal plant recognition systems.

#PURPOSE OF THE IMAGE CLASSIFICATION MODEL 

The purpose of this image classification model is to accurately identify and classify different types of herbal plants from images. It is designed to support automated plant recognition, assist researchers and students in botanical studies, and improve efficiency in herbal plant analysis. By using the dataset of 5,000 images with balanced classes, the model helps reduce human error, saves time, and enables reliable decision-making in applications such as agriculture, medicine, and environmental monitoring.

B. Plant Species Section

![red_sage_plant](https://github.com/user-attachments/assets/a4846f6c-5c9c-4af8-9bfa-b97f652fd505)

Common Name: Scarlet Sage / Red Salvia
Scientific Name (Specific Term): Salvia splendens
Family: Lamiaceae (Mint family)



Scarlet sage (*Salvia splendens*) is a beautiful flowering plant known for its bright red flowers and green leaves. It belongs to the mint family and is commonly grown in gardens and parks for decoration. Its colorful appearance makes it very attractive and popular in landscaping.

This plant grows well in sunny areas and needs well-drained soil and regular watering. It is easy to care for, making it suitable for beginners and students. Scarlet sage also attracts pollinators such as bees and butterflies, which help support the environment.

In conclusion, scarlet sage is an important ornamental plant that adds beauty to natural spaces. Its easy cultivation and environmental benefits make it valuable for both gardeners and nature lovers.



C. Model Training Details


<img width="276" height="608" alt="Screenshot 2026-02-15 225526" src="https://github.com/user-attachments/assets/d87fcd09-9885-41d7-b4b8-31a77c9a1bc2" />
Number of images per class :250


D. Model Evaluation


<img width="384" height="1035" alt="image" src="https://github.com/user-attachments/assets/d69efadd-7544-4039-b940-d3cd52d54e22" />


E. Model Testing











<img width="300" height="1025" alt="sample1" src="https://github.com/user-attachments/assets/573347eb-9969-4931-bef7-b73fdc0d8ef1" /> <img width="225" height="1014" alt="sample 2" src="https://github.com/user-attachments/assets/55025283-f446-4f5f-95f6-898cfa4ba1d1" /> <img width="216" height="1000" alt="sample 3" src="https://github.com/user-attachments/assets/d8b0b1f3-2592-4181-8f6e-8a830ece8d89" /> <img width="225" height="998" alt="sample 4" src="https://github.com/user-attachments/assets/2a3b2412-0d7d-407e-b29e-e5afeadcea81" /> <img width="237" height="1016" alt="sample 5" src="https://github.com/user-attachments/assets/af9b9d39-4e61-44e9-a0a5-e510ec45249a" /> <img width="218" height="1020" alt="sample 6" src="https://github.com/user-attachments/assets/a38bc23c-910d-496a-b5f4-34d5243a2489" /> <img width="221" height="1016" alt="sample 7" src="https://github.com/user-attachments/assets/dae912ea-6d39-4ef0-9b90-9ddd24eaefef" /> <img width="219" height="1013" alt="sample 8" src="https://github.com/user-attachments/assets/0612db2e-716b-4fd3-a819-c609a715a9d1" /> <img width="227" height="1010" alt="sample 9" src="https://github.com/user-attachments/assets/b0320223-e9fa-4d6c-aa1a-75cfdc50ca87" /> <img width="225" height="1014" alt="sample 10" src="https://github.com/user-attachments/assets/ddf3f09c-2e76-4308-9700-a257090049e7" />


#REFLECTION QUESTIONS :

1.How did the number of images per class affect your model’s accuracy?

answer:Having 250 images per class helped improve the model’s accuracy by providing enough data for each plant species. Since all classes had the same number of images, the dataset was balanced, which reduced bias and prevented the model from favoring one class over another. This balance helped the model learn better features and improved overall performance.

2.Which plant species were most commonly misclassified and why?

answer:Some plant species with similar leaf shapes, colors, or flower patterns were more commonly misclassified. This happened because the visual features of these plants were very close, making it difficult for the model to clearly distinguish between them. Variations in lighting, background, and image quality also contributed to misclassification.

3.How did changing the epochs, batch size, or learning rate affect the training results?

answer:Increasing the number of epochs improved accuracy at first because the model had more time to learn patterns. However, too many epochs caused overfitting. Changing the batch size affected training speed and stability, where smaller batch sizes gave more stable learning but slower training. Adjusting the learning rate was important because a high learning rate caused unstable results, while a low learning rate slowed down training.

4.What challenges did you encounter during dataset collection and labeling?

answer:One major challenge was finding enough high-quality images for each plant species. Some images had poor lighting, unclear backgrounds, or low resolution. Another difficulty was correctly labeling similar-looking plants, which required careful checking to avoid mistakes and ensure accuracy.

5.If you were to improve your model, what specific changes would you make and why?

answer:To improve the model, I would increase the size of the dataset by adding more images from different environments and angles. I would also apply data augmentation techniques to improve generalization. Using a more advanced deep learning architecture and fine-tuning hyperparameters would further enhance accuracy. Additionally, improving image quality and background removal could help reduce misclassification.









