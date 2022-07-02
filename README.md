# Playground for CLIP-like models

| Demo  | Colab Link |
| ------------- | ------------- |
| GradCAM Visualization  |  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_GradCAM_Visualization.ipynb)  |
| Naive Zero-shot Detection  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_Patch_Detection.ipynb)  |
| Smarter Zero-shot Detection  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_Zero_shot_Detector.ipynb)  |
| Captcha Solver  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_reCAPTCHA.ipynb) |

If you find this playground useful, consider citing it:

```bibtex
@software{zakka2021clipplayground,
    author = {Zakka, Kevin},
    month = {7},
    title = {{A Playground for CLIP-like Models}},
    url = {https://github.com/kevinzakka/clip_playground},
    version = {0.0.1},
    year = {2021}
}
```

## Changelog

### 2021-07-28

* Better plotting for reCAPTCHA.

### 2021-07-27

* Allow multiple captions in detection query, colon separated.
* Allow the user to resize an image during selective search.
* Tuned the rejection parameters of selective search.
* Minor bugfix in naive patch detector.
