# Automatic-Ticket-Classification-tool

## Introduction
This innovative project introduces an Automatic Ticket Classification Tool designed to streamline user queries across HR, IT, and Transportation departments. The system employs a customized chatbot with domain-specific knowledge, overcoming the limitations of general language models. The administration interface facilitates knowledge enrichment by allowing the upload of department manuals, enabling the chatbot to provide accurate and relevant responses.

The heart of the project lies in the integration of an SVM ML model and PINECONE for ticket classification. The ML model, trained on a carefully curated dataset, ensures precise categorization of user queries into the respective departments. The seamless UI empowers users to interact effortlessly, pose questions, and, if unsatisfied, submit tickets for resolution.

Through meticulous implementation, the project achieves a robust solution where users can engage with a knowledgeable chatbot and efficiently route their concerns to the appropriate department. The SVM ML model, coupled with PINECONE, not only enhances the chatbot's responsiveness but also ensures accurate ticket classification, contributing to a comprehensive and effective system.

## Features
- **Chatbot Interaction:** Engage with a domain-specific knowledge chatbot for HR, IT, and Transportation queries.
- **Knowledge Enrichment:** Admin interface to upload manuals, enhancing the chatbot's domain-specific knowledge.
- **Ticket Classification:** SVM ML model and PINECONE for accurate categorization of user tickets.
- **User-Friendly UI:** Intuitive interface for seamless user interaction and ticket submission.

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/automatic-ticket-classification.git

# Navigate to the project directory
cd automatic-ticket-classification

# Install the required dependencies
pip install -r requirements.txt

# Run the application
python src/main.py
