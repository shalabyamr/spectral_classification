# Spectral Classification of Land Surface Types Using Landsat 7 Satellite Imagery

This project focuses on the spectral classification of land surface types in the Toronto area using Landsat 7 satellite imagery, specifically analyzing Band 2 and Band 4 data.

## Project Overview

The repository contains:

- **Data**: Satellite images of Toronto in Band 2 and Band 4.
- **Python Scripts**: Code for processing and classifying the spectral data.
- **Output**: Results of the classification process.

## Data

The input data consists of Landsat 7 images:

- **Toronto Band 2**: Captures visible green light, useful for assessing plant vigor.
- **Toronto Band 4**: Captures near-infrared light, effective for analyzing vegetation and water bodies.

## Methodology

1. **Preprocessing**: The satellite images are preprocessed to correct for atmospheric effects and sensor anomalies.
2. **Classification**: Using spectral signatures, land surface types are classified into categories such as vegetation, water, and urban areas.
3. **Output Generation**: The classification results are saved for visualization and analysis.

## Results

The output includes classified images highlighting different land surface types based on their spectral characteristics in Band 2 and Band 4.

## Usage

To replicate the analysis:

1. Clone the repository:
   ```bash
   git clone https://github.com/shalabyamr/spectral_classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd spectral_classification
   ```
3. Ensure you have the necessary Python libraries installed (e.g., NumPy, GDAL, Matplotlib).
4. Run the Python scripts in the `Python` directory to process the data and generate classification outputs.

## Dependencies

- Python 3.x
- NumPy
- GDAL
- Matplotlib

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License.
