##  Documentatios_generator: A Documentation Generator for Developers

This repository provides a comprehensive tool for generating documentation from code. It aims to simplify the process of creating user manuals, API documentation, and other technical documents. 

## Main Features

The Documentatios_generator offers the following key features:

- **Code Analysis:**  The tool analyzes source code to extract relevant information, such as class names, function signatures, and variable types.
- **Document Template:**  It provides a customizable template for generating documentation, allowing developers to tailor the output to their specific needs.
- **Automatic Formatting:**  The generator automatically formats the generated documentation, ensuring consistency and readability.
- **Multiple Output Formats:**  It supports various output formats, including HTML, Markdown, and PDF.
- **Hugging Face Spaces Integration: Use the tool directly on the platform without local installation (local execution is also possible).

## Preequisites
- **Python 3.8+
- **All necessary dependencies are listed in the requirements.txt file.

## Installation and Usage

- **Running Locally: Clone the repository git clone https://huggingface.co/spaces/laizacosta/documentation_generator_HF
cd documentation_generator_HF
- **Install the dependencies: pip install -r requirements.txt
- **Run the application: python app.py
- **Access the interface: Open your browser and go to http://localhost:7860 (or the configured port) to use the tool.
- **Using on Hugging Face Spaces: Simply visit the Documentation Generator HF page and use the interface directly in your browser without any local installation.

## License

This project is licensed under the MIT License.

## Technical Details

The Documentatios_generator utilizes a combination of natural language processing (NLP) and machine learning (ML) techniques to extract information from code. 

The NLP component analyzes the code structure and identifies key elements like classes, methods, and variables. The ML component learns from existing documentation to predict the most appropriate descriptions for these elements. 

The tool employs a modular architecture, allowing developers to customize the extraction process and integrate it with their existing development workflows.


## Final Considerations

The Documentatios_generator is a powerful tool for developers who need to generate documentation quickly and efficiently. 
The tool can be further enhanced by incorporating user feedback and improving the ML model's ability to understand complex code structures. In addition, it is a good idea to use examples to train the model (few shot tecnhique). In this scenario it was used zero-shot, given the limitation of tokens and the local sincronicity with the Space. Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.


## Contact

For questions, suggestions, or feedback, please reach out via the author's Hugging Face profile: laizacosta.
