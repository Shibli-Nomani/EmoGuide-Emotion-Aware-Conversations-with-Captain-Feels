# EmoGuide-Emotion-Aware-Conversations-with-Captain-Feels
![image](https://github.com/user-attachments/assets/1df379a2-050c-4dae-a88b-11214545fbbd)

Unlock the power of empathetic AI with **EmoGuide: Captain Feels** — using **DeepFace** for image emotion detection, **LLaMA 2 (GGUF)** for NLP-driven advice, and **VITS TTS** for natural voice responses! 🤖💬  
#AI #EmotionRecognition #Chatbot #NLP

---

## 🧠 Emotion-Aware Chatbot Summary: Captain Feels 🤖

### 🔗 Model Integrations & Why They Matter

- 🐑 **LLaMA 2 (GGUF)**  
  Advanced NLP model for empathetic, personalized advice generation, making chats natural and emotionally aware.

- 🔊 **VITS TTS**  
  State-of-the-art Text-to-Speech for clear, expressive voice responses, enhancing user engagement.

- 📄 **JSON Data**  
  Holds emotion-specific advice and dynamic questions, enabling tailored conversations.

---

### 🧍‍♂️ Image Emotion Analysis

- 📷 **DeepFace Detection**  
  Accurate emotion, age, and gender recognition from facial images, providing key inputs for empathy.

- 🖼️ **Image Annotation**  
  Visual labels with emotion confidence scores for transparency.

---

### 🌳 Data Visualization

Visualized with **Plotly**, **Matplotlib**, and **Seaborn** for rich, interactive, and insightful charts:  
- 🧭 **Treemap** shows emotion, age, and gender distributions  
- 📊 **Bar Chart** displays emotion confidence with expressive emojis  

---

### 💬 Conversational Flow

- 🗨️ Friendly welcome audio to set the tone  
- 💡 NLP-driven empathetic chat with auto-generated, emotion-aware questions  
- 🧵 Chat memory for smooth flow and graceful exits  

---

### 🎧 Audio Output

Plays pre-generated audio responses via **VITS TTS**.

---

### 🔄 Future Scope

Plan to add voice-based response system for fully conversational interaction.

---

### 🖼️ Gradio UI Workflow

Upload Image → 🧠 Analyze → 🤖 Chat with Captain Feels

---

This blend of AI models and visualization tools delivers a powerful, empathetic chatbot experience — smart, sensitive, and visually engaging.
Let me know if you want me to add installation or usage instructions!

### 📌 Image - 1

![image](https://github.com/user-attachments/assets/0a0b3fcc-62e4-4f1e-b9dd-0b0e5f574441)

### 📌 Image - 2

![image](https://github.com/user-attachments/assets/bf5cf0a8-08fc-4728-a4ad-b34d665efc48)

### 📌 Image - 3

![image](https://github.com/user-attachments/assets/245637dc-26b2-45f2-bf1e-31c690932ac3)

## ⚙️ How Does It Work?

#### 🎧 Welcome Audio Message
A friendly welcome message is played using the VITS Text-to-Speech (TTS) model to set a warm, engaging tone.

#### 📤 Upload Your Image
Users upload a facial image via the Gradio interface.

#### 🧠 Emotion Detection with DeepFace
The image is analyzed using DeepFace, extracting the user’s emotion, age, and gender.

#### 📍 Emotion Classification & Routing
Once the emotion is detected, the chatbot dynamically shifts its response logic to match the classified emotion:

'angry': 😠

'disgust': 😷

'fear': 😨

'happy': 😊

'sad': 😢

'surprise': 😲

'neutral': 😐

#### 🗂️ JSON-Driven Response Logic
Each emotion is mapped to specific advice and dynamic follow-up questions stored in a structured JSON format. The chatbot uses the following prompting logic to generate personalized advice using LLaMA 2:

```sh
prompt = (
    f"User feels {emotion} and said: '{user_response}'.\n"
    f"Advice: \"{advice}\"\n"
    f"Rewrite this as a single empathetic sentence directly addressing the user's situation. "
    f"Respond only with the rephrased line in quotes, no explanation or questions."
)
```
#### 🖼️ Visual Feedback
The user's image is annotated with detected emotion labels and confidence scores, and displayed for transparency.

#### 📊 Emotion Data Visualization
Emotion trends are visualized using Plotly, Matplotlib, and Seaborn:

- Treemap: Shows emotion, age, and gender distribution.

- Bar Chart: Displays confidence levels of emotions with expressive emojis.

#### 🤖 Empathetic Advice via LLaMA 2
The Captain Feels chatbot uses LLaMA 2 (GGUF) to deliver rephrased, empathetic guidance and asks context-aware follow-up questions.

#### 🧵 Chat Memory & Exit Flow
The system maintains conversational context and enables graceful exits through simple commands like exit or goodbye.


