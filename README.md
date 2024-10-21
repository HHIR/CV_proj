# Custom YOLOv8 for Object Detection

This project, completed as part of the Computer Vision course at Sapienza University in 2024, modifies YOLOv8 for faster object detection using the CLEVR-Hans dataset. We reduced layers and simplified components like **C2f** and **SPPF** to achieve up to 47% faster inference speeds and a model size 88% smaller, with only a minimal drop in accuracy.

The dataset contains objects like cubes, spheres, and cylinders, varying in size, color, and material, providing a challenging task for the model. Training was performed on **Google Colab Pro+** using an **A100 GPU**, and all experiments, models, and outputs were stored in Google Drive.

For more details, you can read the full report [here](./x.pdf).
