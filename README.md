# NLP-Powered Comparative Discourse Analysis

## Project Overview
This project performs a comparative discourse analysis on two datasets: project management dissertations and peer-reviewed articles. The analysis uses Halliday's Systemic Functional Linguistics model, focusing on various meta-functions including ideational, interpersonal, and textual aspects. The datasets consist of multiple PDF files, each containing either dissertations or articles, and the analyses are done through natural language processing (NLP) techniques.

## Features
The project provides the following analyses:

1. **Word Count Analysis**: Counts the total number of words in each dataset.
2. **In-Text Citations Analysis**: Extracts and analyzes in-text citations, calculating the number of in-text citations per 200 words.
3. **Content Density Analysis**: Counts the total number of ideas and new concepts presented in each dataset.
4. **Ideational Meta-Function Analysis**: Analyzes different types of processes (material, mental, relational) and counts participants and circumstances.
5. **Interpersonal Meta-Function Analysis**: Analyzes the number of declarative, interrogative, and imperative clauses, as well as modality and pronouns usage.
6. **Textual Meta-Function Analysis**: Analyzes the theme and rheme structure, conjunctions, reference words, substitutions, ellipses, and lexical chains.
7. **Summary Report**: Generates a combined Excel report summarizing all the analyses, with each analysis in its own worksheet.

## Files Included
- **analysis_code.py**: Contains all functions used to analyze the datasets, including the word count, content density, and different meta-function analyses.
- **combined_analysis.xlsx**: The output Excel file that summarizes all the analyses in separate worksheets.
- **datasets**: Folder containing Dataset 1 (Dissertations) and Dataset 2 (Peer-Reviewed Articles) in PDF format.

## Requirements
- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries:
  - `pandas`
  - `PyMuPDF` (`fitz`)
  - `pdfminer.six`
  - `spacy`
  - `pytesseract`
  - `pdf2image`
  - `xlsxwriter`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/nlp-discourse-analysis.git
   cd nlp-discourse-analysis
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the English model for spaCy:
   ```bash
   python -m spacy download en_core_web_sm
   ```

## Usage
1. Place the PDF files in the `datasets` folder.
2. Run the `analysis_code.py` script to analyze the datasets.
3. The analysis results will be saved in the `combined_analysis.xlsx` file, which contains different worksheets for each type of analysis.

## Analysis Summary
The `combined_analysis.xlsx` file includes the following worksheets:
- **Word Count Analysis**: A summary of the total number of words in each dataset.
- **In-Text Citations Analysis**: Total citations and citations per 200 words.
- **Content Density Analysis**: Total number of ideas and new concepts.
- **Ideational Meta-Function Analysis**: Counts of processes, participants, and circumstances.
- **Interpersonal Meta-Function Analysis**: Counts of different clause types, modality, and pronouns.
- **Textual Meta-Function Analysis**: Counts of themes and rhemes, conjunctions, reference words, substitutions, ellipses, and lexical chains.

## Output
The output of the project is a detailed comparative analysis between project management dissertations and peer-reviewed articles, highlighting differences in language use, complexity, and style. The results are saved in an Excel file that can be easily used for visualizing key findings.

## Contributing
Contributions are welcome! If you would like to add features, improve the analysis, or fix issues, feel free to fork this repository and open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions, please reach out at +923045525139

