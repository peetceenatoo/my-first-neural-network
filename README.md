## Blood Smear Classification

This computer vision challenge aimed to classify peripheral blood smears into eight categories using deep neural networks. 

Blood smear classification is challenging due to high intra-class variability and subtle inter-class differences between cell morphologies.

![Screenshot](images/outlier.png) 

While designing and implementing our solution, we explored:

1. Dataset cleaning and Outlier analysis
2. Data Augmentation
3. Custom Convolutional Neural Networks
4. Hyperparameter Tuning
5. Cross-validation
6. Transfer Learning (ImageNet)
7. Test Time Augmentation

The model performance was evaluated through accuracy on a private test set.

## Libraries

For the implementation, we used TensorFlow Keras. We also used Numpy, Matplotlib and Seaborn for secondary purposes.

## More Info

Refer to the [report](report.pdf) and [notebooks](/notebooks).

## Acknowledgements

I thank my colleagues and friends [Matteo Salari](https://github.com/matteo-salari), [Davide Salonico](https://github.com/DavideSalonico) and [Federica Topazio](https://github.com/federicatopazio) who worked with me on this project.
