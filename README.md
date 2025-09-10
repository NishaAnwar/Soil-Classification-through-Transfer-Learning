# Soil-Classification-through-Transfer-Learning

📘 **Dataset Overview**

Title: Comprehensive Soil Classification Dataset (GAN-Augmented)

Source: AI4A Lab, Manipal University Jaipur, India (Kaggle link
)

# Description:
This project uses the GAN-augmented version of the dataset, which contains over 5,000 images of soil samples generated using Generative Adversarial Networks (GANs). The GAN augmentation helps increase data variability and improves model performance for soil classification tasks.

# 🧾 Dataset Details

File Format: Images (JPEG/PNG)
Number of Files: ~5,000 (GAN-Augmented)
Size: ~514 MB
Primary Soil Types:

Sandy

Clayey

Loamy

Peaty

Saline

Silty

# Organization:
Images are organized in folders by soil type, and each image is labeled with its corresponding soil class for supervised learning.

🔄 Preprocessing Steps Applied

Resizing: All images resized to a uniform dimension (e.g., 224x224 pixels)

Normalization: Pixel values scaled to [0, 1]

Augmentation (Optional): Rotation, flipping, zooming to increase variability

Splitting: Dataset divided into training, validation, and test sets

# 📌 Usage in Project

The GAN-augmented images are used to train a Convolutional Neural Network (CNN) for soil type classification. Using the augmented dataset ensures better generalization and higher prediction accuracy.
