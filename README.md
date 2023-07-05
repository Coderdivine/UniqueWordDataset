# Unique Word Dataset

This repository contains a Python script for generating a dataset of unique words from a given text corpus. The dataset can be used for various natural language processing (NLP) tasks such as vocabulary analysis, word frequency analysis, and word embedding training.

## Table of Contents

- [Introduction](#introduction)
- [Usage in Google Colab](#usage-in-google-colab)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The **Unique Word Dataset** script is designed to take a text corpus as input and generate a dataset containing unique words present in the corpus. It removes any duplicates and outputs a clean dataset that can be easily processed for further analysis or training purposes.

## Usage in Google Colab

To use the **Unique Word Dataset** script in Google Colab, follow these steps:

1. Open Google Colab in your web browser.

2. Click on `File` > `New Notebook` to create a new notebook.

3. In a code cell, run the following command to clone the repository:
   ```python
   !git clone https://github.com/Coderdivine/UniqueWordDataset.git
   ```

4. Change into the project directory:
   ```python
   %cd UniqueWordDataset
   ```

5. Install the required dependencies:
   ```python
   !pip install -r requirements.txt
   ```

6. Upload your input text corpus file to Google Colab by clicking on the folder icon in the left sidebar, selecting the file, and choosing "Upload".

7. In a code cell, run the following command to generate the unique word dataset:
   ```python
   !python unique_word_dataset.py --input <path_to_input_file> --output <path_to_output_file>
   ```

   Replace `<path_to_input_file>` with the path to your uploaded input file and `<path_to_output_file>` with the desired path to save the unique word dataset file.

8. Once the script finishes running, you can download the generated unique word dataset file from Google Colab by right-clicking on the file in the left sidebar and selecting "Download".

## Example

To generate a unique word dataset from a text corpus file named `corpus.txt` and save it as `unique_words.txt`, you can use the following command:

```python
!python unique_word_dataset.py --input corpus.txt --output unique_words.txt
```

This will generate a file `unique_words.txt` containing all the unique words found in the `corpus.txt` file.

## Contributing

Contributions to this repository are always welcome. If you find any issues or want to add new features, please submit a pull request with your changes. Make sure to follow the existing code style and provide appropriate documentation for the modifications.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes.
