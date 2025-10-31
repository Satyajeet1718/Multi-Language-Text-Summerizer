# Multi-Language Text Summarizer

## Description
A Python-based tool designed to efficiently summarize text in multiple languages, including English, Marathi, and Mixed-Language (English, Marathi, and Hindi) with multiple reduction modes. This project leverages natural language processing techniques to provide accurate and concise summaries while preserving the essential meaning of the original text.

## Features
- **Multi-Language Support**: Summarize text in English, Marathi, and mixed languages (English, Marathi, and Hindi)
- **Multiple Reduction Modes**: Choose from different summarization levels to suit your needs
- **Efficient Processing**: Fast and accurate text summarization
- **Easy to Use**: Simple interface for quick summarization tasks
- **Preserves Context**: Maintains the key information and context of the original text

## Supported Languages
- English
- Marathi (मराठी)
- Hindi (हिंदी)
- Mixed-Language (Combination of English, Marathi, and Hindi)

## Technologies Used
- **Python**: Core programming language
- **Natural Language Processing (NLP)**: Text processing and analysis
- **Jupyter Notebook**: Interactive development environment
- **Machine Learning Libraries**: For advanced text summarization

## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Satyajeet1718/Multi-Language-Text-Summerizer.git
   cd Multi-Language-Text-Summerizer
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Multi_Language_text_summarizer.ipynb` and run the cells

## Usage

### Basic Example
```python
# Import the summarizer
from text_summarizer import summarize

# Your text to summarize
text = "Your long text here..."

# Generate summary
summary = summarize(text, language='english', reduction_mode='medium')
print(summary)
```

### Parameters
- `text`: The input text to summarize
- `language`: Choose from 'english', 'marathi', 'hindi', or 'mixed'
- `reduction_mode`: Select summarization level ('low', 'medium', 'high')

## Project Structure
```
Multi-Language-Text-Summerizer/
│
├── Multi_Language_text_summarizer.ipynb  # Main notebook with implementation
├── README.md                             # Project documentation
└── requirements.txt                      # Python dependencies (if available)
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Make your changes and commit them (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

### Guidelines
- Ensure your code follows Python best practices
- Add comments and documentation for new features
- Test your changes thoroughly
- Update the README if you add new functionality

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Satyajeet**
- GitHub: [@Satyajeet1718](https://github.com/Satyajeet1718)

## Acknowledgments

- Thanks to the open-source NLP community for providing excellent libraries and tools
- Inspired by the need for multi-language text processing solutions

## Contact

For questions, suggestions, or issues, please open an issue on GitHub or contact the repository owner.

---

⭐ If you find this project helpful, please consider giving it a star!
