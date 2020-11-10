# privacy-filter-facial-images
Detects faces in singular or sequential image sets and applies a blur over the identified faces to preserve privacy of uploaded photos.

## Before running

1. In the directory, create a folder called `neg_train`. cv2.imwrite will fail silently and not write anything while generating the training data if that folder does not exist.
2. The dataset should be `./WIDER_train/<folder names>`, NOT `./WIDER_train/images/<folder names>`.

# python requirements
* opencv2
* mtcnn
* tensorflow
* scikit-image

Requires downloading the WIDERFACE train dataset.

Download the WIDERFACE Training data to `/WIDER_train/*`
Download the WIDERFACE annotations to `/wider_face_split/*`