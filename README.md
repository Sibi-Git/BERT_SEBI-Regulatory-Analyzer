# **BERT-SEBI-Regulatory-Analyzer**  
### *Automated SEBI Filings Analysis Using BERT for Financial Compliance*  
🚀 **By Sibi Marappan**  
**Internship Project at HCL**  
**Internship Period**: July – December 2022  
**Duration**: 6 months  
**LinkedIn**: [Sibi Marappan](https://www.linkedin.com/in/sibi-marappan/)

---

## 📖 **Table of Contents**
1. [📝 Introduction](#-introduction)
2. [🔍 Project Overview](#-project-overview)
3. [🚀 Key Features](#-key-features)
4. [💻 Technologies Used](#-technologies-used)
5. [📥 Installation Guide](#-installation-guide)
6. [🛠️ Usage Instructions](#️-usage-instructions)
7. [📊 Sample Outputs](#-sample-outputs)
8. [🚧 Future Enhancements](#-future-enhancements)
9. [📞 Contact Information](#-contact-information)

---

## 📝 **Introduction**
This project, developed as part of an **HCL Internship**, automates the analysis of regulatory filings issued by the **Securities and Exchange Board of India (SEBI)**. Leveraging **BERT** and advanced NLP techniques, this tool helps extract key insights, categorize documents, and visualize relationships between financial entities, regulations, and penalties. It addresses the need for automation in regulatory compliance for financial institutions, ensuring faster and more accurate document analysis.

---

## 🔍 **Project Overview**
The **BERT-SEBI-Regulatory-Analyzer** performs the following key tasks:
- **Extracts financial terms and regulatory actions** like company names, insider trading, and penalties.
- **Classifies documents** by topics such as **insider trading**, **mergers**, and **compliance**.
- **Generates interactive graphs** to show relationships between companies, regulations, and penalties.
- **Creates a summary HTML report** for quick review of findings.

---

## 🚀 **Key Features**
- **Data Cleaning & Preprocessing**: Handles SEBI filings in HTML or PDF, cleaning and preparing them for analysis.
- **Entity Extraction**: Automatically extracts company names, regulatory terms, insider trading mentions, and penalties.
- **Topic Modeling**: Categorizes SEBI filings into topics such as insider trading, mergers, and compliance.
- **Graphical Visualization**: Provides interactive graphs showing how different entities are connected in SEBI filings.
- **Summarization & HTML Report**: Automatically generates a **summary HTML report** of the analysis for easy review.

---

## 💻 **Technologies Used**
- **BERT**: Transformer model used for text analysis and entity extraction.
- **Python**: For scripting, data processing, and backend operations.
- **Pandas & NumPy**: Libraries for handling large datasets and numerical operations.
- **Matplotlib & Plotly**: For creating visualizations and graphs.
- **spaCy**: NLP library for performing Named Entity Recognition (NER).
- **SimpleTransformers**: Used for fine-tuning the BERT model.
- **HTML Reports**: Automatically generated summary reports for easy viewing.

---

## 📥 **Installation Guide**

Follow these steps to set up the project locally:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/BERT-SEBI-Regulatory-Analyzer.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd BERT-SEBI-Regulatory-Analyzer
    ```

3. **Create a Virtual Environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```

4. **Install Required Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Prepare SEBI Filings Data**:
    - Place the SEBI filings (HTML or PDF) into a directory called `data/` within the project directory.
  
6. **Ensure Necessary Packages are Installed**:
   - Verify that Python 3.7+ is installed and all dependencies listed in `requirements.txt` are satisfied.

---

## 🛠️ **Usage Instructions**

1. **Upload SEBI Filings**:
   - Place the SEBI filings in the `data/` folder. Ensure the documents are either in **HTML** or **PDF** format.

2. **Run the Analysis**:
   - To analyze the filings and generate outputs, use the following command:
     ```bash
     python run_analysis.py --input ./data/ --output ./output/
     ```
     The results, including extracted entities, topics, and visualizations, will be stored in the `output/` directory.

3. **Generate HTML Summary Report**:
   - The system automatically creates an HTML file summarizing the results of the analysis. This file will be saved as `output/summary_report.html`. Open this file in a web browser to view a high-level overview of the findings.

4. **Visualize Graphs**:
   - To visualize the relationships between entities, open the `output/graph_visualization.html` file in a browser.

---

## 📊 **Sample Outputs**

- **Entity Extraction**:
    - Extracts terms such as "Company X," "insider trading," and "penalty."
  
- **Topic Categorization**:
    - Example:
        - Document 1: Insider Trading (75% relevance)
        - Document 2: Mergers & Acquisitions (60% relevance)

- **Graphical Visualization**:
    ![Graphical Visualization Example](path/to/graph/image.png)

- **HTML Report**:
    - The `summary_report.html` file provides a quick overview of key findings, extracted entities, and topics in a browser-friendly format.

---

## 🚧 **Future Enhancements**

- **Automated SEBI Filings Download**: Add a web scraper to automatically download the latest SEBI filings.
- **Real-Time Monitoring**: Implement real-time analysis to continuously monitor new SEBI filings as they are published.
- **Customizable Dashboard**: Develop a dashboard for non-technical users to view insights and visualizations in an easy-to-understand format.
- **Custom Reports**: Allow users to generate custom reports on specific topics or regulatory terms of interest (e.g., insider trading, penalties).

---

## 📞 **Contact Information**

- **Developer**: Sibi Marappan  
- **Email**: [msibi.mail@gmail.com](mailto:msibi.mail@gmail.com)  
- **LinkedIn**: [Sibi Marappan](https://www.linkedin.com/in/sibi-marappan/)

---

**Note**: This project was part of an internship with **HCL** (July – Dec 2022) and is designed to automate the analysis of SEBI filings, improving the efficiency of regulatory compliance for financial institutions.
