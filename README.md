PromptPix
Generative AI Project using Gemini 1.5 Pro & Gemini 1.5 Flash

````markdown
# Overview
This project is a Generative AI-based application that leverages **Gemini 1.5 Pro** and **Gemini 1.5 Flash** to generate text and analyze images based on user prompts. Users can input text-based queries or upload images, and the model provides meaningful responses accordingly.

# Features
- **Text-based Queries**: Users can provide text prompts, and the AI generates relevant responses.
- **Image Analysis**: Upload an image, and the AI provides insights or generates responses based on the image.
- **Hybrid Processing**: Supports both textual and visual data for comprehensive AI-powered assistance.
- **Fast & Efficient**: Uses **Gemini 1.5 Flash** for quick responses and **Gemini 1.5 Pro** for detailed reasoning.

# Setup Instructions

## Prerequisites
Before setting up the project, ensure you have the following installed:
- Python 3.11 or later
- Pip (Python package manager)
- Virtual environment 

## Step 1: Clone the Repository
```cmd
git clone https://github.com/ayushyadav10/PromptPix.git
cd gen-ai-gemini
```

## Step 2: Create a Virtual Environment
```cmd
conda create --name myvenv python=3.11.0 -y
conda activate myvenv/  
```

## Step 3: Install Dependencies
```cmd
pip install -r requirements.txt
```

## Step 4: Set Up API Key
This project requires access to Google’s Gemini API.
1. Obtain an API key from [Google AI Studio](https://ai.google.dev/)
2. Create a `.env` file in the project root and add:
```ini
GEMINI_API_KEY=your_api_key_here
```

## Step 5: Run the Application
```cmd
streamlit run vission.py
```

# Usage
1. **Text Prompt**: Enter a text-based query in the application, and it will generate a relevant response.
2. **Image Upload**: Upload an image, and the AI will analyze it and provide contextual insights.
3. **Hybrid Input**: Provide both text and images for a richer AI-driven response.

# Folder Structure
```bash
├── vission.py          # Main application script
├── requirements.txt    # Dependencies
├── .env                # API keys 
├── static/             # Stores images 
├── README.md           # Project documentation
```

# Technologies Used
- **Python**: Core programming language
- **Gemini 1.5 Pro & Flash**: AI models for text & image processing
- **Streamlit**: For User Interface
- **Google AI API**: For accessing Gemini models

# License
This project is open-source and available under the **MIT License**.

# Contact
For questions or support, reach out via aayushyadav1210@gmail.com or open an issue in the repository.

---

Happy Coding! 🚀
````

