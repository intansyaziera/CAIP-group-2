# Parking Lot Occupancy Detection

This is a Parking Lot Occupancy Detection project and developed with Java using the [Deeplearning4j](https://github.com/eclipse/deeplearning4j) library. The project aims to detect parking lot by showing it using webcam.

## Objectives

1. To show the proof-of-concept of the effectiveness of Deep Learning model can be a baseline to evolve a model intended to detect cars in parking lot.
2. To build an intelligent real-time-based parking occupancy detection by detecting the parking lot either free/ busy.
3. To evaluate the performance of the proposed parking occupancy detection model.

## Dataset

1. This project used two classes of image dataset:
- Free
- Busy
2. The dataset has been annotated for testing and training purposes.

3. Sources:
- Self prepared image
- Create annotations by using [Makesense.ai](https://www.makesense.ai/) for labelling image. 

## Methodology 

1. Image Collection : Dataset of 150 images of hot wheel cars manually captured
2. Image Labelling : Annotation on [Makesense.ai](https://www.makesense.ai/) and division of dataset into train and test images
3. Model development : Transfer Learning from the adopted pre-trained Tiny-YOLO model
4. Performance Evaluation : Display the results (Confidence Score of testing dataset)

## Group Members

| Name                                                      | Email                      |
| --------------------------------------------------------- | -------------------------- |
| Nur Syazarin Natasha Binti Abd Aziz                       | syazarinnatasha@gmail.com  |
| Nur Intan Syaziera Binti Mohamad Salleh                   | intansyaziera00@gmail.com  |
