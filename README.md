# GTM Country Code & Name Converter

## Description
The **Country Code & Name Converter** is a Google Tag Manager (GTM) custom variable template that enables seamless conversion between country names, Alpha-2 codes, and Alpha-3 codes. The template includes advanced options for handling invalid or unrecognized input.

## Features
- Convert country names to Alpha-2 or Alpha-3 codes.
- Convert Alpha-2 or Alpha-3 codes to full country names.
- Handles invalid input with an optional fallback mechanism.
- Fully configurable via GTM's interface.

## Installation
1. Download the template file (`country-code-name-converter.tpl`) from this repository.
2. Import it into Google Tag Manager:
   - Open GTM and navigate to **Templates**.
   - Click **New** under "Variable Templates" and select **Import**.
   - Upload the `.tpl` file.
3. Configure the template fields and use it in your tags or variables.

## Usage
1. Input a country name, Alpha-2 code, or Alpha-3 code.
2. Select the desired transformation type:
   - Convert to Alpha-2 code
   - Convert to Alpha-3 code
   - Convert to full country name
3. Optionally enable advanced handling for invalid input.
4. Use the output as needed in your GTM container.

## Example
Here's an example of how to configure and use the variable:

### Input
- **Input Value**: `United States`
- **Transformation Type**: Convert to Alpha-2 Code

### Output
- **Result**: `US`

### Another Example
- **Input Value**: `US`
- **Transformation Type**: Convert to Full Country Name

- **Result**: `United States`

### Advanced Option Example
- **Input Value**: `XYZ` (not a valid country name or code)
- **Transformation Type**: Convert to Alpha-3 Code
- **Advanced Option Enabled**: ✅
  
- **Result**: `XYZ` (original input returned)

---

## License
This project is licensed under the [MIT License](LICENSE).

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your changes.

## Author
Created by Jude Nwachukwu Onyejekwe.

Created as part of the [Dumbdata.co](https://dumbdata.co) measurement resource hub to provide you with resources that help simplify measurement.

## Issues
If you encounter any issues or have suggestions, please open an issue in this repository.
