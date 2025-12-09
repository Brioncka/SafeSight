# SafeSight
Welcome to SafeSight, Preventing Accidents with AI-Powered Wildlife Detection

AlexNet Final Project
Presented By: Brioncka Russell
Class: MAP2192 Mathematics Of Data Science
Semester: Fall 20225
Professor: William Hahn


# The Problem
Many lives are lost to unsuspected wildlife and motor vehicle collisions accross The United States and the world as a whole. I was motivated to create something that preserves human life and provides overall benefits to individuals an companies alike.

# The Dataset
Safesight uses a small but focused custom image dataset of dashcam-style scenes. I collected around 320 images from Google Images across two classes: deer and nodeer. After cleaning and loading, the final dataset used for training contains 192 training images and 115 validation images (roughly a 60/40 split), organized into train/deer, train/nodeer, valid/deer, and valid/nodeer.

# Experiments
I conducted several experiments to visualize and understand the dataset. Some of the experiments you will find in my repository range from Batch size and learner rate comparisons to data augmentation and architecture comparison.

# Summary Table
| Chart Type               | Final Filename                    | Folder        |
| ------------------------ | --------------------------------- | ------------- |
| Batch size comparison    | `batch_size_comparison.png`       | assets/images |
| Learning rate comparison | `learning_rate_comparison.png`    | assets/images |
| AlexNet confusion matrix | `confusion_matrix_alexnet.png`    | assets/images |
| ResNet confusion matrix  | `confusion_matrix_resnet.png`     | assets/images |
| ResNet accuracy curve    | `resnet_train_valid_accuracy.png` | assets/images |
| ResNet loss curve        | `resnet_train_valid_loss.png`     | assets/images |


# Key Takeaways
Transfer learning works extremely well - A pretrained AlexNet dramatically outperforms an untrained AlexNet on a small, custom dataset.
Data quality matters - Having clear, on-topic images for each class is crucial for reliable wildlife detection.
Experiment tracking helps - Using Weights & Biases made it easy to compare dozens of runs and clearly see the gap between pretrained and untrained models.

# Google Colab Link
https://colab.research.google.com/drive/1tW3QHN380WdVEltBKYO9OifVpo18hqRk?authuser=2

# Google Slides Link
https://docs.google.com/presentation/d/1UAQDCMdM28KBrx_VfNjvROy9_kzS-zTjeEc-nLbNpVE/edit?slide=id.p1#slide=id.p1

# GitHub Website Link


# W&B Link
https://wandb.ai/brussell2025-florida-atlantic-university/alexnet_map2192_experiments?nw=nwuserbrussell2025

# Poster Link

# Video Presentation Link

