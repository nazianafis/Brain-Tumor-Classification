# Brain-Tumor-Classification

---

Brain tumors account for 85% to 90% of all primary central nervous system tumors around the world, with the highest incidence and mortality belonging to high HDI regions. With some image classification techniques, I was able to train a model which could then not only determine the presence of a tumor from Brain MRI Scan but also classify the tumor into one of the following types: Glioma, Meningioma, Pituitary Tumor.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Results](#results)
4. [Licensing](#licensing)

## Installation <a name="installation"></a>

* The complete dataset is publicly available. You can also find it in mhy GitHub repo [here](https://github.com/nazianafis/Brain-Tumor-Classification/tree/main/Brain-MRI).
* The code can be run in [Google Colab](https://colab.research.google.com/drive/1bpq58g2gohNRtpJlole5JGCU9w0yY8pu) as an Interactive Python Notebook (ipynb). No additional installation is required.

## Project Motivation<a name="motivation"></a>

The Project builds a model that is trained on images of Brain MRI Scans, which it then uses to classify a test image into one of the following four categories : 

* Glioma,
* Meningioma,
* Pituitary Tumor, or
* No Tumor

> **Gliomas:** These are the tumors that occur in the brain and/or spinal cord. Types of glioma include: Astrocytomas, Ependymomas, and Oligodendrogliomas. Gliomas are one of the most common types of primary brain tumors. 
> **Meningiomas:** These are the tumors that arise from the Meninges — the membranes that surround the brain and spinal cord. Most meningiomas grow very slowly, often over many years without causing symptoms. 
> **Pituitary tumors:** These are the tumors that form in the Pituitary — a small gland inside the skull. Most pituitary tumors are often pituitary adenomas, benign growths that do not spread beyond the skull.
> 
![dataset](https://github.com/nazianafis/Brain-Tumor-Classification/blob/main/MRI-images/dataset.png)

I cropped and augmented the images before building, compiling, training, and evaluating the model.

![crop](https://github.com/nazianafis/Brain-Tumor-Classification/blob/main/MRI-images/crop-img.png)

## Results<a name="results"></a>

In the end, I could obtain validate a test image passed through the model.

![validation](https://github.com/nazianafis/Brain-Tumor-Classification/blob/main/MRI-images/valid-img.png)

## Licensing<a name="licensing"></a>

The dataset is available under the Open Database License [ODbL](http://opendatacommons.org/licenses/odbl/1.0/).
Any rights in individual contents of the database are licensed under the [Database Contents License](http://opendatacommons.org/licenses/dbcl/1.0/).
