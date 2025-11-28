# 🌍 Bridges from Borders – AI-Powered Cultural Integration Platform

Empowering immigrants to overcome cultural and language barriers through intelligent translation, local support, and adaptive learning.

![ConnectU](https://github.com/aishwaryachand/MindBridge/blob/main/mockups/connectu.jpeg)
![Chatbot](https://github.com/aishwaryachand/MindBridge/blob/main/mockups/chatbot.jpeg)
![Tastematch](https://github.com/aishwaryachand/MindBridge/blob/main/mockups/tastematch.jpeg)
![Learnnest](https://github.com/aishwaryachand/MindBridge/blob/main/mockups/learnnest.jpeg)



##  Project Overview

- Built an AI-driven platform using Hugging Face Transformers for dialect-aware translation across 30+ languages tailored to immigrant contexts.  
- Engineered **ConnectU**, a geolocation-based community connector leveraging graph clustering to link users with nearby immigrants for real-time support.  
- Developed a multilingual cultural adaptation chatbot using transformer-based models to guide users on local customs, essential services, and emergency protocols.  
- Designed interactive language learning tools for survival phrases and cultural etiquette, with gamified modules and contextual feedback.  
- Optimized for on-device inference and offline access in low-resource settings; tested across diverse user groups, achieving 4.2/5 in usability and a 43% faster adaptation score.

##  Tech Stack

| Component           | Stack                                           |
|---------------------|-------------------------------------------------|
| Translation         | Hugging Face Transformers (`mBART`, `MarianMT`) |
| Chatbot             | Custom NLP pipeline / LLM + rule-based fallback |
| Geolocation & Graph | `scikit-learn`, `NetworkX`, PostGIS             |
| Frontend            | React.js / Streamlit                            |
| Backend             | Python, FastAPI                                 |
| Deployment          | Docker, on-device inference (Qwen2, LLaMA 3.2B) |

## 📦 Key Features

###  Precision Multilingual Translation
Handles regional dialects and immigrant-relevant phrasing using fine-tuned transformers.

###  ConnectU – Community Connector
Detects user geolocation and recommends nearby immigrant support communities using graph clustering.

###  Cultural Chatbot
Conversational AI agent that answers real-world questions on laws, healthcare, transport, housing, and local customs.

###  Language Learning Assistant
Gamified, bite-sized language lessons with cultural etiquette integrated for rapid adaptation.



## 🚀 Getting Started

# Clone the repository
git clone https://github.com/yourusername/bridges-from-borders.git
cd bridges-from-borders

# Install dependencies
pip install -r requirements.txt

# Run server
uvicorn app.main:app --reload
