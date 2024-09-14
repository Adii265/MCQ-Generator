****MCQ Generator****

**Overview**

This project performs text summarization and generates multiple-choice questions (MCQs) based on extracted keywords from the summarized text. 
The process involves:
1. **Reading and Summarizing the Text:** Using the Summarizer model to condense a given text.
2. **Extracting Keywords:** Identifying key terms from the original text.
3. **Mapping Keywords to Sentences:** Linking extracted keywords to sentences in the summarized text.
4. **Generating Distractors:** Creating distractors for MCQs using WordNet and ConceptNet.
5. **Creating MCQs:** Compiling MCQs with a correct answer and distractors into a text file.

**Prerequisites**
1. Python 3.x
2. transformers library
3. nltk library
4. pke library
5. flashtext library
6. requests library
7. pywsd library

**Files**
1. Text2.txt: The input text file to be summarized and analyzed.
2. MCQS1.txt: The output file containing the generated MCQs.


**Contact**
For questions or feedback, please reach out to aditiagrawal267@gmail.com
