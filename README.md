##  Documentation_generator: A Documentation Generator for different audience using LLM

This repository contains a tool designed to automatically generate documentation for your projects. The Documentation Generator scans your source code, extracts docstrings and comments, and creates well-structured documentation. This tool is ideal for developers who want to maintain clear and up-to-date project documentation with minimal manual effort.

## Overview
Maintaining comprehensive documentation can be a challenge—especially in fast-paced development environments. The Documentation Generator streamlines this process by automating the extraction of code comments and docstrings, formatting them into a cohesive and accessible document. Whether you are working on a small project or a large codebase, this tool helps ensure that your documentation is always current and easy to navigate.

## Main Features

The Documentatios_generator offers the following key features:

- **Code Analysis:**  The tool analyzes source code to extract relevant information, such as class names, function signatures, and variable types.
- **Document Template:**  It provides a customizable template for generating documentation, allowing developers to tailor the output to their specific needs.
- **Automatic Formatting:**  The generator automatically formats the generated documentation, ensuring consistency and readability.
- **Hugging Face Spaces Integration: Use the tool directly on the platform without local installation (local execution is also possible).

## Preequisites
- **Python 3.8+
- **All necessary dependencies are listed in the requirements.txt file.

## Technical Details
-  Programming Language: Python
    -  Core Functionality:
    -  Parsing source code files to extract documentation.
    -  Formatting extracted content using user-defined or default templates.
    -  Exporting documentation to the desired format.
-  Dependencies: The project relies on standard Python libraries along with a few additional packages for parsing and formatting. (Refer to requirements.txt if available for a full list.)

## Installation and Usage

- **Running Locally: Clone the repository git clone https://huggingface.co/spaces/laizacosta/documentation_generator_HF
cd documentation_generator_HF
- **Install the dependencies: pip install -r requirements.txt
- **Run the application: python app.py
- **Access the interface: Open your browser and go to http://localhost:7860 (or the configured port) to use the tool.
- **Using on Hugging Face Spaces: Simply visit the Documentation Generator HF page and use the interface directly in your browser without any local installation.

The Documentatios_generator utilizes a combination of natural language processing (NLP) and machine learning (ML) techniques to extract information from code. 

The NLP component analyzes the code structure and identifies key elements like classes, methods, and variables. The ML component learns from existing documentation to predict the most appropriate descriptions for these elements. 


## License

This project is licensed under the MIT License.

## Future Improvements
-  Enhanced Parsing: Incorporate support for additional programming languages and file types.
-  GUI Interface: Develop a user-friendly graphical interface for configuring and running the generator.
-  Advanced Customization: Expand the template system to support more advanced formatting options and themes.
-  Integration Plugins: Create plugins for popular IDEs and code editors to trigger documentation generation on demand.

## Final Considerations

The Documentatios_generator is a powerful tool for developers who need to generate documentation quickly and efficiently. 
The tool can be further enhanced by incorporating user feedback and improving the ML model's ability to understand complex code structures. In addition, it is a good idea to use examples to train the model (few shot tecnhique). In this scenario it was used zero-shot, given the limitation of tokens and the local sincronicity with the Space. Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## About
The Documentation Generator was developed by LaizaCostaa to simplify the process of maintaining project documentation. It serves as a foundation for further enhancements and can be tailored to fit the needs of various development workflows.

## Contact

For questions, suggestions, or feedback, please reach out via the author's Hugging Face profile: laizacosta.
