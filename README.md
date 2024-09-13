# Classification of histopathological images
This repository contains my work on a data challenge as part of my specialized master's program at Télécom Paris.

For this data challenge, we worked on histopathological images. The dataset consists of microscopic images of breast tumor tissue collected from several patients. These images have the following properties: 700x460 pixels, 3-channel RGB, 8-bit depth in each channel, PNG format.

We have two subfolders :
<br>● <b>Train :</b> contains a set of training images with labels.
<br>● <b>Test :</b> contains a set of images with no available labels.

These images correspond to samples of breast tumors that are either benign or malignant. Among malginants, we can also distinguish between different types of tumors. For this data challenge, we will be evaluated on the prediction of the type of tumors (8 possible classes).

<i>The jupyter notebook contains some plotly graphs. The issue is that github performs a static render of the notebooks and it doesn't include the embedded HTML/JavaScript that makes up a plotly graph. One nice option is to paste the link to the GitHub Jupyter notebook into http://nbviewer.jupyter.org/ in order to render these graphs.</i>
