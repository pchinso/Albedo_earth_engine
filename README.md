# Satellite Albedo Extraction Tool for Google Earth Engine

This repository contains a Jupyter Notebook-based tool, `gee-extract-tool`, for downloading local satellite albedo values from Google Earth Engine collections.

## Description

The `gee-extract-tool` provides a way to perform detailed albedo analysis using satellite imagery. It simplifies the process of fetching specific albedo data points for designated locations, leveraging the extensive collections available in Google Earth Engine.

This tool is ideal for researchers, environmental scientists, and solar energy analysts who need accurate albedo measurements for their studies or projects.

## Key Features

* **Local Data Extraction:** Download satellite albedo values for specific geographic coordinates.
* **Google Earth Engine Integration:** Utilizes the power of Google Earth Engine for accessing vast amounts of satellite data.
* **Detailed Analysis:** Enables in-depth analysis of albedo from satellite images.

## Future Enhancements

The tool can be extended to include the extraction of other important environmental variables, such as:

* Solar Radiation
* Land Cover

## Value Proposition

Using this tool can lead to significant cost savings. For perspective, detailed albedo and solar reports from commercial providers like Solargis can be costly. This tool provides an alternative for obtaining detailed data, with an estimated saving of around $1,000 per location.

## Getting Started

1. **Prerequisites:**

   * An authenticated Google Earth Engine account.
   * A Google account with access to Google Colab.
2. **Usage:**

   * [Open the Jupyter Notebook in Google Colab](https://colab.research.google.com/github/pchinso/Albedo_earth_engine/blob/feature%2Fnotebook-csv-generator/gee_variable_extraction.ipynb).

   ```
   https://colab.research.google.com/github/pchinso/Albedo_earth_engine/blob/feature%2Fnotebook-csv-generator/gee_variable_extraction.ipynb
   ```

   * Authenticate with your Google Earth Engine account when prompted.
   * Follow the instructions within the notebook to specify your locations of interest and execute the data extraction.
   * All processing runs in the cloud - no local installation required.

---

*This tool was implemented with approximately 100 hours of development work.*
