# YTVideoAnalyser

YTVideoAnalyser is an advanced tool designed to leverage Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG), to provide in-depth analysis and responsive query handling for YouTube video content. This project aims to enhance the accessibility and understanding of video content, making it easier for educators, content creators, and media professionals to retrieve specific information and generate content-based responses.

## Features

- **Video Content Analysis**: Analyze transcriptions of YouTube videos to understand the content deeply.
- **Query Response Generation**: Utilize LLMs and RAG to answer queries related to the video, providing contextually relevant responses.
- **Integration with OpenAI's API**: Harness the power of OpenAI's language models for natural language processing tasks.
- **Vector Database Utilization**: Efficiently store and retrieve high-dimensional data vectors, improving the speed and accuracy of information retrieval.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/roshankhandelwal97/YTVideoAnalyser.git
cd YTVideoAnalyser
```
## Set up a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
```
## Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To use YTVideoAnalyser, you need to follow these steps:

**Set your API keys:**

Ensure your OpenAI and Pinecone API keys are set in your environment variables or configured directly in the application.
Run the application:

Execute the main script to start analyzing YouTube videos and responding to queries.

```bash
python main.py
```

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

**Fork the Project**

- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

