# LinkedIn Cold DM Generator 🤖

A powerful AI-powered tool that generates personalized LinkedIn messages for recruiters and hiring managers. Built with Streamlit and powered by Groq's high-performance LLM.

[App](https://linkedincolddmgenerator.streamlit.app/)

## ✨ Features

- **Personalized Messages**: Generates unique, context-aware messages for each recipient
- **Company-Specific Content**: Automatically researches and incorporates company-specific technologies
- **Natural Tone**: Creates messages that sound human and engaging
- **Easy to Use**: Simple interface requiring just a LinkedIn URL and your information
- **Secure**: API keys managed through Streamlit's secure secrets management

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **AI/LLM**: 
  - Groq API
  - Meta's Llama 2 (4-maverick-17b-128e-instruct)
  - LangChain for orchestration
- **APIs**: 
  - SERP API for LinkedIn profile scraping
  - Groq API for LLM inference
- **Vector Database**: ChromaDB

## 🚀 Getting Started

### Prerequisites

- Python 3.13+
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/furiousstrafer/LInkedinColdDMGenerator.git
cd LInkedinColdDMGenerator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application locally:
```bash
streamlit run ColdDMApp/app.py
```

### Environment Setup

For local development, create a `.env` file in the `ColdDMApp` directory with:
```
GROQ_API_KEY=your_groq_api_key
SERP_API_KEY=your_serp_api_key
```

## 💡 Usage

1. Enter the LinkedIn profile URL of the recruiter or hiring manager
2. Provide your name and university information
3. Click "Generate DM" to create a personalized message
4. Copy and use the generated message on LinkedIn

## 🔒 Security

- API keys are securely managed through Streamlit's secrets management system
- No sensitive data is stored in the repository
- All API calls are made securely through HTTPS

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) for the amazing web framework
- [Groq](https://groq.com/) for the high-performance LLM inference
- [LangChain](https://www.langchain.com/) for the LLM orchestration framework
