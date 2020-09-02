# neural-image-caption-generation

Image Captioning is the process of generating textual description of an image. It uses both Natural Language Processing and Computer Vision to generate the captions.
We talk about an attention based model that automatically learns to describe the content of images. We describe how we can train this model in a deterministic manner using standard back propagation techniques and stochastically by maximizing a variational lower bound. We also show through visualization how the model is able to automatically learn to fix its gaze on salient objects while generating the corresponding words in the output sequence. We validate the use of attention with state-of-the- art performance on three benchmark datasets: Flickr8k, Flickr30k and MS COCO.

Steps:
1. resize images using resize.py
2. train the model using train.py
3. generate captions using cap_gen.py
