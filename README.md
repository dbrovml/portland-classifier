# PortLand classification: portrait vs landscape

The goal of this mini-project is to carry-out a **simple end-to-end image classification** project. The task is to train a CNN model for classifying an image of an **art painting** as one of the two genres - **portrait** or **landscape**. The input dataset consists of **20 000 images** of each class obtained by scraping the WikiArt art library (code for this can be found [here](https://github.com/dbrovml/my-scrapers/tree/main/wikiart)).

The notebook is structured to mirror a typical modeling workflow:
1. Download and sort input images from Google Drive
2. Split input images into train, validation, and test sets
3. Define image preprocessing and TF datasets
4. Train a baseline CNN model
5. Visually assess the model
6. Tune a pretrained model

The whole project is coded in ``portland.ipynb``.