# AIFORT-

AIFORT: AI-Enhanced Intelligence Forensic Tool
AIFORT is a Python-based digital forensic tool that provides 12 analysis options, including file hashing, metadata extraction, keyword search,
timeline analysis, hidden file detection, log parsing, network traffic analysis, PDF report generation, and simulated AI chat assistance
(DeepSeek and Open AI). This README explains how to download Visual Studio Code (VS Code) and run the aifort.py script on Window




 1. Network Traffic Analysis (PCAP)

    Analyzes PCAP files to detect anomalies in network traffic using machine learning techniques (Isolation Forest for anomaly detection).
    Identifies suspicious IP addresses by counting packet frequency and comparing it to a predefined threshold.

2. File Metadata Extraction

    Extracts metadata from files, such as documents, images, and more, using the hachoir library.
    Provides insights into file properties, such as creation date, author information, and other embedded details.

3. Synthetic Media Detection

    Attempts to detect AI-generated images using a TensorFlow-based model.
    If TensorFlow is unavailable, synthetic media detection is disabled.
    Models trained for synthetic media detection are used to predict whether an image is AI-generated or genuine.

4. PDF Report Generation

    Automatically generates a PDF report summarizing the analysis results (network traffic anomalies, suspicious IPs, file metadata, and synthetic media detection).
    The report is created using the fpdf library and can be customized with the user's choice of output file name.
