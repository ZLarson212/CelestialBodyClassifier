In this project, we will be training and testing several models to predict whether an observed object is a star, galaxy, or quasar.

**Data**

We will be using data collected by the Sloan Digital Sky Survey that has been pre-cleaned and normalized. It includes a table of 10,000 observed objects, for each of which we have an identifying label and the following features:
- ra : Right Ascension
- dec : Declination
- redshift

We also have the magnitude of each object in the following optical filter bands (wavelengths of emitted light):
- u : Ultraviolet
- g : Green
- r : Red
- i : Near Infrared
- z : Infrared

Each model will use these data to predict a corrseponding label: 0 (Star), 1 (Galaxy), 2 (Quasar)

**Models**

- Logistic Regression (PyTorch)
- Dense Neural Network (PyTorch)
- Principal Component Analysis (SciKit Learn)
- Support-Vector Machine (SciKit Learn)
- Violin Plots (Pandas/Seaborn)

**Result**

Support-vector machine was the most successful, with 95% accuracy. The deep neural network outperformed logistic regression 89% accuracy to 79%. And the violin plots reinforced the result of principal component analysis, which was that quasars are most easily distinguishable while stars and galaxies are more similar.

**Further Reading**

If you are curious about any of these topics, I encourage you to check out these links:

- [SDSS](http://www.sdss3.org/dr9/imaging/imaging_basics.php)
- [Right Ascension](https://en.wikipedia.org/wiki/Right_ascension)
- [Declination](https://en.wikipedia.org/wiki/Declination)
- [Redshift](https://en.wikipedia.org/wiki/Redshift)
- [Optical Bands](http://skyserver.sdss.org/dr1/en/proj/advanced/color/sdssfilters.asp)

Thank you for reading me!
