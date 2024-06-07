# Project-on-Using Deep Learning for Early Breast Cancer Detection
The project uses the CBIS-DDSM dataset to develop deep learning models for early breast cancer detection. The project uses high-resolution mammography images and comprehensive annotations to improve diagnostic accuracy. Traditional methods rely on radiologists' expertise, leading to variability in diagnostic accuracy. The Curated Breast Imaging Subset of DDSM (CBIS-DDSM) offers a standardized dataset, enhancing early cancer detection, making diagnostic processes more reliable and accessible. This standardized dataset promotes reproducibility and innovation in medical imaging.

# Descripton
This dataset is jpeg format of the original dataset(163GB). The resolution was kept to the original dataset.

Number of Studies: 6775
Number of Series: 6775
Number of Participants: 1,566(NB)
Number of Images: 10239
Modalities: MG
Image Size (GB): 6(.jpg)
NB: The image data for this collection is structured such that each participant has multiple patient IDs. For example, pat_id 00038 has 10 separate patient IDs which provide information about the scans within the IDs (e.g. Calc-Test_P_00038_LEFT_CC, Calc-Test_P_00038_RIGHT_CC_1) This makes it appear as though there are 6,671 participants according to the DICOM metadata, but there are only 1,566 actual participants in the cohort.

Summary
This CBIS-DDSM (Curated Breast Imaging Subset of DDSM) is an updated and standardized version of the Digital Database for Screening Mammography (DDSM). The DDSM is a database of 2,620 scanned film mammography studies. It contains normal, benign, and malignant cases with verified pathology information. The scale of the database along with ground truth validation makes the DDSM a useful tool in the development and testing of decision support systems. The CBIS-DDSM collection includes a subset of the DDDSM data selected and curated by a trained mammographer. The images have been decompressed and converted to DICOM format. Updated ROI segmentation and bounding boxes, and pathologic diagnosis for training data are also included. A manuscript describing how to use this dataset in detail is available at https://www.nature.com/articles/sdata2017177.

Published research results from work in developing decision support systems in mammography are difficult to replicate due to the lack of a standard evaluation data set; most computer-aided diagnosis (CADx) and detection (CADe) algorithms for breast cancer in mammography are evaluated on private data sets or on unspecified subsets of public databases. Few well-curated public datasets have been provided for the mammography community. These include the DDSM, the Mammographic Imaging Analysis Society (MIAS) database, and the Image Retrieval in Medical Applications (IRMA) project. Although these public data sets are useful, they are limited in terms of data set size and accessibility.

For example, most researchers using the DDSM do not leverage all its images for a variety of historical reasons. When the database was released in 1997, computational resources to process hundreds or thousands of images were not widely available. Additionally, the DDSM images are saved in non-standard compression files that require the use of decompression code that has not been updated or maintained for modern computers. Finally, the ROI annotations for the abnormalities in the DDSM were provided to indicate a general position of lesions, but not a precise segmentation for them. Therefore, many researchers must implement segmentation algorithms for accurate feature extraction. This causes an inability to directly compare the performance of methods or to replicate prior results. The CBIS-DDSM collection addresses that challenge by publicly releasing a curated and standardized version of the DDSM for evaluation of future CADx and CADe systems (sometimes referred to generally as CAD) research in mammography.

Please note that the image data for this collection is structured such that each participant has multiple patient IDs. For example, participant 00038 has 10 separate patient IDs which provide information about the scans within the IDs (e.g. Calc-Test_P_00038_LEFT_CC, Calc-Test_P_00038_RIGHT_CC_1). This makes it appear as though there are 6,671 patients according to the DICOM metadata, but there are only 1,566 actual participants in the cohort.

For scientific inquiries about this dataset, please contact Dr. Daniel Rubin, Department of Biomedical Data Science, Radiology, and Medicine, Stanford University School of Medicine (dlrubin@stanford.edu).
