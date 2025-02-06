# Copilot for Regulatory Compliance

An AI-powered virtual assistant designed to automate IT audit checks for regulatory compliance. This tool leverages machine learning and natural language processing to evaluate documents against ISO 27001 and ISO 27002 standards, reducing manual effort and minimizing human error during audits.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Architecture](#project-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The Copilot project automates compliance audits by integrating:
- **A Fine-Tuned LLM**: Trained on IT compliance standards (ISO 27001 & ISO 27002) for accurate audit evaluations.
- **A User-Friendly Web Interface**: Built with HTML, CSS, and JavaScript to ensure an intuitive user experience.
- **A Python (Flask) Backend**: Handles API requests, document processing, and integration with the AI model.
- **Data Handling & Reporting**: Features automated report generation and session history management.

## Features

- **Automated Compliance Checks**: Quickly analyzes uploaded documents for compliance gaps.
- **Report Generation**: Generates detailed compliance reports with actionable recommendations.
- **Real-Time Interaction**: Chat with the AI copilot for instant feedback on uploaded documents.
- **Multi-Format Support**: Upload DOCX, PDF, CSV, and Excel files.
- **User Account Management**: Create, manage, and delete user accounts with ease.
- **Session History**: Filter, delete, and export past sessions for audit trails.

## Project Architecture

- **Frontend**: HTML, CSS, and JavaScript for a responsive UI.
- **Backend**: Python with the Flask framework for API management.
- **AI Model**: Fine-tuned GPT-4o-mini model for compliance auditing.
- **Database**: MySQL for storing user data, session history, and other structured information.
- **Optional Hosting**: Use [ngrok](https://ngrok.com/) for exposing the application to the web.

## Installation

### Prerequisites

- **Python 3.8 or above**  
  Download from: [Python.org](https://www.python.org/downloads/)
- **Git** (optional, for cloning the repository)  
  Download from: [Git Downloads](https://git-scm.com/downloads)
- **ngrok** (optional, for web hosting)  
  Download from: [ngrok.com](https://ngrok.com/)

### Cloning the Repository

Clone the repository using Git:

```bash
git clone https://github.com/KKYC-hub/ComplyZense.git
