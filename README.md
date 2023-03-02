# THE_CHANDRAYAAN_MOON_MAPPING_CHALLENGE

The dataset_prep.ipynb file contains code that was used for preparing the dataset.


1. Run the Model cell. </br>
2. Run the Inference cell. </br>
3. After running the inference cell , follow the example cell. </br>
4. In the example cell, a 2d numpy array which is in low resolution is passed to the final_model. Before passing the array, make sure to apply min-max standardization (to convert the pixel values between 0 and 1) on the image as shown in example. </br>
5. The output is the 32x super resolved image which is in the form of a 2d numpy array. </br>
</br>
Note - The output image dimension will not be exactly 32 times. The input image is truncated so that both the dimensions are multiples of 80 inside the inference model.
</br>
Models state dictionaries for both stages of the model are provided in the same folder as the notebook.
