---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank # See https://wowchemy.com/docs/page-builder/
headless: true # This file represents a page section.
weight: 10 # Order that this section will appear.

title: 'X-Data'
subtitle: 'data analysis experiments in Python and R a.k.a. portfolio'

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  background:
    # Apply a background color, gradient, or image.
    #   Uncomment (by removing `#`) an option to apply it.
    #   Choose a light or dark text color by setting `text_color_light`.
    #   Any HTML color name or Hex value is valid.
    #color: black
    #gradient_start: DarkGreen
    #gradient_end: ForestGreen
    image: #hello.jpg # Name of image in `static/media/`.
    image_darken: 0.4
    image_size: cover
    image_position: right
    image_parallax: true
    text_color_light: false
advanced:
  css_style:
  css_class: fullscreen
---

This is an ongoing project of self-study/improvement where I create notebooks
with the techniques I'm learning.

## R
- Soon...

## Python

- **Survival Analysis**: [[Jupyter Notebook](https://nbviewer.org/github/helderc/portfolio/blob/main/survival-analysis/survival-analysis-01.ipynb)] [[GitHub](https://github.com/helderc/portfolio/tree/main/survival-analysis)]
	- *Library*: LifeLines
	- *Methods*: Kaplan-Meier, Weibull, Exponential, LogNormal
	- *Evaluation of covariates*: Weibull and Cox Proportional Hazards models.
###
- **Bee Images Classification**: [[Jupyter Notebook](https://nbviewer.org/github/helderc/portfolio/blob/main/BeeImage/beeimg_hog_pca.ipynb)] [[GitHub](https://github.com/helderc/portfolio/tree/main/BeeImage)]
	- *Features*: HOG and Color pixel intensities (vector size of 31296 elements)
	- *Feature transform*: PCA (the best number of components was analyzed)
	- *Classifier*: SVM (linear kernel, binary classification)
	- *Evaluation*: Accuracy, ROC curve and AUC ROC



## Contact
[{{< icon name="envelope" pack="fas" >}}Email](mailto:heldercro[AT]@gmail[DOT]com)  
