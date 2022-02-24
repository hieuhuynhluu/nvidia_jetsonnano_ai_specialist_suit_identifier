# nvidia_jetsonnano_ai_specialist_suit_identifier
 This project showcases a classification model that is trained to classify playing cards
 into one of 4 suits: spades, clubs, diamonds, and hearts. It is built on top of
 a pre-trained ResNet-18 CNN (trained on ImageNet), with the last layer being fully connected.
 
 The images in the data set are taken with a USB webcam and one deck of cards was used, with each card being captured in different angles and lighting.

# Requirements
- Docker container: https://catalog.ngc.nvidia.com/orgs/nvidia/teams/dli/containers/dli-nano-ai must be properly set up. Use the latest tag.
- Jetson Nano with USB webcam.

# How to use model
- Download my classification jupyter notebook and add it to the docker container in the classification folder. 
- Download my data set and add it to the data directory in the docker container.
- Run each cell until the interactive window pops up and load my model.
- From here, you can test the model and your own data with the webcam.
