#  Face Mask Detection (With & Without Mask) :

This project is an end-to-end image classification pipeline to detect whether a person is wearing a face mask or not, using Convolutional Neural Networks (CNN) in TensorFlow/Keras.



##  Dataset :

This dataset was sourced from Kaggle:
**[Face Mask Dataset on Kaggle](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)**

### Summary:

> Face Mask Detection Dataset
> In response to global COVID-19 lockdowns, face masks became mandatory in public spaces. This dataset enables training deep learning models to detect masked and unmasked faces using RGB images.
>
> * Total images: **7,553 RGB images**
> * Two folders:
>
>   * `with_mask/`: 3,725 images
>   * `without_mask/`: 3,828 images
> * Each image is labeled by folder name
> * Trained model achieved:
>
>   * **Training accuracy**: \~94%
>   * **Validation accuracy**: \~96%


## Tools & Technologies

* **Python**
* **TensorFlow / Keras**
* **Matplotlib / Seaborn / NumPy / sklearn**


## Predictions (Sample Visualization)

* The model was tested on random images from both classes
* Images were plotted with:

  * **True label**
  * **Predicted label**
  * **Model confidence score**


## How to Use

1. Download and extract the dataset from Kaggle:
   [https://www.kaggle.com/datasets/omkargurav/face-mask-dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)
2. Upload the zipped data (`data.zip`) with folders `with_mask/` and `without_mask/` inside
3. Run the Colab notebook step-by-step
4. Trained model will predict and visualize results

