# Microfiche-Emulator
An unfinished emulator of a fiche reader! Used in a Digital Humanities project [found here](https://hhfinals.dgah.sites.carleton.edu/microfiche/)

## What is it?
  This is a digital version of the Minolta RP605Z model fiche reader. 
  Scroll through the scanned microfiches on the model. Click on different scans of fiche to learn more.
  Zooming of screen is done by clicking the left(zoomIn) and right(zoomOut) of the blue 'zoom' region of the image
      Each image of microfiche is a scan which was made of fiche from Carleton’s collection.
## How I did it
  - Images shown within the screen are thumbnails which redirect to the pdfs they are associated with
    - Using Apple's Automator app, I was able to convert the pdfs I had to jpegs in a fast fashion
  - Used image mapping to create zoom in and zoom out buttons
  - Used CSS grid to create screen 
    - Used JS alongside grid to:
      - resize grid elements and allow for zoom functionality
      - Create cards using a reducer function


## Citation
  - Credit to https://github.com/stowball/jQuery-rwdImageMaps for responsive image maps
 <img width="696" alt="image" src="https://user-images.githubusercontent.com/81717303/158650878-15e2fc4b-bf3b-4955-8c12-8a06a98e8c25.png">









## Currently Unfinished
  Expecting updates with the popup pages of the fiche.
