# Chatbot Application using Gemini Pro API and Streamlit

[![Deployed App](https://img.shields.io/badge/Deployed%20App-Streamlit-green)](https://geminichatbot-pro.streamlit.app/)

This repository contains a chatbot application built using the Gemini Pro API, with a user interface created using Streamlit and Python. The API token is obtained from Google Studio.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Functions](#functions)
- [Configuration](#configuration)
- [License](#license)
- [Contributing](#contributing)

## Introduction

This project is a simple chatbot application that leverages the capabilities of the Gemini Pro API for natural language processing. The user interface is built using Streamlit, a Python library that makes it easy to create interactive web applications.

## Features

- **Real-time Chat**: Communicate with the chatbot in real-time.
- **Streamlit UI**: A simple and interactive user interface.
- **Gemini Pro API**: Utilizes Gemini Pro for natural language processing and response generation.
- **Customizable**: Easy to customize and extend according to your needs.

## Installation

To get started, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. **Create a Virtual Environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Obtain Gemini Pro API Token**:
   - Get your API token from Google Studio by signing up and following their instructions.
   - Replace the placeholder in the configuration with your API token.

2. **Run the Streamlit Application**:
    ```bash
    streamlit run app.py
    ```

3. **Access the Application**:
   - Open your web browser and navigate to `http://localhost:8501` to start chatting.
   - Alternatively, you can access the deployed application [here](https://geminichatbot-pro.streamlit.app/).

