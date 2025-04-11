
# 🤖 Technical Writer AI Agent

This AI-powered Gradio app helps you generate high-quality technical content based on your interests or background. It can:

- 🧠 Suggest relevant topics
- 📚 Research the selected topic
- ✍️ Write and optimize a technical article
- 🧪 Create a quiz for readers
- 🌐 Translate the article into any language
- 🔊 Generate text-to-speech audio using a selected voice

---

## 🚀 How It Works

1. **Input your background or area of interest**
2. The AI may ask follow-up questions for better topic suggestions
3. Once topics are available, it picks the top one and:
   - Researches the topic
   - Writes and polishes an article
   - Generates a quiz
   - Translates the article to your selected language
   - Converts the translated text into audio

---

## 🛠️ Technologies Used

- **Gradio** for the UI
- Custom Python pipeline for content generation
- Integration with:
  - Sarvam AI for translation and TTS
  - Custom NLP agents for topic suggestion, writing, and quiz generation

---

## 📦 Requirements

Install dependencies:

```bash
pip install load_dotenv, gradio
# Also ensure you have access to Sarvam APIs and other pipeline dependencies
