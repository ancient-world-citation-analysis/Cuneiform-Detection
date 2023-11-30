# Cuneiform-Detection
This repository primarily focuses on the detection and deciphering of Cuneiform languages using machine learning models and natural language processing (NLP) techniques.

## Project Overview

The primary goal of this project is to accurately translate the Cuneiform language, ensuring the preservation of its original meaning, into contemporary languages.
We are employing a comprehensive range of data science techniques, including text classification and advanced natural language processing (NLP) methods such as dependency parsing.
These techniques are pivotal in understanding and interpreting the complex structure of the Cuneiform language. Our methodology involves a systematic data-gathering process.
We utilize a rule-based approach to meticulously segment text from Cuneiform texts, moving from the page level to word and sentence levels. 
This structured approach is essential for the accurate processing and analysis of ancient language data. The overarching aim is to construct dependency parsers for Cuneiform and 
other underrepresented languages. To achieve this, we are leveraging Large Language Models (LLMs), which are highly effective in various linguistic tasks. These models enable us 
to delve deeper into the linguistic nuances of Cuneiform and similar low-resource languages, facilitating a better understanding and more accurate translations into modern languages.

### Data Overview

**Data Structure:**
- The data for this project is meticulously organized and stored in Google Drive. It encompasses over 13,000 files, primarily structured at the page level and categorized based on different books.
- The majority of our data sources are secondary resources. These resources are particularly diverse, containing words from various languages, which adds to the complexity and richness of the dataset.

**Data Challenges:**
- One of the significant challenges we face in this project is the transformation of raw data into a structured format suitable for detailed linguistic analysis. Given the vastness and diversity of the data,
- this process is crucial for ensuring the accuracy and efficacy of our analysis.
- The multi-language nature of the sources necessitates a careful and nuanced approach to data processing to maintain the integrity and context of the original texts.

**Data Analysis Techniques:**
- **Language Detection:** An essential component of our data analysis involves the identification of languages within the texts. This step is critical in understanding the context and meaning of the words in our dataset.
- **Lemmatization:** To facilitate accurate language processing, we employ lemmatization techniques. This helps in reducing words to their base or dictionary form, which is vital for analyzing ancient languages.
- **Computational Analysis:** Our approach includes computational methods to correctly identify and interpret the linguistic structures in the Cuneiform texts.
- **Conversion of Data:** Utilizing the `words.ipynb` notebook, we successfully convert data from page level to word level. This granular level of data processing allows for a more detailed and nuanced analysis.
- **Sentence Segmentation:** Currently, we are segmenting the text into sentences using the `sentences_strict.ipynb` notebook. This segmentation is a critical step in preparing the data for dependency parsing and further linguistic analysis.

The data structure and processing techniques in this project are designed to tackle the unique challenges of working with ancient texts, particularly in the context of low-resource languages like Cuneiform. 
Through these efforts, we aim to construct a comprehensive language model that can effectively translate and interpret these ancient scripts.

### Methodology
### Methodology for the Cuneiform Language System Project

The methodology of the "Building a Language Model for the Cuneiform Language System" project is multi-faceted, incorporating various data science and natural language processing (NLP) techniques to analyze and interpret the Cuneiform language.

**1. Data Collection and Organization:**
   - The project starts with collecting a vast array of Cuneiform texts, stored as over 13,000 files in Google Drive. The data, primarily secondary resources, includes texts in multiple languages.
   - The raw data is organized at the page level, categorically based on books, which sets the foundation for subsequent processing.

**2. Data Transformation:**
   - A key step is transforming the raw data into a structured format. This involves converting texts from page level to word level using the `words.ipynb` notebook.
   - We also implemented methods to correct the misprinted words from the raw data to increase the overall accuracy of the text.

**3. Language Detection and Lemmatization:**
   - Since the raw data mainly consists of secondary resources, Language detection is employed to identify the various languages present in the texts. We have developed `language_detect.ipynb` to identify the language within the text.
   - Lemmatization is applied to bring words to their base or dictionary form. This process aids in the standardization of data, especially important for ancient languages.

**4. Sentence Segmentation:**
  -  Sentence segmentation is then conducted using `sentences_strict.ipynb`, transitioning the data from word level to sentence level, crucial for detailed linguistic analysis.
  - We have implemented the rule-based approach to segment the text from page level to sentence level for later translation. We still want to use machine learning models such Hidden Markov Model or Neural Network Model to increase the accuracy. 

**5. Dependency Parsing:**
   - The project aims to construct dependency parsers for Cuneiform and other low-resource languages. This involves developing algorithms to analyze the grammatical structure and relationships between words in sentences.
   - The use of Large Language Models (LLMs) like BERT and other advanced NLP tools is a crucial aspect of this process, providing the capability to understand complex linguistic patterns.

**5. Computational Analysis:**
   - Computational analysis is utilized to identify the correct linguistic structures within the Cuneiform texts. This step involves analyzing the syntax and semantics of the language, supported by the models and algorithms developed.

**6. Iterative Refinement and Evaluation:**
   - Evaluate the accuracy of sentence translations against original versions by utilizing metrics such as Recall, Precision, and F-1 Score for validation.
   - The models and methods are continually refined and evaluated to improve accuracy and efficacy. This involves frequent testing and adjustments based on the analysis outcomes.

By employing these methods, the project endeavors to create a comprehensive language model that can accurately translate and interpret Cuneiform texts. The methodology reflects an
innovative blend of traditional linguistics and modern data science, aimed at unlocking the secrets of one of the world's oldest written languages.

## Conclusion
By integrating traditional NLP techniques with advanced language models, this project aims to significantly contribute to the understanding of Cuneiform languages. Our approach balances the use of 
rule-based methods with the innovative application of machine learning, opening new avenues in the field of historical linguistics and ancient language analysis.
