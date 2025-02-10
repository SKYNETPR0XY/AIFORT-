# AIFORT-
AIFORT Digital Forensics Analysis Tool  

This repository contains a Python-based Digital Forensics Analysis Tool designed to help security researchers and digital forensics professionals with various types of analysis, including network traffic analysis, metadata extraction, and synthetic media detection.

. Network Traffic Analysis (PCAP)

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
