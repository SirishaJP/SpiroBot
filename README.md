# Project : SpiroBot

## What are medicinal plants? 

Medicinal plants contain natural compounds that can have therapeutic effects on the human body. These compounds, such as alkaloids, flavonoids, and terpenes, have been used for centuries to treat various ailments and have been shown to have anti-inflammatory, antioxidant, and antimicrobial properties. The use of medicinal plants can be a natural alternative to conventional pharmaceuticals and can have fewer side effects. However, it's important to note that the use of medicinal plants should be done under the guidance of a healthcare professional to ensure their safety and effectiveness.

## Why do we need to identify them? 

Effective treatment: Correct identification of medicinal plants is crucial to ensure the right plant is used for the right condition, leading to effective treatment.

Safety: Some medicinal plants can be toxic, and accurate identification can prevent their accidental ingestion or application, ensuring safety.

Conservation: Over-harvesting of medicinal plants can lead to their depletion, and accurate identification can help regulate their collection and ensure their conservation.

Standardization: Proper identification of medicinal plants is necessary for standardization in the production of herbal medicines, ensuring their quality, purity, and potency.

Research: Accurate identification of medicinal plants is essential for scientific research and the development of new medicines from natural sources.

## Goal 

A simple CNN Based approach for Identification of Medicinal Plants. 

## Data Collection

With the use of python library Bing-Image-Downloader. Let us download Images of Medicinal Plants namely, Mint, Aleovera, Hibiscus, Lavender,Neem. 

## Annotation & Labeling 

Using Apeer tool, Images are annotated and labeled using plant name. 

## Data Augmentation 

More the data, better the accuracy. Therefore, augmentation technique is used to improve the dataset. The following augmentation methods are applied:
               * ZCA Whitening 
               * Rotate Image in range 0 to 180 degrees
               * Randomly Zoom Images
               * Shift images horizontally
               * Shift images vertically
               * Random Flips
               
## CNN Model Architecture

![cnn](https://user-images.githubusercontent.com/104147973/216021806-bc2fe73e-3683-4501-8424-b0d00b9af58a.png)

## Result 

An accuracy of 0.7514 is acheived. 

#### Note

This project is in the development phase, therefore, I would request for your patience and understanding.

For up-to-date information, follow me on GitHub and blog posts:




## Author
@SirishaJotheeswaranPadmasekhar. 
