## Search similar images


This code allows you to search for images that are similar to a given image using ResNet50, a popular deep learning model for image recognition. The script uses PCA (Principal Component Analysis) and Nearest Neighbors algorithm to create a compressed index that enables a fast search for nearest neighbors in the space of image features.

## Prerequisites:

  1) Python 3.x >
  
  2) Lib:
    
    - glob
    - pickle
    - os
    - matplotlib
    - numpy
    - torch
    - tqdm
    - PIL
    - scikit-learn
    - torchvision
  
  
## Usage

1) Clone the repository or copy the code into your local environment.
2) Put your images into the "Data" folder or modify the code accordingly.
3) Run the code in your local environment.
4) Call the "search" function with an image path or index and the number of factors you want to use for PCA decomposition. The output will be a set of similar images to the input image.
  search("ris1.jpg", 500, concl=True)



## Options

The script has several options that you can change:

  - "trained": A boolean value that determines whether to load the pre-trained weights or train the model from scratch. By default, it is set to "True" 
  
  - "emb_filename": The name of the pickle file to save the image embeddings. By default, it is set to "images_weights.pickle"
  
  - "num_images": The number of images to display in the output. By default, it is set to "6"


## Examples  

![Search ](C:\\Users\\Virtus\\Desktop\\Search-similar-images\\ris1.jpg)
