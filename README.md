# Smart Assist

Smart Assist is an AI-powered tool built using Streamlit and the YouTube Data API that helps users fetch and analyze data from YouTube channels, such as video titles, descriptions, publish dates, and view counts.

## 🔧 Features

- Search for any YouTube channel by username or channel ID  
- Display metadata of recent videos  
- Simple, responsive interface using Streamlit  
- Modular and easy to extend

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher  
- A valid YouTube Data API v3 key

### Installation

```bash
git clone https://code.swecha.org/AmulyaGandhi/smart-assist.git
cd smart-assist
pip install -r requirements.txt
```

### Configuration

Open `smart_assist_app.py` and replace the placeholder API key:

```python
YOUTUBE_API_KEY = "your_api_key_here"
```

### Run the app

```bash
streamlit run smart_assist_app.py
```

## 📁 Project Structure

```
smart-assist/
├── smart_assist_app.py
├── requirements.txt
├── README.md
├── CONTRIBUTING.md
```
