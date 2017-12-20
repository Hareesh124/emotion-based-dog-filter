# Adversarial Examples in Computer Vision: Building then Fooling an Emotion-Based Dog Filter

Source code for the tutorial at DigitalOcean, for a dog filter and face authenticator, including utilities used for portions of the tutorial.

created by [Alvin Wan](http://alvinwan.com), December 2017

# Getting Started

If you want to forego the tutorial and just try these applications out:

1. Start by installing [PyTorch](http://pytorch.org).

2. Install all Python dependencies.

```
pip install -r requirements.txt
```

To use the **emotion dog filter**, navigate to to the step 10 directory, and launch the script.

```
cd step_10_emotion_dog_filter
python dog_emotion_mask.py
```

To use the **face authenticator**, you'll need to follow the original article, for the authenticator to work for your face. If, for whatever reason, you'd like to run the face authenticator for *my* face, navigate to the step 11 directory and launch.

```
cd step_11_transfer_learning
python face_authenticate.py
```

