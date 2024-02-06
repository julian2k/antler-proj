# CV Assistant Interface

This project is a Streamlit application that serves as an interface for a CV Assistant. It allows users to upload their CVs and leverages both a custom Assistant API and Bland AI for analysis and feedback.

## Features

- **CV Upload**: Users can upload their CV in PDF or DOCX format.
- **Assistant API**: Calls a custom Assistant API to provide initial feedback or analysis on the uploaded CV.
- **Bland AI Integration**: Utilizes Bland AI for further analysis and insights on the CV.

## Installation

To run this project locally, you need to have Python installed on your system. Follow these steps to get started:

1. Clone this repository to your local machine.
2. Navigate to the project directory and install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Set up your environment variables by renaming the `.env.example` file to `.env` and filling in your API keys and endpoints:

```
# Assistant API credentials
ASSISTANT_API_KEY=your_assistant_api_key_here

# Bland AI integration details
BLAND_AI_ENDPOINT=your_bland_ai_endpoint_here
BLAND_AI_API_KEY=your_bland_ai_api_key_here
```

## Running the Application

After setting up your environment variables, you can start the Streamlit application by running:

```bash
streamlit run app.py
```

Navigate to the URL provided in your terminal to interact with the CV Assistant Interface.

## Project Structure

- `app.py`: The main Streamlit application script.
- `assistant_api.py`: Contains the function to call the Assistant API.
- `bland_ai_integration.py`: Handles the integration with Bland AI for CV analysis.
- `utils.py`: Utility functions for file handling and response formatting.
- `requirements.txt`: Lists all the Python dependencies required for this project.
- `.env`: Stores environment variables for API keys and endpoints (ensure this file is added to `.gitignore` for security).
- `README.md`: Provides an overview of the project and setup instructions.

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-source and available under the MIT License.
