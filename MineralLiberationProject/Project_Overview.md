## Project Overview: Mineral Liberation Prediction

This project develops a Python-based automated image processing pipeline to predict the liberation behavior of chalcopyrite and pyrite minerals from polished section SEM images.

### Motivation

Mineral liberation—the degree to which valuable minerals are physically separated from gangue—is a key factor in optimizing mineral processing operations. Traditional liberation analysis requires fully liberated particles and expensive instrumentation. This project offers a cost-effective alternative by analyzing polished sections directly.

### Methodology

- **Image Preprocessing:** Noise reduction and contrast enhancement using Gaussian filters and adaptive thresholding.
- **Segmentation:** Identification of individual mineral grains via connected component labeling.
- **Quantitative Analysis:** Calculation of grain size distribution and liberation percentages based on exposed grain surface area.
- **Batch Processing:** Automation to handle multiple SEM images consistently.

### Benefits

- Enables early-stage liberation assessment without extensive sample preparation.
- Reduces operator bias through automated, reproducible workflows.
- Supports data-driven process design and optimization in mineral processing.

### Tools Used

- Python 3.8+
- OpenCV, NumPy, Pandas, Matplotlib, Seaborn
- Jupyter Notebook for interactive analysis

---

For more details, refer to the Jupyter notebook and scripts in this repository.
