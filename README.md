## **Streetscapes at Scale: Mapping Platform APIs as a Tool to Sample Space**

This project focuses on using the Google Street View API to collect and analyze streetscape images from various regions. The project consists of three Jupyter notebooks, each designed for specific analysis purposes. Through this tutorial, you will learn how to effectively utilize the Google Static Street View API to analyze urban environments.




## Project Structure

The project is organized into three main folders. Each folder contains one Jupyter notebook file specific to a different aspect of the sampling Street View images, along with any necessary files (such as CSVs, shapefiles, etc.) needed for the tutorial. Additionally, the folders also store the output files generated when running the notebooks.

### `1A.StreetViewStreetscapeCapture`

This folder contains the first notebook (`StreetViewStreetscapeCapture.ipynb`) of this tutorial, which demonstrates the basic method of collecting streetscape images using the Google Static Street View API. You can obtain Street View images of specific location(s) through API calls and combine them with Python's data processing and visualization tools for analysis.

### `1B.MapillaryStreetscapeCapture`

This folder contains the `MapillaryStreetscapeCapture.ipynb` notebook, which replicates the basic method of collecting streetscape images demonstrated in `1A.StreetViewStreetscapeCapture`, but using the free Mapillary API instead of the Google Static Street View API.

### `2.LocationBasedSampling`

This folder contains the `LocationBasedSampling.ipynb` notebook, which covers how to collect Street View images based on specific locations, using the 'Text Search' function of Google Places API. This approach allows users to specify location queries, such as place names or types, and retrieve corresponding Street View images for those locations.

### `3.RegionBasedSampling`

This folder contains the `RegionBasedSampling.ipynb` notebook, which explains how to collect and analyze images based on a designated region. We use a shapefile, which is a widely used geospatial vector data format that contains geometry data. Using a shapefile, you can collect Street View images from randomly sampled points within a specified area. Additionally, you can tessellate the specified area (divide the area into smaller cells) as needed for more detailed analysis.




## Requirements

This project relies on the following Python packages:

- **numpy**: 1.26.4
- **pandas**: 2.1.4
- **matplotlib**: 3.7.1
- **requests**: 2.32.3
- **json**: 2.0.9
- **Pillow**: 9.4.0
- **geopandas**: 0.14.4
- **shapely**: 2.0.5
- **h3**: 3.7.7
- **s2sphere**: 0.2.5



## Running on Google Colab

This tutorial was written in a Google Colab environment. To replicate the same environment, open and run the notebooks in Google Colab. The necessary libraries and their specific versions are listed in the [Requirements](#requirements) section. It is recommended to use the specified library versions to avoid unexpected behavior.

### 1. Downloading the Repository and Uploading to Google Drive:

- Go to the GitHub repository where the project is hosted.
- Click on the `Code` button (usually a green button near the top right) and select `Download ZIP`.
- Once the ZIP file is downloaded, **extract** its contents to a folder on your local computer.
- Open Google Drive in your web browser.
- Click on the `+ New` button on the left sidebar and select `New folder` to create a new folder.
- Name the folder appropriately, such as “Street_View_Project”.
- Once the folder is created, navigate to the folder.
- Upload the **extracted folder** (containing all the files and subfolders) from your local computer to this Google Drive folder by either dragging and dropping it into the folder or by clicking the `+ New` button again and selecting `File upload` or `Folder upload`.

### 2. Opening the Jupyter Notebooks in Google Colab:

- Open Google Drive and navigate to the folder where you uploaded the extracted project folder.
- Inside the uploaded folder, locate the specific Jupyter notebook file you want to work with (e.g., `StreetView_Demo.ipynb`).
- Double-click the notebook file to open it in a new Google Colab tab. If it's your first time using Google Colab, you'll need to install it. Right-click the notebook file, select 'Open with', then 'Connect more apps', search for 'Colaboratory', and install it.
- Ensure you are signed in with your Google account to access Google Colab.
- If prompted, authorize Google Colab to access your Google Drive files.


## License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/deed.en). You are free to share, copy, and adapt the material under the terms of this license, as long as you give appropriate credit, provide a link to the license, and indicate if changes were made. If you modify or build upon this work, you must distribute your contributions under the same license.

## Citation

If you use this project in your research or any derivative work, please cite the [associated paper]([https://www.dropbox.com/scl/fi/6bp0h4zuwvpnkxynk3vhg/StreetScapes_SocCog_InPress.pdf?rlkey=kkzgjmf78xrgacqio5hwiz20y&st=ifu10ak5&dl=0](https://guilfordjournals.com/doi/pdf/10.1521/soco.2025.43.3.257)): Camp, N. P., & Jo, E. (2025). Streetscapes at scale: Mapping platform APIs as a tool to sample space. Social Cognition, 43(3), 257-275..
