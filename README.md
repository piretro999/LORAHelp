# LoraHelp

LoraHelp is a comprehensive Python script designed for automated file management and processing in diverse environments such as business and research. It supports multiple file formats and integrates advanced functionalities like speech recognition, handling of compressed archives, and detailed output customization.

## Features

- **Multiple File Types Support:**
  - Handles text files, PDFs, Word documents, PowerPoint presentations, Excel spreadsheets, and CSV files.
  - Processes ePub and HTML files by removing HTML tags and cleaning up text.
  - Manages audio (MP3, WAV, M4A) and video files (MP4, AVI, MOV, MKV, MPEG, MPG, 3GP), including speech-to-text functionality for extracting text from audiovisual content.

- **Multilingual Speech Recognition:**
  - Incorporates Google Speech Recognition with a focus on Italian language for enhanced accuracy in recognizing spoken content in Italian audio files.

- **Archive Handling:**
  - Extracts and processes supported file types from ZIP archives.

- **Advanced Configuration:**
  - Allows users to define input and output directories, manage lists of directories to ignore, and choose whether to process subdirectories.

- **Customizable Output:**
  - Saves processed file results into separate text files, annotating the original file path for traceability.

- **Robust Error Handling:**
  - Comprehensive error management to handle issues such as corrupted files, unsupported formats, or access errors.

## Installation

To get started with LoraHelp, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/LoraHelp.git
```

Ensure that you have Python installed on your system. The script requires the following packages:
- PyPDF2
- PyMuPDF (fitz)
- python-pptx
- moviepy
- SpeechRecognition
- python-docx
- xml.etree.ElementTree
- pydub
- pandas
- ebooklib
- BeautifulSoup4
- zipfile

You can install these packages using pip:

```bash
pip install PyPDF2 pymupdf python-pptx moviepy SpeechRecognition python-docx lxml pydub pandas ebooklib beautifulsoup4
```

## Usage

To use LoraHelp, navigate to the script's directory and run:

```bash
python lora_help.py
```

Make sure to adjust the paths and configurations as needed in the script to match your specific requirements.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

---

You will need to create a LICENSE file in your repository that contains the text of the GNU General Public License v3.0. You can find this text on the official [GNU website](https://www.gnu.org/licenses/gpl-3.0.en.html).

This README provides a clear overview of what your project does and how users can install, configure, and use it. Adjust as necessary to fit more specific details or additional functionalities of your script.
