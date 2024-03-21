# Publicly Available Malaria Datasets
This repository is an attempt to list all malaria parasite imaging datasets (blood smears).

Current stage: updated from [tobsecret](https://github.com/tobsecret/Awesome_Malaria_Parasite_Imaging_Datasets)

Contributions welcome! Please report broken links and add new links + citations in the issues or via pull requests!

## Multiple *Plasmodium* species
- [Download data](https://github.com/andrealoddo/MP-IDB-The-Malaria-Parasite-Image-Database-for-Image-Processing-and-Analysis/archive/master.zip) | [git repository](https://github.com/andrealoddo/MP-IDB-The-Malaria-Parasite-Image-Database-for-Image-Processing-and-Analysis)<br>**Data (thin smear):**
Thin smears; 229 images in total, i.e. 122 *Plasmodium falciparum* images, 37 *P. malariae* images, 29 *P. ovale* and 46 *P. vivax* images. Image masks designating parasites are given. The number before the hyphen (e.g. 1305121398 in Falciparum) refers to the same blood smear.
Therefore, each image with the same part number refers to the same patient. <br>Loddo A., Di Ruberto C., Kocher M., Prod’Hom G. (2019) [**MP-IDB: The Malaria Parasite Image Database for Image Processing and Analysis**](https://link.springer.com/chapter/10.1007/978-3-030-13835-6_7) In: Lepore N., Brieva J., Romero E., Racoceanu D., Joskowicz L. (eds) Processing and Analysis of Biomedical Information. SaMBa 2018. Lecture Notes in Computer Science, vol 11379. Springer, Cham

## *Plasmodium falciparum*

 - [Download data](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html) | [website](https://ceb.nlm.nih.gov/repositories/malaria-datasets/) | [git repository](https://github.com/sivaramakrishnan-rajaraman/Deep-Neural-Ensembles-toward-Malaria-Parasite-Detection-in-Thin-Blood-Smear-Images)<br>**Data (thin smear):** 27,558 images of individual cells (infected/ uninfected RBCs) segmented from thin blood smears.<br>Sivaramakrishnan Rajaraman, Sameer K. Antani, Mahdieh Poostchi, Kamolrat Silamut, Md. A. Hossain, Richard J. Maude, Stefan Jaeger, and George R. Thoma. [**Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images.**](https://www.ncbi.nlm.nih.gov/pubmed/29682411), PeerJ., 2018.

 - [Download data](https://data.mendeley.com/datasets/j55fyhtxn4/2) <br>**Data (thin smear):**  A dataset with 38,000 different RBCs (in vitro cultures). All images were labelled five times by five designated annotators from three different research centers for the test set. <br>Mira S. Davidson, Sabrina Yahiya, Jill Chmielewski, Aidan J. O’Donnell, Pratima Gurung, Myriam Jeninga, Parichat Prommana, Dean Andrew, Michaela Petter, Chairat Uthaipibull, Michelle Boyle, George W. Ashdown, Jeffrey D. Dvorin, Sarah E. Reece, Danny W. Wilson,, D. Michael Ando, Michelle Dimon and Jake Baum [**Automated detection and staging of malaria parasites from cytological smears using convolutional neural networks**](https://www.medrxiv.org/content/10.1101/2021.01.26.21250284v1), medRxiv, 2021.

- [Download data *](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html) <br>**Data (thin smear):** Point and polygon datasets. The polygon set consists of 165 blood smear images from 33 patients, with each patient contributing five slides. The point set consists of 800 images from 160 patients. The total number of RBCs is 34,213 and 162,450 in the polygon and point set, respectively  <br> Kassim, Y.M., Palaniappan, K., Yang, F., Poostchi, M., Palaniappan, N., Maude, R.J., Antani, S. and Jaeger, S.,[**Clustering-Based Dual Deep Learning Architecture for Detecting Red Blood Cells in Malaria Diagnostic Smears**](https://ieeexplore.ieee.org/document/9244549), IEEE Journal of Biomedical and Health Informatics ( Volume: 25, Issue: 5, May 2021) 

 - [Download data *](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html) <br>**Data (thick smear):**  1819 images from 150 patients who are infected with parasites. <br> Yang, F., Poostchi, M., Yu, H., Zhou, Z., Silamut, K., Yu, J., Maude, R.J., Jaeger, S. and Antani, S. [**Deep Learning for Smartphone-Based Malaria Parasite Detection in Thick Blood Smears**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8846750), in IEEE Journal of Biomedical and Health Informatics, vol. 24, no. 5, pp. 1427-1438, May 2020, doi: 10.1109/JBHI.2019.2939121.

- [Download data](http://air.ug/downloads/plasmodium-phonecamera.zip) | [website](http://air.ug/microscopy/)<br>**Data (thick smear):** 1182 images of thick smears, parasite bounding boxes given in xml format <br>J.A. Quinn, R. Nakasi, P.K. Mugagga, P. Byanyima, W. Lubega, A. Andama. [**Deep Convolutional Neural Networks for Microscopy-Based Point of Care Diagnostics.**](http://proceedings.mlr.press/v56/Quinn16.pdf) Proceedings of the International Conference on Machine Learning for Health Care, Journal of Machine Learning Research W&C track, Volume 56, 2016.

- [Download data](https://drive.google.com/open?id=1EMJ7dg0TBs34sDWcj7Tj1wozXJC0wtbc)<br>**Data (thin smear):** 655 images of thin smears with bounding boxes around parasites<br>Tek FB, Dempster AG, Kale I, [**Parasite detection and identification for automated thin blood film malaria diagnosis.**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2719653/) Computer Vision and Image Understanding 2010, 114:21-32.

## *Plasmodium vivax*

- [Download data](https://data.broadinstitute.org/bbbc/BBBC041/malaria.zip) | [website](https://data.broadinstitute.org/bbbc/BBBC041/) <br>**Data (thin smear):** 1364 images (~80,000 cells)<br>Hung J, Goodman A, Lopes S, Rangel G, Ravel D, Costa F, Duraisingh M, Marti M, Carpenter A. [**Applying Faster R-CNN for Object Detection on Malaria Images.**](https://arxiv.org/abs/1804.09548), arxiv, 2018.<br> The authors want you to cite this other [paper](https://www.nature.com/articles/nmeth.2083)

\* https://data.lhncbc.nlm.nih.gov/public/Malaria/index.html <br>
