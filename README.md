# Undergraduate Thesis: Quantum Image Classifier Design with Data Re-uploading Quantum Convolution and Data Re-uploading Classifier Scheme

A repository for finishing my undergraduate thesis titled: <br>
*Quantum Image Classifier Design with Data Re-uploading Quantum Convolution and Data Re-uploading Classifier Scheme*. <br>
Advisors: [Prof. Andriyan Bayu Suksmono M.T., Ph.D.](https://scholar.google.co.id/citations?user=IMH571IAAAAJ&hl=en) and [Ir. Nugraha, Ph.D.](https://scholar.google.co.id/citations?user=fym11QIAAAAJ&hl=id)

![DRQConv Diagram](https://github.com/eraraya-ricardo/quantum_image_classifier/blob/master/DRQConv%201%20diagram.png) <br>
*A flow diagram of the Data Re-uploading Quantum Convolution scheme.*

![Training gif](https://github.com/ericardomuten/quantum_image_classifier/blob/master/Results/train_QConv1.gif) <br>
*An animation showing how the quantum states evolve on the Bloch sphere during training. Every point represents a data point, with blue color shows data points of number 0 and red color shows data points of number 1 in the MNIST dataset. At the start, all the data points got mapped randomly on to a single location in the Bloch sphere, as the circuit parameters are randomly generated. But after several training iteration, we can see that the circuit maps the blue points toward the |0⟩ state and the red points toward the |1⟩ state, indicating that the circuit is now able to differentiate different numbers in the dataset.*

![4 classes](https://github.com/ericardomuten/quantum_image_classifier/blob/master/Results/1a_4classes%20cropped.png) <br>
*For more than 2 classes of classification, we need to separate each class into its own region in the Bloch sphere. To make training easier, we need to make sure that those regions for each class are maximally orthogonal to each other. For example, for 4 classes clasification, we can take the shape of regular tetrahedron as the reference and treat the vertices as the region for each class (with all four vertices touch the surface of the Bloch sphere).*

<!--
<a href="https://ml4sci.org/" target="_blank"><img alt="gsoc@ml4sci" height="200px" src="https://raw.githubusercontent.com/eraraya-ricardo/qcnn-hep/main/assets/gsoc%40ml4sci.jpeg" /></a>
-->

### Abstract
The need for computational power keeps increasing as industry and academia's problems get harder and harder to solve. Applications such as simulation of large quantum systems like molecules or solving large linear systems can be very expensive in computational cost. This has become one of the reasons for quantum computing development, a computational method that employs characteristics and theories of quantum systems for information processing. Quantum computers promise us exponential speed-up for these kinds of problems.

Although quantum computers' development has been growing rapidly in recent years, the theoretical and technological challenges remain a barrier for a large-scale quantum computer. Quantum computers that exist today have severe limitations, such as limited qubits and limited gate operations due to noise in the processes. Variational Quantum Algorithms (VQA) have arisen to be one of the promising strategies in dealing with these limitations. Applications across the fields that employ this strategy have been proposed, including image classification as quantum machine learning applications.

This research proposed a modification scheme of the VQA-based Data Reuploading Classifier (DRC) for MNIST classification. A binary, four-class, and eight-class classification task reached 99.7%, 96.5%, and 86.25% of testing accuracy, respectively, using the Principal Component Analysis (PCA) for dimensionality reduction and Data Re-uploading Classifier with binary representation (DRC-BR) for classification. An improvement in accuracy compared to the previous related VQA works. This research also proposed a DRC-based quantum convolution scheme. Without using PCA, quantum convolution with DRC-BR classifier for binary and four-class classification task achieved 98.9% and 89.5% of testing accuracy, respectively. A respectable result compared to the classical Convolutional Neural Network with the same amount of parameters.


### Table of Contents
**Note**: all contents here are written in Indonesian as required by the university. If you are non-Indonesian but interested in this research and would like to receive a summary in English, please feel free to contact me.
- [Thesis Paper](https://github.com/eraraya-ricardo/quantum_image_classifier/blob/master/13316082_Tugas%20Akhir.pdf)
- [Thesis Defense Presentation](https://github.com/eraraya-ricardo/quantum_image_classifier/blob/master/13316082_Presentasi%20Tugas%20Akhir.pdf)
- [Thesis Poster](https://github.com/eraraya-ricardo/quantum_image_classifier/blob/master/13316082_Poster%20Tugas%20Akhir.pdf)


### Acknowledgment
This thesis project is supported by grants from [Radio Telecommunication and Microwave Laboratory](https://et.stei.itb.ac.id/ltrgm/) under Prof. Andriyan's supervision. Starting from January 2021, this thesis project's affiliation changed to the [Quantum Technology Laboratory](http://qlab.itb.ac.id/index.html), a newly founded laboratory at Bandung Institute of Technology.
