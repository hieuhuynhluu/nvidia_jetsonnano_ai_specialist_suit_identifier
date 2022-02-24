# nvidia_jetsonnano_ai_specialist_suit_identifier
 This project showcases a classification model that is trained to classify playing cards
 into one of 4 suits: spades, clubs, diamonds, and hearts. It is built on top of
 a pre-trained ResNet-18 CNN (trained on ImageNet), with the last layer being fully connected.
 
 The images in the data set are taken with a USB webcam and one deck of cards was used, with each card being captured in different angles and lighting.
 
# Problems
 With a preliminary set of data, the model struggled to differetiate hearts from spades due to only a slight difference in appearance. Since the spades is really just a heart with a small detail added, the model found it hard to associate that small detail to spades. But given more data, the model was able to identify each much more accurately.
 
 ![IMG_1052](https://user-images.githubusercontent.com/61090996/155471791-df29a7bd-4a39-4398-b0fa-e4711bd5c0b4.jpg)

 
# Requirements
- Docker container: https://catalog.ngc.nvidia.com/orgs/nvidia/teams/dli/containers/dli-nano-ai must be properly set up. Use the latest tag.
- Jetson Nano with USB webcam.

# How to use model
- Git clone this repo.
- run the notebook.
