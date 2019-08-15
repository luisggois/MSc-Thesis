# MSc-Thesis

Automatic classification of skin lesions using dermoscopic images

# INTERFACE FOR RESEARCHERS

<img width="1275" alt="preinterface" src="https://user-images.githubusercontent.com/43065679/46265201-31cbdc00-c51c-11e8-9e3b-ebd35bf0e535.png">

When I started this study I wanted to provide an efficient approach to the classification of dermoscopic images, in a way to which doctors would trust my algorithm to the extent of really taking it seriously, and that was my major focus. During this willingness for thriving, I was forced to try several different methods along the steps of the work-flow, some which led to good outcomings and others which did not. Throughout this course in search of the most proficient methods, I came to the conclusion that most of the authors, who tried to achieve a similar screening procedure to mine, also wasted a lot of time and effort investigating which methods suited better their purposes. In that sense, and after some careful thought, I decided that it would be helpful to provide a mutual framework to all of the researchers interested in this field of work, a tool that looks at the bigger picture and might lead the community to faster developments in the area. As a result, the idea was to create a graphical user interface, that would serve as a framework for everyone.

<img width="1274" alt="seginterface" src="https://user-images.githubusercontent.com/43065679/46265223-5cb63000-c51c-11e8-8e9a-782be33394ac.png">

## METHODS

In this work, a methodological approach to the automatic classification of skin lesions in dermoscopy images is presented. Noise reduction is the first step applied, in order to improve the image's illumination parameters, as well as eliminating surrounding hair and additional unwanted artefacts. Secondly, border detection is performed, to differentiate the lesion from the surrounding background skin. Then, a sequence of transformations is applied to each lesion to extract a global set of colour, texture, border and shape attributes, which afterwards are fed into an optimization selection framework, which ranks these attributes according to their importance. To find this optimal feature vector, RelieF and Principal Component Analysis techniques are compared. Lastly, classification is done through the use of three classifiers, namely, Support Vector Machines, Random Forests and Adaptive Boosting.

## RESULTS

The proposed method has been evaluated on a set of 100 dermoscopic images, including benign and melanoma cases. Regarding the optimized selection of features, the RelieF method surpasses Principal Component Analysis as the most effective framework for melanoma diagnosis, and in the end, I use 5 of 36 different discriminating parameters to train and test the models. Among the three used classifiers Adaptive Boosting achieves the best average results for 500 runs, obtaining a sensitivity of 99.9%, and a specificity of 97.9%, for the melanoma class, and an overall accuracy of 98.2% for discriminating between malignant and benign classes.
 
## CONCLUSIONS

The experimental results show promising signs for a future integration of this system on the clinical level, as a complementary system that could be used to screen images and complement doctors decision on whether or not a biopsy is necessary. 
