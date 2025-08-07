# Stable Medical Diffusion
Stable Diffusion-Based Text-to-Image Generation for Medical Applications



## Dataset (IU Chest X-ray)

This dataset is curated from the **Indiana University Chest X-ray Collection**, provided by the **U.S. National Library of Medicine (NLM)**. It contains frontal chest X-ray images accompanied by detailed radiology reports in XML format. It is suitable for research in medical image analysis, report generation, and multimodal learning tasks such as **text-to-image generation** using diffusion models (e.g., Stable Diffusion).


### Dataset Content

- Chest X-ray images (PNG and DICOM formats)
- Associated radiology reports in XML
- Optional: Radiology vocabulary mapping (Excel)

### Download Instructions

Use the following bash commands to download all parts of the dataset into a folder called `dataset`.

```bash
cd ./dataset

# Download PNG images
wget https://openi.nlm.nih.gov/imgs/collections/NLMCXR_png.tgz

# Download DICOM images
wget https://openi.nlm.nih.gov/imgs/collections/NLM-MEDLINE/NLM-MEDLINE-DICOM.zip

# Download XML reports
wget https://openi.nlm.nih.gov/xml

# (Optional) Download vocabulary mapping
wget https://openi.nlm.nih.gov/radiology_vocabulary_final.xlsx
```
