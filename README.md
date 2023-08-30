# Generating_Composite_Photos_with_StyleGAN

Composite a photo of two people using stylegan2.

The requirements are the same as for stylegan2.

We used ├ stylegan2-ffhq-config-f.pkl for the weights.

The file shape_predictor_68_face_landmarks.dat is required.

Preprocess the images using pre_processing.ipynb.

Use projector.ipynb to project the image.

Composite the two projected images using toonify.ipynb.
