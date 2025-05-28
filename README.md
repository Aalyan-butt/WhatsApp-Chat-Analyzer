# 📲 WhatsApp Chat Analyzer

## 🔄 Overview

**WhatsApp Chat Analyzer** is a powerful tool designed to parse and analyze WhatsApp chat export files. It provides meaningful insights and visualizations based on chat data, such as message counts, activity timelines, word frequency, sentiment analysis, and more. This project helps users gain a deeper understanding of their chat patterns and interactions.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square">
  <img src="https://img.shields.io/badge/NLP-Scikit--learn-yellow?logo=scikit-learn">
  <img src="https://img.shields.io/badge/UI-Streamlit-red?logo=streamlit">
</p>


## 🌟 Features

* 🗃️ Import WhatsApp chat export files (.txt)
* 🔢 Analyze message frequency by user and time
* 🔍 Generate word clouds and top word statistics
* 😊 Detect sentiment trends over time
* 📊 Visualize chat activity with graphs and charts
* 📈 Support for group and individual chats
* 📄 Export analysis reports in various formats (CSV, PDF)

---

## 🚀 Installation

### Prerequisites

* ☕ Python 3.7 or higher
* Required libraries (can be installed via `requirements.txt`)

### Setup

```bash
git clone https://github.com/Aalyan-butt/WhatsApp-Chat-Analyzer
cd whatsapp-chat-analyzer
pip install -r requirements.txt
```

---

## 🔧 Usage

### Running the Analyzer

```bash
python analyze.py --file path/to/chat.txt --output results/
```

### Command-line Options

| Option         | Description                                    |
| -------------- | ---------------------------------------------- |
| `--file`       | 📂 Path to the WhatsApp chat file              |
| `--output`     | 📁 Directory to save the reports               |
| `--user`       | 👤 Filter analysis by specific user (optional) |
| `--date-range` | ⏰ Analyze chats within a date range (optional) |

---

## 📂 Project Structure

```bash
whatsapp-chat-analyzer/
│
├── analyze.py              # 🔢 Main script to run analysis
├── utils.py                # 🔧 Utility functions for parsing and processing
├── visualizations.py       # 📊 Graph and chart generation
├── requirements.txt        # 📄 Python dependencies
├── README.md               # 📖 Project documentation
```

---

## 📚 Contributing

Contributions are welcome! Please follow these steps:

1. 👁 Fork the repository
2. 📚 Create a new feature branch (`git checkout -b feature-name`)
3. 📃 Commit your changes (`git commit -m "Add feature"`)
4. ⬆️ Push to the branch (`git push origin feature-name`)
5. 📩 Open a Pull Request

---


## 📧 Contact

For questions or support, please contact:
**Aalyan Riasat**
📧 [aalyanriasatali@gmail.com](mailto:your.email@example.com)
🔗  • [GitHub](https://github.com/Aalyan-butt)

---

## 👏 Acknowledgements

* ✨ Inspired by various open-source chat analysis projects
* 📊 Thanks to the open-source community for the libraries used

---

## 🎨 Built With

* ![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg?logo=python)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg?logo=python)
* ![Pandas](https://img.shields.io/badge/Pandas-Data--Processing-yellow.svg?logo=pandas)
* ![NLTK](https://img.shields.io/badge/NLTK-Natural--Language--Toolkit-green.svg?logo=python)
* ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical--Graphics-lightblue.svg?logo=python)
* ![WordCloud](https://img.shields.io/badge/WordCloud-Text--Visualization-purple.svg?logo=python)
