Research Question: 

Can Radiomic Features Extracted From Multi-Sequence MRI Predict Clinical Outcomes (i.e. Overall Survival) In Pediatric High-Grade Glioma Patients Using The BraTS-PEDs Dataset. 

Dataset Access Instructions: 

The dataset can be accessed from the TCIA's webpage using this link: https://www.cancerimagingarchive.net/collection/brats-peds/

This dataset is open access and there are no sharing restrictions. 

Map of the Files: 

From this link, we accessed the Images (Training and Validation) which includes the MR sequences and segmentation masks in the NIfTI file formate. We also used the Imaging Metadata in the TSV format for the completion of the project. 

Steps to Open and Run Progress Check: 

## How to Run the Preliminary Analysis

1. Download the BraTS-PEDs metadata TSV file from [The Cancer Imaging Archive (TCIA)](https://www.cancerimagingarchive.net/collection/brats-peds/).
2. Open `preliminary_results.ipynb` in Google Colab using the **Open in Colab** button.
3. Run the first code cell and upload the downloaded metadata TSV file when prompted.
4. Run the remaining cells in order.
5. The notebook will display the dataset summary statistics and generate the preliminary analysis figure.

**Software required:** Google Colab (Python, pandas, NumPy, Matplotlib).

No Google Drive setup or file path modifications are required.
