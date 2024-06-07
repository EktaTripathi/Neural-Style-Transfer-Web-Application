# Neural-Style-Transfer-Web-Application
This project implements neural style transfer using TensorFlow and TensorFlow Hub, and provides an interactive user interface using Streamlit. The application allows users to upload two images: one as the content image and the other as the style image. The neural network then applies the style from the second image to the first image, creating a stylized version of the content image.

# Features
- Image Upload: Users can upload both a content image and a style image.
- Style Transfer: The application uses a neural network to transfer the style from the style image to the content image.
- Image Display: The original and stylized images are displayed side by side for easy comparison.

# Technologies Used
- Streamlit: For creating the interactive web interface.
- TensorFlow & TensorFlow Hub: For leveraging the pre-trained neural style transfer model.
- Altair: For potential future data visualization enhancements.
- Pillow (PIL): For image processing.

# Screenshots
1. Upload Interface:

- The interface allows users to add a content image and a style image.
- The images are displayed below the upload buttons upon successful upload.

![neural (1)](https://github.com/EktaTripathi/Neural-Style-Transfer-Web-Application/assets/94041887/2a729882-ee0f-4870-a382-e84d70de5706)

2. Uploaded Images:

- Shows the content image (a lion) and the style image (a colorful flower).
  
![neural (2)](https://github.com/EktaTripathi/Neural-Style-Transfer-Web-Application/assets/94041887/3f1e13a6-a6b2-4306-a342-1cc9524cf217)

3. Stylized Output:

- Displays the content image with the style of the colorful flower applied.
  
![neural (3)](https://github.com/EktaTripathi/Neural-Style-Transfer-Web-Application/assets/94041887/d8719dfb-def3-4358-a14c-81c58793116f)

4. Image: The original image of the cat (cat image.jpg).
5. Style Image: The artistic image with the castle and the stylized scenery (animation.jpg).

![neural (4)](https://github.com/EktaTripathi/Neural-Style-Transfer-Web-Application/assets/94041887/48a93ec8-c8a6-461d-9874-7a57b3411a6d)

6. Result: The final output image where the cat from the content image is rendered in the artistic style of the animation image.

![neural (5)](https://github.com/EktaTripathi/Neural-Style-Transfer-Web-Application/assets/94041887/039d60da-cfd6-49b8-bde4-08b4645e9fd4)
