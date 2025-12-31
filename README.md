# Word Count and Non-English Word Detection

## Project Overview
This project analyzes text files to extract words, count their occurrences, and identify non-English words using the SpellChecker library. The script processes the input text and provides insights into both English and non-English word usage.

## Features
- **Word Extraction**: Extracts all words from a specified text file.
- **Word Counting**: Counts the frequency of each extracted word.
- **Non-English Word Detection**: Identifies and counts words that are not recognized as English.
- **Sorted Output**: Displays results sorted by word frequency for better readability.

## Getting Started

### Prerequisites
Before running the script, ensure you have the following installed:
- **Python**: Version 3.x
- **Required Libraries**:
  ```bash
  pip install pyspellchecker
  ```

### File Preparation
1. Place your text files (e.g., `file1.txt` and `file2.txt`) in the project directory.

### Running the Script
To run the script, use the following command in your terminal or command prompt:
```bash
python script.py
```

### Function Descriptions
- **`reading(f_path)`**: Reads the content of the specified text file.
- **`mapping(text)`**: Splits the text into words and maps each word to a count of 1.
- **`reducing(mapped_words)`**: Counts the total occurrences of each word.
- **`finding_non_english_words(text)`**: Identifies non-English words using the `SpellChecker`.

## Output
Upon execution, the script will print:
- A list of all words with their respective counts.
- A list of non-English words along with their counts, sorted in descending order.

## Conclusion
This project serves as a foundational text analysis tool for counting word occurrences and identifying non-English words, facilitating deeper insights into text data for various applications.
