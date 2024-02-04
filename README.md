# Weed-Classification-Task-

Weed classification is considered fundamental in identifying and distinguishing plants in agricultural fields. In
more recent literature, machine learning techniques have been advocated to be increasingly more useful in its
precision when detecting and classifying weed and plants alike (Al-Badri, et al., 2022). Detection of weed
plants is an important aspect to consider in an agricultural environment. Put simply, weed plants are not
advantageous and therefore unwanted. Weed plants grow amongst crops and have an adverse impact on a
crop’s productivity as they compete with crops for a significant amount of their limited environmental
resources (for example water and sunlight; Adhikari et al.,2019).


With specific regard to this report, image processing is utilised to tackle the problem of weed
classification. The intention is to build an efficient machine learning classifier. Built upon requisite pre-
processing and varied feature extractions, the model will be able to accurately detect and distinguish the
differentiations between two weeds, Charlock and Cleaver.

Weeds, such as the Charlocks and Cleavers that were used in this report, are a type of vegetation that grows in the incorrect 
location and obstructs the growth of crops therefore reducing a farm’s yield, or productivity. (Hamuda et al., 2016).
Therefore, developing an accurate machine learning classifier that will help identify and detected these weeds, can be used in the
agricultural industry to remove them to increase the efficiency of crop yield. The dataset used in this report
contained a total of 158 images of weeds, divided into two weed population groups, charlock and cleaver (90
and 68 respectively).

From a coding aspect, contextually the files added to this repository include only my developed and refined pipelines, not the originally proposed pipelines. 
The improved pipelines focused on extending my original pipelines and/or rectifying errors where necessary. 
In doing so a critical evaluation between the original and newly developed pipelines could be formed.

The following adaptions were made to my original pipelines to produce the following ML image classifiers: 

- Extended LGR pipeline (PLT, RGB & HCD+ Hyper tuning parameters)
- Extended LGR pipeline (Power law transform, RGB + Hyper tuning parameters)
- Extended LGR pipeline (Power law transform, HCD + Hyper tuning parameters)
- Improved SVM pipeline (Adaptive thresholding, RGB + Hyper tuning parameters)
- Additional pipeline 1 DT (Hough transform, RGB + Hyper tuning parameters)
- Additional pipeline 2 KNN (Sharpening, Brightness Normalization + SIFT)
- Additional pipeline RF (Sharpening, Brightness Normalization + SIFT)
 
