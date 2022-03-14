# phdcsf21m508_project1
Automated Liver cancer detection
Mask R-CNN has been used to segment the liver as well as tumor from Tri phasic CT scans 
For this purpose three different models have been trained. 
First model segments the liver from the CT Scans
Second model segments the liver as well as  tumors from the CT Scans
Third model segments the tumor directly from the CT scans
Segmented livers are further classified into six categories i.e. Hemangiomas, Cysts, Cholangiocarcinoma Hepatocellular carcinoma(HCC), Cirrohsis and Normal liver. 
Among the detected tumors Hemangiomas and Cysts are benign tumors whereas  Cholangiocarcinoma and HCC are the malignant ones. 
Cirrohsis is the condition in which healthy liver tissue is replaced by scar tissue and liver is permanantly impaired. In this condition liver has an irregular external contour 

The repository includes:
1.Jupyter notebooks of the applied Mask R-CNN applied for the segmentation of liver, tumor and both.
2.Jupyter notebooks to visualize the detection of liver and tumor
3.Example of training on dataset
4.Notebook for the classification of segmented liver into its classes
