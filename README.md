# Image to Text Response with RAG

This project is a web application that allows users to upload an image, process it to extract details, and then interact with the application by asking questions about the image. The application uses the Salesforce BLIP model for image captioning and OpenAI's GPT-3.5-turbo for generating responses to user queries.

## Description

This project was built to demonstrate the capabilities of using advanced machine learning models for image processing and natural language generation. The application provides an interactive way to understand and interact with the content of an image by using state-of-the-art models for image captioning and conversational AI.

### Technologies Used

- **Streamlit**: For building the interactive web interface.
- **Salesforce BLIP Model**: For generating image captions.
- **OpenAI GPT-3.5-turbo**: For generating responses to user questions.
- **Pillow**: For image processing.
- **Python Dotenv**: For managing environment variables.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up your OpenAI API key**:
    - Create a `.env` file in the root directory of the project.
    - Add your OpenAI API key to the `.env` file:
      ```env
      OPENAI_API_KEY=your_openai_api_key
      ```

5. **Run the Streamlit application**:
    ```sh
    streamlit run app.py
    ```

6. **Open the application**:
    - Open your web browser and go to `http://localhost:8501`.

## Usage

1. Upload an image in JPG, JPEG, or PNG format.
2. Wait for the image to be processed.
3. Ask questions about the image in the chat interface.
4. View the responses generated by the application based on the image details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
