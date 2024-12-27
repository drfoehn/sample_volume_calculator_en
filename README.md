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
- Warnings issued if the calculated volumes exceed the selected tube sizes.
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
   - A template for the Excel file used for initial data input can be found at [Excel to JSON Converter](https://salk.cadamu.ro/excel_to_json_converter). Download this file and fill it with your laboratory test data.

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
   - The application will display the required plasma volume, dead volume, and the total amount of whole blood/sample needed for each selected test.
   - The required volumes will be displayed, along with warnings if the calculated volumes exceed the selected tube sizes.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 - see the [LICENSE](LICENSE) file for details.

## Disclaimer:
The use of the sample volume calculator application described in this manuscript is at the user's own risk. The authors, contributors, and affiliated institutions cannot be held liable for any errors, omissions, or consequences arising from the use of this tool. The application is provided "as is" without any warranties, express or implied.
Users are responsible for verifying the accuracy of the information provided by the application and should always rely on their professional judgment and institutional guidelines when making clinical decisions. The tool is intended to serve as a guide and should not replace established medical protocols or override the expertise of healthcare professionals.
It is the responsibility of each institution to validate the application's calculations and ensure compliance with their own laboratory standards and practices before implementation. Users should be aware that laboratory requirements and test specifications may vary between institutions and over time.
By using this application, you acknowledge that you have read and understood this disclaimer and agree to use the tool at your own discretion and risk.

## Acknowledgments
- Thanks to all contributors and users for their support and feedback.
