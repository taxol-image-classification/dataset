# Glioma Cell Microscopy Dataset

This dataset was developed as part of an investigation into the morphological effects of Taxol, a widely used anti-cancer drug, on glioma cells. The study utilized C6 glioma cells — a well-established rat-derived cell line frequently employed in brain cancer research. Originating from chemically induced glial tumors in Wistar rats, these cells serve as a widely accepted in vitro model for glioblastoma. C6 glioma cells exhibit several key characteristics of malignant astrocytes, including high proliferation rates and expression of glial fibrillary acidic protein (GFAP), making them particularly suitable for studying cellular responses to chemotherapeutic agents.

## Image Acquisition

C6 glioma cells were cultured in Kaighn’s modification of Ham’s F-12 medium (F12K) supplemented with 2.5% fetal bovine serum (FBS), 15% horse serum, and 1% Penicillin-Streptomycin. Cells were maintained at 37°C in a humidified atmosphere of 5% CO₂ and 95% air. After seeding into 24-well plates, cells were treated with Taxol (dissolved in dimethyl sulfoxide, DMSO) at final concentrations of:

- 100 μM
- 40 μM
- 20 μM  
- A DMSO-only control group was also included.

Cells were incubated for 72 hours. Some wells were subsequently fixed with paraformaldehyde. Phase contrast microscopy at 20× magnification was used to capture approximately 8 images per well.

## Dataset Composition

The dataset includes the following number of grayscale images per treatment group:

- **Control (DMSO only):** 109 images  
- **20 μM Taxol:** 109 images  
- **40 μM Taxol:** 110 images  
- **100 μM Taxol:** 110 images  

All images are grayscale and saved in `.jpg` format at a resolution of 1600 × 1200 pixels.

## Example Visualization

A combined panel with one representative image from each class is shown below:

![Combined Image](combined_image_png.png)

Each quadrant displays a representative image from the Control, 20 μM, 40 μM, and 100 μM Taxol-treated groups.

## License

This dataset is provided for academic use only. Please cite this repository if you use it in your work.
