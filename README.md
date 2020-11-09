# privacy-filter-facial-images
Detects faces in singular or sequential image sets and applies a blur over the identified faces to preserve privacy of uploaded photos.

# python requirements
* opencv2
* mtcnn
* tensorflow
* scikit-image

Requires downloading the WIDERFACE train dataset.

Download the WIDERFACE Training data to `/WIDER_train/*`
Download the WIDERFACE annotations to `/wider_face_split/*`