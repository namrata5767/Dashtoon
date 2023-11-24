# Dashtoon
Generative AI

Neural Style Transfer for Artistic Adaptation

1. Model Architecture

In this assignment, I have designed a neural network architecture inspired by Convolutional Neural Networks (CNN) to learn features that represent an artist's style. The model utilizes convolutional layers to capture both content and style information from input images, drawing from neural style transfer techniques.

2. Training

Dataset
The training dataset comprises artworks from various artists, obtained from [insert dataset source]. This diverse collection serves as the foundation for training the model.

Link: style images- https://www.kaggle.com/datasets/czkaiweb/subwikiarts?select=imgs
content images- provided


Data Preprocessing
Images in the dataset undergo standard preprocessing steps, including resizing to a common dimension, normalization of pixel values, and data augmentation to enhance model generalization.

Training Procedure
To evaluate the model's performance effectively, the dataset is split into training, validation, and test sets. The model is trained using a composite loss function that considers both content preservation and style emulation. The training process involves optimizing the model's parameters to minimize this combined loss.

3. Style Adaptation

The style adaptation algorithm is developed to transfer learned style features to new artworks while retaining the original content. This involves applying the trained model to new images, extracting style features, and integrating them with the content features of the original artwork.

4. Evaluation

Criteria
Evaluation of the style transfer effectiveness is based on the following criteria:

Stylistic Accuracy: Assessing how well the model captures and applies the stylistic features of the selected artist.
Content Preservation: Examining the extent to which the original content is maintained during style transfer.
Visual Appeal: Providing a subjective assessment of the visual quality and aesthetic appeal of the adapted artwork.
Evaluation Methodology
The model's performance is assessed using a test set comprising artworks not seen during training. Human evaluators will offer feedback on the mentioned criteria, and quantitative metrics like Structural Similarity Index (SSI) and Mean Squared Error (MSE) will be employed for objective evaluation.

Conclusion

This project aims to create an adaptive neural style transfer model capable of transforming original artworks to resemble the aesthetic of various artists. The model undergoes thorough training, and its performance is evaluated through a combination of quantitative and qualitative measures. The primary objective is to generate stylized artworks that seamlessly blend the content of the original with the distinctive style of the chosen artist.
