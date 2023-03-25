<h1>Model Document Generator</h1>

![image](https://user-images.githubusercontent.com/78321696/227716412-2721e2a2-d4eb-4b35-978f-b8ebf926f33c.png)


![image](https://user-images.githubusercontent.com/78321696/227716417-fcab02f2-266e-4419-9a1a-b50e4160a77c.png)


![image](https://user-images.githubusercontent.com/78321696/227716435-5304f7bf-c0f9-428d-9e5a-7eef7f2f8491.png)

![image](https://user-images.githubusercontent.com/78321696/227716455-407a8a73-e4ec-4970-9453-75980d66e6ae.png)

This program is designed to read a CSV file and generate a model document that includes a graph of the data as well as general information and model-specific information.

<h3>Installation</h3>
This program requires Python 3.7 or higher. You can install the necessary packages by running the following command:

Copy code
```pip install pandas plotly```

<h3>Usage</h3>
To use this program, run the following command:

bash
Copy code
```python model_document_generator.py [path/to/csv/file]```

Replace [path/to/csv/file] with the path to your CSV file.

</h3>General Information</h3>
The program will prompt you to provide some general information about the model, including:


Name
Website
Email
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
