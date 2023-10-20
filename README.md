# Language-detection
# Language Detection for Large Files using XLM-RoBERTa Model

## Overview

This script is designed to perform language detection for large files, especially those that cannot be efficiently processed through limited free APIs such as Google Sheets. Leveraging the powerful XLM-RoBERTa model, it ensures high accuracy and performance, comparable to the 'DETECTLANGUAGE' function in Google Sheets. The script is versatile, catering to various text sources, including audio transcripts, making it an ideal solution for language-sensitive applications that require efficient language identification.

## Features

- Efficiently processes large text files with superior accuracy.
- Handles diverse text sources, including audio transcripts and other language-sensitive data.
- Batch processing implementation to optimize system resources and ensure high performance.
- Conversion of detected language codes to their full names for easy interpretation.
- Output saved in a CSV file for seamless integration into the data analysis workflow.
- Customizable for specific language models and various text data requirements.

## How to Use

1. Ensure that the necessary dependencies are installed, including pandas, transformers, and joblib.
2. Customize the input and output file paths as required for your data.
3. Run the script and wait for the completion message displaying the output file path.

## Use Case

This script is particularly useful in scenarios where language detection is a crucial aspect of data analysis, such as customer feedback analysis, multilingual content processing, and user-generated content moderation.

## Requirements

- Python 3.x
- Pandas
- Transformers
- Joblib

## Note

Ensure that the XLM-RoBERTa model is accessible through the Hugging Face model hub or provide the appropriate model path as necessary.

Feel free to customize the script for specific use cases and integrate it seamlessly into your data processing pipeline.
