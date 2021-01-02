# OCR-using-ML---EE-113DB
EE113DB - UCLA: electrical engineering digital signal processing design
handwritten text to speech using deep learning

Used deep learning to perform optical character recognition on two datasets of increasing difficulty as the capstone project for my B.S. in EE at UCLA.

First the MNIST and then a handwritten names dataset. MNIST was just handwritten digits, the handwritten names dataset had non-cursive names written using all alphabetic characters and required segmentation based on 2-d histograms before chunked images of characters into the deep neural network for classification. Used python to convert final model output to speech using system calls.

93% accuracry on character classification using handwritten names.
98% accuracy on digit classification using MNIST.
