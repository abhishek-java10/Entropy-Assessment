# Project Name: Custom Named Entity Recognition (NER) for Medical Data

## Overview
This project involves developing a custom Named Entity Recognition (NER) model using spaCy, aimed at extracting specific information from medical text data. The project utilizes spaCy to identify and categorize entities such as medical terms and their corresponding values and units from unstructured text data.

## Project Structure
- `Custom_NER.ipynb`: Jupyter notebook containing the spaCy NER model training and evaluation scripts.
- `0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt`: Sample OCR output of medical data used for model testing.
- `X1.json`: JSON file containing the mappings of medical abbreviations and their synonyms, used for entity normalization in NER.

## How to Use
1. **Setup Environment**:
   - Ensure Python 3.8+ is installed.
   - Install spaCy and other necessary dependencies via pip:
     ```bash
     pip install spacy
     ```

2. **Running the Notebook**:
   - Open `Custom_NER.ipynb` in a Jupyter environment:
     ```bash
     jupyter notebook Custom_NER.ipynb
     ```
   - Execute the cells sequentially to train and test the NER model on the provided text data.

3. **Data Format**:
   - The OCR output text file (`0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt`) should be formatted with clear demarcations of data such as test names, values, and units.
   - The JSON file (`X1.json`) should contain a list of medical abbreviations with their possible full forms or synonyms to assist in entity recognition and normalization.

4. **Modifying the NER Model**:
   - Adjustments to the NER model can be made in the notebook to improve accuracy or to adapt to different types of medical documents.

5. **Output**:
   - The output from the model will be structured data extracted from unstructured text, categorized into test names, values, and units, which can be used for further medical analysis or record-keeping.
   - This output can be further refined by replacing synonym names with abbreviations and selecting the first instances of every abbreviation present. Both of these tasks can be achieved using a simple Python function.

6. **Further Modifications**:
   - Additional cleaning and refinement can be done on the OCR output to improve accuracy.
   - Additional rules can be implemented on the regex output to further clean the training data.
   - Machine learning or deep learning models could be employed to enhance prediction of accurate test names, values, and units.
   - Identifying new patterns from various OCR outputs can enrich the training dataset, further improving the model's robustness.
   - Advanced models such as Large Language Models (LLMs) or other AI technologies could be utilized for better accuracy.
   - As this is my first NLP project and was developed in a learning phase, some Python code can be optimized for better time and space efficiency.

## Conclusion
   - This project demonstrates the potent capabilities of spaCy for custom NER tasks tailored specifically to the medical field. The development and continual refinement of this NER system have the potential to significantly enhance the processing of medical documents, leading to more effective data handling and extraction. The model's flexibility for easy adjustments and scalability proves invaluable for adapting to the dynamic requirements of medical data analysis.

## Important Notes
- Ensure that the paths to the data files (`0ab9800e-bc9a-4388-aaa2-d4fc05e7d111.txt` and `X1.json`) are correctly set in the notebook before running the cells.
- This model is configured for English-language medical data. Modifications may be necessary for processing data in other languages or for specialized medical sub-fields.

## Contact Information
- This is my first project in NER/ER, and I would greatly appreciate any feedback. Please feel free to contact me at abhishek2486teotia@gmail.com.
