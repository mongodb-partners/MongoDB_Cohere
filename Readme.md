# Cohere Demo

This repository contains a demo application showcasing the integration with Cohere. Below is a detailed explanation of the contents, architecture, and instructions on how to run the application.

## Architecture Diagram

![Architecture Diagram](arch_diagram.png)

The architecture diagram above illustrates the flow and components of the application:

1. **User Interface (UI)**: The main entry point of the application is `ui.py`. This script handles user interactions and displays the results.
2. **Backend Processing**: The backend processes the data received from the UI, interacts with the Cohere API, and returns the processed results.
3. **Cohere API**: The application integrates with Cohere's API to leverage its capabilities for natural language processing.

## Running the Application

To run the application, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Cohere-demo.git
    cd Cohere-demo
    ```

2. **Install Dependencies**:
    Ensure you have Python installed. Then, install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Environment Variables**:
    Create a `.env` file in the root directory and add the necessary environment variables:
    ```plaintext
    COHERE_API_KEY = <COHERE_API_KEY>
    HF_TOKEN = <HUGGING_FACE_TOKEN>
    MONGO_URI = <MONGODB_URI>
    ```

4. **Run the Application**:
    Execute the main file to start the application:
    ```bash
    python ui.py
    ```

## Environment Variables

The application uses the following environment variables, which should be defined in the `.env` file:

- `COHERE_API_KEY`: Your API key for accessing Cohere's services.

## Files and Directories

- `ui.py`: The main file to run the application.
- `requirements.txt`: Lists the dependencies required to run the application.
- `arch_diagram.png`: The architecture diagram of the application.
- `.env`: File to store environment variables (not included in the repository for security reasons).

## Conclusion

This README provides a comprehensive guide to understanding and running the Cohere demo application. For any issues or contributions, please refer to the repository's issue tracker or submit a pull request.
