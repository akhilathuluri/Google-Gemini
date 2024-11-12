# Google-Gemini
This repository contains two Streamlit applications that leverage the Google Generative AI (Gemini) models for natural language processing and image generation.

![google-gemini](https://github.com/user-attachments/assets/112448d8-f138-4eef-bb30-d4d35c4a143a)

## Table of Contents
- [Prerequisites](#prerequisites)
- [File-Structure](#File-Structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
  - [Text-based Q&A](#text-based-qa)
  - [Image-based Generation](#image-based-generation)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before running the applications, ensure you have the following prerequisites:

- Python 3.6 or later
- [Google API Key](#configuration)

## File-Structure
```bash
streamlit-gemini/
│
├── app.py
├── vision.py
├── requirements.txt
├── .gitignore
├── .env (Add your Google API Key here)
└── README.md
```

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/gemini-streamlit.git
    ```

2. Navigate to the project directory:

    ```bash
    cd gemini-streamlit
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Configuration

Create a `.env` file in the project root and add your Google API Key:

```env
GOOGLE_API_KEY=your_google_api_key
```

## Usage
### Text-based Q&A (app.py)
To run the text-based Q&A application, execute:
```bash
streamlit run app.py
```
This will launch the Streamlit app for text-based interactions with the Gemini model.

### Image-based Generation (vision.py)
To run the image-based generation application, execute:
```bash
streamlit run vision.py
```
This will launch the Streamlit app for image-based interactions with the Gemini model.

## Contributing
Contributions are welcome! If you have ideas for improvements or find issues, please open an issue or create a pull request.

## License
This project is licensed under the MIT License.


#### Remember to replace "your_google_api_key" with your actual Google API Key in the `.env` file. Additionally, you can add more details to the README based on your project's specific features and functionalities.
