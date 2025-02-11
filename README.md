# Threat-Analyser-AI
Transform Unstructured Threat Data into Actionable Intelligence. Leveraging Gemini LLM API to automatically detect and structure cyber threats from unstructured data sources (logs, reports, alerts), then store organized threat intelligence in MongoDB Atlas cloud database with a web interface for threat analysis.

# Threat Analyzer AI 🔍🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![MongoDB Atlas](https://img.shields.io/badge/MongoDB-Cloud-green.svg)](https://www.mongodb.com/atlas)

Transform unstructured cyber threat data into structured intelligence using Gemini LLM and MongoDB Atlas.

![Workflow Diagram](https://via.placeholder.com/800x400.png?text=Threat+Processing+Workflow) <!-- Replace with actual diagram -->

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [API Reference](#api-reference)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features ✨
- **AI-Powered Analysis**: Gemini LLM API for threat extraction
- **Structured Data Output**:
  - Attack Identification
  - MITRE ATT&CK Tactics Mapping
  - Technique/Sub-technique Classification
  - Detailed Mitigation Strategies
- **Cloud Storage**: MongoDB Atlas integration
- **Interactive Dashboard**:
  - Threat Visualization
  - Advanced Search & Filtering
  - Timeline Analysis

## Installation ⚙️

### Prerequisites
- Python 3.10+
- HTML, CSS, JS (for frontend)
- MongoDB Atlas account
- Gemini API key

### Backend Setup
```bash
git clone https://github.com/Guhan-Sachi/Threat-Analyser-AI
cd Threat-Analyser-AI/backend
pip install -r requirements.txt

cd ../frontend
# Follow the instructions for setting up the frontend
