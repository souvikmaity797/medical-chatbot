# 🩺 MedBot – AI-Powered Medical Assistant

MedBot is a conversational AI-powered medical assistant built using [Streamlit](https://streamlit.io/) and OpenAI's GPT API. It provides instant answers to general health questions, explains medical terms, offers symptom-related suggestions, and helps users understand medical reports like PDFs. MedBot also uses interactive maps and secure login to enhance user experience.

---

## 🚀 Features

- 💬 **Conversational AI** – Chat with MedBot to get answers on general medical queries.
- 📄 **PDF Analysis** – Upload medical PDFs (like lab reports) and ask questions about the content.
- 🗺️ **Location Services** – Find nearby hospitals or medical services using geolocation and maps.
- 🔐 **Secure Login** – User authentication using `streamlit-authenticator` and bcrypt hashing.
- 📈 **Progress Tracking** – Progress bars and NLP-powered insights using `tqdm` and `nltk`.

---

## 🧰 Tech Stack

| Purpose                     | Libraries Used                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| UI and Web App             | `streamlit`, `streamlit_chat`, `streamlit-authenticator`, `streamlit-folium`  |
| AI Integration             | `openai`, `langchain`                                                          |
| PDF Reading                | `PyPDF2`                                                                       |
| Geolocation & Maps         | `geopy`, `folium`                                                              |
| Environment Variables      | `python-dotenv`                                                                |
| NLP and Progress           | `nltk`, `tqdm`                                                                 |
| Security                   | `bcrypt`                                                                       |
| Network/API Requests       | `requests`                                                                     |

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/medbot.git
cd medbot
