# Python Code Review Assistant

This project utilizes Streamlit to create a web application that allows users to upload Python (.py) files for code review. The application leverages the OpenAI API, specifically the GPT-3.5-turbo model, to analyze the uploaded code and provide detailed suggestions for improvement. The review process includes a step-by-step analysis, mentioning the existing code line by line with proper indentation and suggestions for enhancements.

## Features

- **File Upload**: Users can upload Python files (.py) directly into the application for review.
- **Code Review**: Utilizes the GPT-3.5-turbo model to generate detailed code reviews, including suggestions for improvement.
- **Download Review**: Users can download the review comments as a text file, which includes a timestamp for uniqueness.

## Installation

To run this application, you need Python 3.6 or later and pip installed on your system.

1. Clone the repository to your local machine:
   git clone https://github.com/your-repository/python-code-review-assistant.git

2. Navigate to the cloned directory:
   cd python-code-review-assistant

3. Install the required dependencies:
   pip install -r requirements.txt

4. Run the Streamlit application:
   streamlit run app.py

## Usage

After starting the application, navigate to the provided URL by Streamlit (usually `http://localhost:8501`). Follow the instructions on the web page to upload a Python (.py) file and receive a detailed code review.

## Environment Variables

Before running the application, ensure you have created a `.env` file in the root directory with the following content:

OPENAI_API_KEY=your_openai_api_key_here

Replace `your_openai_api_key_here` with your actual OpenAI API key.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions for improvements or have identified bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
