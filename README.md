#Model Document Generator
This program is designed to read a CSV file and generate a model document that includes a graph of the data as well as general information and model-specific information.

Installation
This program requires Python 3.7 or higher. You can install the necessary packages by running the following command:

Copy code
pip install pandas plotly
Usage
To use this program, run the following command:

bash
Copy code
python model_document_generator.py [path/to/csv/file]
Replace [path/to/csv/file] with the path to your CSV file.

General Information
The program will prompt you to provide some general information about the model, including:

Name
Author
Date
Description
Model-Specific Information
The program will also prompt you to provide some model-specific information, including:

Independent variable name
Dependent variable name
Model type
Model parameters (if applicable)
Output
The program will generate a model document in HTML format. The document will include:

General information
Model-specific information
Graph of the data using Plotly
License
This program is licensed under the MIT License. See the LICENSE file for more information.
