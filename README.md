# Project Name: Custom Named Entity Recognition (NER) for Medical Data

## Overview
This project involves the development of a custom Named Entity Recognition (NER) model using spaCy, aimed at extracting specific information from medical text data. The project utilizes spaCy to identify and categorize entities such as medical terms and their corresponding values and units from unstructured text data.

## Project Structure
- `Custom_NER.ipynb`: Jupyter notebook containing the spaCy NER model training and evaluation scripts.
- `0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt`: Sample OCR output of medical data used for model testing.
- `X1.json`: JSON file containing the mappings of medical abbreviations and their synonyms, used for entity normalization in NER.

## How to Use
1. **Setup Environment**:
   - Ensure Python 3.8+ is installed.
   - Install spaCy and other dependencies via pip:
     ```bash
     pip install spacy
     ```

2. **Running the Notebook**:
   - Open the `Custom_NER.ipynb` in a Jupyter environment:
     ```bash
     jupyter notebook Custom_NER.ipynb
     ```
   - Execute the cells sequentially to train and test the NER model on the provided text data.

3. **Data Format**:
   - The OCR output text file (`0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt`) should be formatted with clear demarcations of data such as test names, values, and units.
   - Further cleaning can be done on the OCR output, and a machine learning or deep learning model can be trained to predict the accurate test names, values, and units for enhanced accuracy.
   - Additional patterns can also be identified from other OCR outputs to enrich the training dataset.
   - The JSON file (`X1.json`) should contain a list of medical abbreviations with their possible full forms or synonyms to assist in entity recognition and normalization.

4. **Modifying the NER Model**:
   - Adjustments to the NER model can be made in the notebook to improve accuracy or to adapt to different types of medical documents.

5. **Output**:
   - The output from the model will be structured data extracted from the unstructured text, categorized into test names, values, and units, which can be used for further medical analysis or record-keeping.
   - This output can be further refined as per use. For example, synonym names can be replaced with the abbreviations, and first instances of every abbreviation present can be taken. Both of these tasks can be done by a simple Python function.

## Conclusion
   - This project showcases the powerful capabilities of spaCy in custom NER tasks tailored to the medical field. Through the development and refinement of this NER system, significant improvements can be made in processing medical documents, leading to more efficient data handling and extraction. The flexibility of the model allows for easy adjustments and scaling, which can be particularly beneficial in adapting to the evolving needs of medical data analysis.

## Important Notes
- Ensure that the paths to the data files (`0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt` and `X1.json`) are correctly set in the notebook before running the cells.
- This model is configured for English language medical data. Modifications might be necessary for other languages or specialized medical sub-fields.

## Contact Information
- For further inquiries or contributions to the project, please reach out via [Email/GitHub/Twitter].

