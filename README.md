# Text-To-Fashion Images: Generating Fashion Images With African Prints.


## Abstract
We explore the generation of fashion images featuring African prints using a fine-tuned version of the RunwayML Stable Diffusion v1-5 model from Hugging face. The study aims to reduce biases in AI-generated content and promote cultural inclusivity within the fashion industry. A curated dataset of 8,005 images, derived from the InFashAIv1 collection by Hacheme and Sayouti is  developed, focusing on African prints and curating corresponding text descriptions. This dataset served as the foundation for fine-tuning the pre-trained model. The model's performance was evaluated using quantitative metrics, including Colour Palette Score, Texture Realism Score, and Structural Similarity Index (SSIM). The findings reveal that the fine-tuned model shows significant improvement in capturing the texture realism of African prints and colour accuracy. However, challenges remain in structural integrity, especially with more complex designs. Qualitative analysis further indicates that while the model effectively represents simpler prints, it struggles with intricate patterns and achieving photo realism. This research contributes to the broader efforts of enhancing cultural diversity in AI-generated fashion, highlighting both the potential and limitations of current generative models. Future work will focus on further refinement of the model and the expansion of the dataset to better capture the richness of African fashion traditional styles.

## Motivation
The primary motivation for this project is to address bias in AI-generated fashion images, particularly the underrepresentation of non-Western styles like African prints. While AI automation enhances creativity and efficiency in fashion design and allows for personalised experiences, it often perpetuates bias due to datasets that feature Western styles. This can limit the visibility of diverse cultural traditions. 
By reducing this bias, AI can generate more inclusive and globally representative fashion images, enriching the industry and promoting cultural appreciation. My passion for fashion research drives this project, which seeks to develop an African-inclusive generative model, advancing the diversity of AI in fashion applications.



Here is a link to my Google Drive containing folders/files  where the dataset used and respective directories for saved model paths can be downloaded and mounted on the user's Google Drive.https:https://drive.google.com/drive/folders/1-1BF1_EKHs-C0yx_NoAaS1nj3VRJ02lv?usp=sharing

## Findings and Future Direction
The fine-tuned model shows improvements in texture realism and capturing the complexity of simpler African prints, but struggles with intricate designs, indicating that bias remains. Fluctuating SSIM values highlight inconsistencies in structural integrity.While the model effectively replicates cultural elements in simpler prints, it lacks consistency and photo-realism in more complex patterns. The inherent randomness in generative AI contributes to these variations, pointing to the need for further refinement.
This research advances the use of AI in promoting cultural diversity in fashion but also emphasizes the need for continued improvements to better capture the richness of diverse fashion traditions.
Included are some snippets of the model's generation to illustrate these findings.

<img width="739" alt="Screenshot 2024-08-09 172526- 5" src="https://github.com/user-attachments/assets/62a8ba96-8209-4377-9a05-4916b812d76d"><img width="191" alt="Screenshot 2024-08-12 095731" src="https://github.com/user-attachments/assets/fb1f4d98-556f-43fe-a0bd-fef6e0e04178"><img width="266" alt="Screenshot 2024-08-12 095645" src="https://github.com/user-attachments/assets/a12f5d44-707b-4d7b-a8df-034a831ab689"><img width="259" alt="Screenshot 2024-08-12 095537" src="https://github.com/user-attachments/assets/6f38e9d9-1721-4e79-ac70-1be9e70854bf">




<img width="249" alt="Screenshot 2024-08-09 172937- 4 1" src="https://github.com/user-attachments/assets/fa0f8680-9869-48e3-b2b0-4874334dbd54">
<img width="249" alt="Screenshot 2024-08-09 172937- 4 1" src="https://github.com/user-attachments/assets/d29946b1-52f5-4a18-aecd-ebc6aa62fcf1">


