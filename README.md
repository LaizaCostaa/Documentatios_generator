##  Documentation_generator: A Documentation Generator for different audience using LLM

## Overview
Maintaining comprehensive documentation can be a challenge—especially in fast-paced development environments. The Documentation Generator streamlines this process by automating the extraction of code comments and docstrings, formatting them into a cohesive and accessible document. Whether you are working on a small project or a large codebase, this tool helps ensure that your documentation is always current and easy to navigate.

## Main Features

The Documentatios_generator offers the following key features:

- **Code Analysis:**  The tool analyzes source code to extract relevant information, such as class names, function signatures, and variable types.
- **Document Template:**  It provides a customizable template for generating documentation, allowing developers to tailor the output to their specific needs.
- **Automatic Formatting:**  The generator automatically formats the generated documentation, ensuring consistency and readability.
- **Hugging Face Spaces Integration: Use the tool directly on the platform without local installation (local execution is also possible).


## Technical Details
-  Programming Language: Python
    -  Core Functionality:
    -  Parsing source code files to extract documentation.
    -  Formatting extracted content using user-defined or default templates.
    -  Exporting documentation to the desired format.
-  Dependencies: The project relies on standard Python libraries along with a few additional packages for parsing and formatting. 


## Future Improvements
-  Enhanced Parsing: Incorporate support for additional programming languages and file types.
-  GUI Interface: Develop a user-friendly graphical interface for configuring and running the generator.
-  Advanced Customization: Expand the template system to support more advanced formatting options and themes.
-  Integration Plugins: Create plugins for popular IDEs and code editors to trigger documentation generation on demand.

## Final Considerations

The Documentatios_generator is a powerful tool for developers who need to generate documentation quickly and efficiently. 
The tool can be further enhanced by incorporating user feedback and improving the ML model's ability to understand complex code structures. In addition, it is a good idea to use examples to train the model (few shot tecnhique). In this scenario it was used zero-shot, given the limitation of tokens and the local sincronicity with the Space. Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

