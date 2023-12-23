# QlikVista

## Overview

By using this template, you may quickly replicate the design from a specific Qlik Sense application and display visualizations in a customized mashup with ease. This approach guarantees a smooth integration by integrating these dynamic representations into a tailored web experience using the Capability API. It makes it possible for Qlik Sense visualizations to be shown within the mashup in an effective and user-centered manner, providing a smooth and interesting user experience.

## Features

- **Dynamic Qlik App Selection**: Admins or users with specific permissions can dynamically choose a Qlik application.
- **Sheet and Object Display**: Sheets and their associated objects are fetched and visualized dynamically based on the selected Qlik app.
- **Visualization Display**: Visualizations from the chosen sheets are displayed within the mashup.
- **Customization Options**: Users can customize application colors, themes, and toggle visibility of sheets/icons.

## Usage

### Installation:

To install and run this Qlik Sense Mashup Template, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/ranvithm/QlikVista.git
   ```
2. Access the Qlik Management Console (QMC).
3. Navigate to "Extensions" on the QMC start page or from the Start Arrow down drop-down menu to access the overview.
4. Click "Import" located in the bottom section.
5. Locate and select the zipped QlikVista extension file, then click "Import" to initiate the import process.

### Create & Configure Mashup:
The following steps outline the process to create a mashup:
1. Open Dev Hub.
2. Create a new mashup.
    1. Click "Add" or "Create new mashup."
    2. Provide a name for the mashup and select the QlikVista template.
    3. Click the 'Create & Edit' button to open the editor tool.
3. Access the "Configuration" section.
4. Choose the Qlik Sense application and configure other settings if needed.
5. Click "Update" to save the changes. 

### Customization:
To customize the application, Qlik theme, colors, show/hide Qlik sheets (pages), and set the icons for sheets, follow these steps:
### 1. Application
1. Open the settings by clicking the profile icon.
2. Choose the desired Qlik application for analysis.
3. Click "Update" to save the changes.
### 2. Theme
1. Access the settings by clicking the profile icon.
2. Select the preferred Qlik theme.
3. Click "Update" to save the changes.
### 3. Colors
1. Open the settings via the profile icon.
2. Update the theme color and active color as required.
3. Click "Update" to save the changes.
### 4. Sheets properties
1. Access settings using the profile icon.
2. Enable sheet properties.
3. Toggle the visibility of sheets based on the checkbox options.
4. Click "Update" to save the changes.
### 4. Icon properties
1. Open the settings via the profile icon.
2. Enable sheet properties.
3. Enable the display of icons.
4. Update icons for text fields. (Currently supports Qlik default icons from Leonardo UI).
5. Click "Update" to save the changes.

## License
This project is licensed under the [MIT License.](https://opensource.org/licenses/MIT)