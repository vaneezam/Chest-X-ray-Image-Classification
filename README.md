# Chest-X-ray-Image-Classification
According to the World Health Organization (WHO), pneumonia kills about 2 million children
under 5 years old every year and is consistently estimated as the single leading cause of
childhood mortality (Rudan et al., 2008), killing more children than HIV/AIDS, malaria, and
measles combined (Adegbola, 2012). The WHO reports that nearly all cases (95%) of newonset
childhood clinical pneumonia occur in developing countries, particularly in Southeast
Asia and Africa. Bacterial and viral pathogens are the two leading causes of pneumonia
(Mcluckie, 2009) but require very different forms of management. Bacterial pneumonia
requires urgent referral for immediate antibiotic treatment, while viral pneumonia is treated
with supportive care. Therefore, accurate and timely diagnosis is imperative. One key element
of diagnosis is radiographic data since chest X-rays are routinely obtained as standard of care
and can help differentiate between different types of pneumonia.</br>

The code Implements 2 CNN architectures for classifying Chest X-ray Images into "Normal" or "Pnuemonia" : </br>
1. VGG16 (16 layers)</br>
2. a Custom designed model (5 layers) </br>

The models are compared in terms of Accuracy and Training Time. </br></br>

The code further includes:</br>
##### 1. Grad CAM
##### 2. Transfer Learning
##### 3. Data Augmentation

The accuracies achieved are as below: </br>
|     Model     | Train Accuracy| Test Accuracy |
| ------------- | ------------- | ------------- |
|     VGG16     |      73%      |     62.5%     |
|  Custom Model |      90 %     |     80.4%     |

#### Conclusion
The Custom Model performs better as compared to VGG16 in terms of both accuracy and time, with Custom Model having an
accuracy of 80.4% and training time of 912 seconds whereas, VGG16 having an accuracy
of 62.5% and training time of 1129 seconds. Dropout Layers in Custom Model which
prevent over fitting and less number of layers which eventually means less number of parameters
help in better predictions and Test accuracy within minimum time.
