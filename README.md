# Winnie

This project is a Flask web application for embedding an HTML template.

## Table of Contents

- [Description](#description)
- [Inspiration](#inspiration)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


## Description

This project is a Flask web application that serves an HTML template called `index.html`. It provides a simple route ("/") that renders the template using Flask's `render_template` function.

## Inspiration

We were inspired to create this application by the need for an efficient way to retrieve relevant information from documents in a corporate environment. It's an enterprise application for retrieval augmented generation. We save documents in Google Cloud and we chat with the document to retrieve relevant information.

## Features

- Renders the `index.html` template
- Supports both POST and GET requests

## How we built it

We built this application using Vertex AI Agent Builder, which allowed us to create a customized summary to provide full details and as much information as makes sense for the question.

## Challenges we ran into

One of the main challenges we faced was trying to integrate the application with our existing document management system. We had to overcome compatibility issues and ensure seamless communication between different components of the system.

## Accomplishments that we're proud of

We are proud of successfully implementing the chat functionality and developing an efficient method for retrieving information from documents. Additionally, customizing the summary to provide relevant details was a significant achievement.

## What we learned

Through this project, we learned a lot about natural language processing techniques, document management systems, and integrating AI technologies into existing workflows. We also gained valuable experience in software development and project management.

## What's next for Winnie

In the future, we plan to further enhance Winnie's capabilities by incorporating advanced machine learning models for document analysis and expanding its integration with other platforms and systems within the enterprise environment.

## Installation

1. Clone the repository:

```
   git clone <repository_url>
```
2. Install the required dependencies


```
pip install Flask
```

## Usage

3. Navigate to the project directory:

```
cd <project_directory>
```

4. Run the Flask application:

```
python app.py

```

5. Open your web browser and go to http://localhost:5000 to view the rendered index.html template.