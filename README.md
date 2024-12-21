# Sample Volume Calculator

## Overview
The Sample Volume Calculator is a web application designed to assist laboratory professionals in calculating the required sample volumes for various laboratory tests. The application allows users to input test data, including hematocrit values, and provides calculated results based on the input data.

## Features
- User-friendly interface for selecting laboratory tests.
- Dynamic calculation of required sample volumes based on user input.
- Ability to display results for different tube types, including Heparin, Serum, EDTA, Urine, and CSF.
- Consideration of hematocrit values for Heparin and Serum tubes while calculating required sample volumes.
- Calculation of total sample volume and highest dead volume for each tube type.
- Addition of a safety margin of 250µl for all tube types except for CSF analyses.
- Warnings issued if the calculated volumes for Urine and EDTA exceed the selected tube sizes.
- Integration with an Excel template for easy data input.

## Getting Started

### Prerequisites
- A web browser (Chrome, Firefox, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (optional, for customization)

### Local Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/sample-volume-calculator.git
   cd sample-volume-calculator
   ```

2. **Open the Application**
   - Open `sample_volume_calculator.html` in your web browser to run the application locally.

3. **Download the Excel Template**
   - A template for the Excel file used for initial data input can be found in the repository as `template_en.xlsx`. Download this file and fill it with your laboratory test data.

4. **Convert Excel to JSON**
   - After filling in the Excel template, you can convert it into JSON format using another one of my applications available at [Excel to JSON Converter](https://salk.cadamu.ro/excel_to_json_converter).

### Using the Web App
- Navigate to the deployed web app URL (if hosted) to access the Sample Volume Calculator.
- Follow the same steps as above to input data and perform calculations.

## How to Use the Application
1. **Input Data**
   - Use the provided Excel template to input your laboratory test data.
   - Ensure that the data is filled out correctly according to the template structure.

2. **Calculate Sample Volume**
   - Enter the required parameters, such as hematocrit values, in the web application.
   - Select the relevant tests and click the "Calculate Sample Volume" button to view the results.

3. **View Results**
   - The application will display the required plasma volume, dead volume, and the total amount of whole blood needed for each selected test.
   - The required volumes for Urine, EDTA, and CSF samples will be displayed, along with warnings if the calculated volumes exceed the selected tube sizes for Urine and EDTA.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to all contributors and users for their support and feedback.