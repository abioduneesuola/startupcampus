This is a skills assessment task from Startup Campus.

As required, I trained a YOLOv8 model for weapon detection over 16 epochs, with a 640×640 input size, using the best.pt checkpoint for inference. During this project, the main challenge I encountered  was the limited size and diversity of the training dataset, which caused the model to misclassify certain weapon types — for example, predicting knives and handguns as automatic rifles. The dataset lacked variation in lighting, background, angles, and distances, which limited the model’s ability to generalize to real-world cases. For better performance, I recommend getting a larger, more balanced dataset with more samples per class, captured in diverse conditions, and supported by high-quality annotations. Incorporating data augmentation can also possibly improve robustness. While the model performed well on training and validation data, its accuracy on real-world images highlights the need for richer, more representative data. I will also like to say that ethical use of this framework should remain a priority, ensuring the system serves lawful and protective purposes only.

Google Drive link to project files:

https://drive.google.com/drive/folders/1n6okQXaEKe28Mi2wh2n8e0Sgs8DUtXQn?usp=sharing
