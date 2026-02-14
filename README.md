A. Project Overview

This project is an Image Classification Model built using Google Teachable Machine.

The purpose of this model is to classify 20 different ornamental, rare, and exotic plant species using deep learning techniques.

The dataset consists of 5,000+ images (250 images per class), collected from multiple angles and lighting conditions.

20 Plants
1. Begonia 
2. Z Plant 
3. Monstera 
4. Hostas 
5. Camellia 
6. Oleander 
7. Hydrangea 
8. Petunia 
9. Azalea 
10. Geranium 
11. Paper Flower Tree (Bougainvillea) 
12. Rock Rose (Cistus) 
13. Welwitschia mirabilis 
14. Puya raimondii 
15. Blue Puya (Puya berteroniana) 
16. Corypha umbraculifera 
17. Metasequoia glyptostroboides 
18. Nepenthes rajah 
19. Ravenala madagascariensis 
20. Himalayan Blue Poppy 


B. Plant Species Section
Begonia

Common Name: Begonia

Scientific Name: Begonia spp.

Description: Begonias are ornamental flowering plants known for their colorful leaves and asymmetrical foliage. They are commonly used in indoor and garden landscaping due to their vibrant flowers and decorative patterns.

C. Model Training Details

● Epochs- 60
● Batch size-16
● Learning rate- 0.001
● Number of images per class - 250

D. Model Evaluation

<img width="1909" height="889" alt="2" src="https://github.com/user-attachments/assets/f037f91e-da71-4578-b01a-8e715bfead4f" />

E. Model Testing

Azalea
<img width="1891" height="879" alt="Azalea" src="https://github.com/user-attachments/assets/a32dfcd2-ed83-4fe2-b304-0c6cab3fb18b" />

bergonia
<img width="1916" height="853" alt="bergonia" src="https://github.com/user-attachments/assets/85acd037-8abd-452f-91e1-5b2667dc4404" />

Blue Puya (Puya berteroniana)
<img width="1887" height="863" alt="Blue Puya (Puya berteroniana)" src="https://github.com/user-attachments/assets/e63c6894-8f70-43c6-b8ef-792f706a4cc2" />

Camellia
<img width="1908" height="875" alt="Camellia" src="https://github.com/user-attachments/assets/ccbe1815-c167-42e0-b5e3-2ec6c7e889be" />

Corypha umbraculifera
<img width="1906" height="845" alt="Corypha umbraculifera" src="https://github.com/user-attachments/assets/463a7888-3c10-4397-b7e9-8c3d5417cde9" />

Himalayan Blue Poppy
<img width="1920" height="892" alt="Himalayan Blue Poppy" src="https://github.com/user-attachments/assets/0ef7cc3a-a0eb-4cfb-b4dd-d686def1aebe" />

Hostas
<img width="1904" height="841" alt="Hostas" src="https://github.com/user-attachments/assets/683137fc-582a-44ce-a39c-5e13570ab1e1" />

Nepenthes rajah
<img width="1918" height="863" alt="Nepenthes rajah" src="https://github.com/user-attachments/assets/f013a251-a5a2-4f3d-b5f8-fc05ea4a7f7c" />

petunia
<img width="1917" height="878" alt="petunia" src="https://github.com/user-attachments/assets/8c70c3f0-7e9b-45ba-88e8-8bb023e16f57" />

Puya raimondii
<img width="1910" height="873" alt="Puya raimondii" src="https://github.com/user-attachments/assets/c76d78b2-22f4-4a96-91c6-c627b6c2ef4d" />

Rock Rose (Cistus
)<img width="1914" height="885" alt="Rock Rose (Cistus)" src="https://github.com/user-attachments/assets/48cd136b-e3ab-401f-8be3-5b2e9a889edf" />

Exported Teachable Machine model files:
https://drive.google.com/drive/folders/1zdY-ALx8qRdRSaVrOZTjzn0rnJXVnzdx?usp=drive_link

Training screenshots:
<img width="1920" height="879" alt="1" src="https://github.com/user-attachments/assets/2cd1b51d-ccff-4d94-b39b-b9b227eb0425" />

Under-the-hood evaluation screenshots:
<img width="1909" height="889" alt="2" src="https://github.com/user-attachments/assets/b69b37d6-a847-4233-8988-dac6440832fa" />

Preview testing screenshots:
<img width="1891" height="879" alt="Azalea" src="https://github.com/user-attachments/assets/ced650c1-f922-492f-9f93-5c12350b1805" />

Reflection Questions:

1. How did the number of images per class affect your model’s accuracy?
   
  -The number of images per class significantly affected the model’s accuracy because having 250 images per plant allowed the model to learn
  different variations such as lighting conditions, viewing angles, and background differences, which improved its ability to generalize
  and reduced overfitting compared to using fewer images.

2. Which plant species were most commonly misclassified and why?

  -The most commonly misclassified species were Monstera and Hostas, as well as Azalea and Camellia, 
  because these plants share similar leaf shapes, flower structures, and color patterns, which made 
  it difficult for the model to distinguish between them based only on visual features.

3. How did changing the epochs, batch size, or learning rate affect the training results?

  -Increasing the number of epochs initially improved model accuracy, but too many epochs led to overfitting, 
  while a moderate batch size of 16 provided stable learning, and a learning rate of 0.001 ensured smooth 
  convergence without causing unstable or fluctuating loss values.

4. What challenges did you encounter during dataset collection and labeling?

  -During dataset collection, challenges included finding 250 high-quality and non-duplicate images per plant
  species, avoiding watermarked or mislabeled images, and collecting enough clear images for rare plants such 
  as Welwitschia mirabilis and Puya raimondii.

8. If you were to improve your model, what specific changes would you make and why?

  -To improve the model, I would increase the number of images per class, apply data augmentation techniques, 
  reduce background noise, and use transfer learning with a pre-trained model to enhance feature extraction 
  and improve classification accuracy.




