# 🚀 SpaceBot – Ask Me Anything About Space!

**SpaceBot** is an interactive chatbot powered by the latest LLMs (Llama 3 via Groq API) that answers any space-related queries in real time. From planets, rockets, and agencies to the mysteries of the universe, SpaceBot is your AI companion for all things cosmic!

---

## 🌟 Features

- **Conversational AI**: Powered by LangChain and Llama 3 (Groq API) for smart, concise answers.
- **Space-focused**: Only responds to queries about space, astronomy, agencies, missions, rockets, satellites, and related physics.
- **Gradio UI**: Simple chat interface that you can run locally or share online.
- **Keyword Filtering**: Ensures only relevant, space-themed questions are answered.
- **Extensible**: Easily modify the space keywords or prompt system for your use case.

---

## 🛠️ Installation

Clone this repo or download the `Space_Chatbot.ipynb` notebook.

Install all required dependencies (recommended in a new environment):

```bash
pip install langchain-community==0.2.15 langchain-chroma==0.1.3 langchain-text-splitters==0.2.2 langchain-huggingface==0.0.3 langchain-groq==0.1.9 unstructured==0.15.0 "unstructured[pdf]==0.15.0" nltk==3.8.1 gradio sqlite-utils
```

---

## 🚦 Usage

1. **Get your Groq API Key**  
   - Sign up at [Groq Cloud](https://console.groq.com/) and generate an API key.
   - Add your API key in the notebook:  
     ```python
     os.environ["GROQ_API_KEY"] = "your_groq_api_key_here"
     ```
2. **Run the notebook** (`Space_Chatbot.ipynb`) in Google Colab or locally with Jupyter.
3. **Interact via Gradio UI**  
   - The chatbot will launch a link. Open it to start chatting!
   - Only space-related questions will be answered.

---

## ✨ Example Questions

- "Tell me about the Chandrayaan missions."
- "What is a wormhole?"
- "How does a rocket reach orbit?"
- "What's the difference between ISRO and NASA?"
- "Explain the concept of dark matter."

_Non-space questions will be politely declined!_

---

## 📦 Project Structure

- `Space_Chatbot.ipynb` – Main notebook with all code.
- `README.md` – You're here!

---

## 🧩 Tech Stack

- [LangChain](https://github.com/langchain-ai/langchain)
- [Gradio](https://www.gradio.app/)
- [Groq API (Llama 3)](https://console.groq.com/)
- Python 3.8+

---

## 🛡️ Disclaimer

- **For educational/demo use only.**
- Keep your API keys secret!  
- The bot is space-focused and will not answer unrelated queries.

---

## 📄 License

MIT License

---

## 🤝 Contributing

Pull requests and suggestions are welcome! Open an issue to discuss improvements or new features.

---

## 🙋‍♂️ Author

- [harshdeepsinghhanspal](https://github.com/harshdeepsinghhanspal)

---

Happy exploring the universe! 🚀
