# Test_Rohan QGIS Plugin

## Overview

Test_Rohan is a QGIS plugin designed to enhance spatial data management and visualization in QGIS. This plugin allows users to upload and visualize three types of shapefiles (line, point, and polygon), with a user-friendly interface and robust error handling.

## Requirements

- QGIS 3.x (Tested on QGIS 3.16 and above)
- Python 3.x (as bundled with QGIS)
- PyQt5 (bundled with QGIS)
- No additional dependencies required

## Features

- **Upload Spatial Layers:** Upload up to three shapefiles: line, point, and polygon.
- **Duplicate Prevention:** Prevents uploading the same file more than once.
- **Visibility Control:** Show/hide each shapefile layer using a checkbox.
- **Error Handling:** 
  - Displays an error if a file is not selected when required.
  - Shows errors for unsupported file types or duplicate uploads.
- **Layer Visualization:** Visualize uploaded shapefiles directly in QGIS.

## Installation

1. Download the plugin as a `.zip` file.
2. Open QGIS and navigate to `Plugins > Manage and Install Plugins`.
3. Click on the `Install from ZIP` tab.
4. Browse and select the downloaded zip file.
5. Click `Install Plugin`.
6. The plugin will appear in the QGIS Plugins menu.

## Usage

1. Launch the plugin from the QGIS Plugins menu.
2. Use the interface to upload your three shapefiles (line, point, polygon).
3. Toggle the visibility of each layer using the provided checkboxes.
4. If you attempt to upload the same file more than once, an error message will appear.
5. If you try to visualize a layer without selecting a file, an error popup will notify you.

## Sample Input Data

- Download the sample shapefiles (line, point, polygon) from the provided link.

## Error Handling

- **Duplicate File Upload:** The plugin will prevent and notify you if you try to upload the same file again.
- **Missing File Selection:** If you attempt to show a layer without selecting a file, an error popup will appear.
- **General Errors:** Any other errors (e.g., unsupported formats) will be displayed in a popup message.

## Support

For questions or issues, please contact Rohan Patil at rohanpatil4002@gmail.com.
