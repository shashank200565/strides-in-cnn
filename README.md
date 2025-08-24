#CNN Strides Demonstration with MNIST

This project is a small demo to show how strides in Convolutional Neural Networks (CNNs) affect feature extraction and information preservation when processing images.

📌 Overview

Stride is the step size with which a convolution filter (kernel) moves across the input image.

Smaller strides (e.g., 1) → Preserve more spatial information but produce larger feature maps.

Larger strides (e.g., 2) → Reduce the size of the output feature maps (downsampling) but may lose fine-grained details.

In this program, we build CNN models on the MNIST dataset (handwritten digit images) and compare:

stride = 1 → high detail, larger feature maps

stride = 2 → reduced detail, smaller feature maps

We display the model summaries to highlight the difference in output shapes.

⚙️ How to Run

Install TensorFlow/Keras if not already installed:

pip install tensorflow


Run the script:

python cnn_strides_demo.py

📊 Example Output

Model summary with stride=1 (larger intermediate feature maps)

Model summary with stride=2 (smaller intermediate feature maps, faster computation)

🧠 Learning Outcome

This demo helps understand:

The role of stride in CNNs

Trade-off between information preservation and computational efficiency

How stride influences output dimensions in convolutional layers
