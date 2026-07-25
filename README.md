# GroupDNA: WhatsApp Chat Analyzer

## Overview
GroupDNA is a Python-based data analysis tool designed to decode the social dynamics, messaging habits, activity peaks, and conversational patterns of WhatsApp group chats without relying on heavy external libraries like Pandas. 

## Project Features
* **Message Parsing:** Cleans and structures raw WhatsApp export text files into manageable dictionaries containing timestamps, senders, and message texts.
* **Activity Metrics:** Identifies busiest days, busiest hours, and maps user activity over a 24-hour heatmap using NumPy.
* **Lexical Analysis:** Filters out common stop-words and visualizes the group's most frequently used words.
* **Behavioral Analytics:** Computes average response speeds, tracks longest silent streaks, and automatically assigns behavioral personality archetypes (e.g., The Spammer, Night Owl, Ghost, etc.) to participants.
* **Executive Report:** Generates a clean, comprehensive terminal report summarizing all findings.

## Dataset
* **Source:** `DADS Minor PROJECT dataset.txt` (WhatsApp chat export export).
* **Metrics Tracked:** Total message volume, active days, individual message counts, and temporal distributions.

## Instructions to Run
1. Open the `GroupDNA_Sudeep_Gorabal.ipynb` file in Google Colab.
2. Upload the required dataset file to your Colab session environment.
3. Run the cells sequentially from top to bottom to parse data, generate visualizations, and print the final report.

## Author
* **Name:** Sudeep Gorabal
* **Project:** DADS Minor Project
