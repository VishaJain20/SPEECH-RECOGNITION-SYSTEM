# SPEECH-RECOGNITION-SYSTEM

**Company**: CODTECH IT SOLUTIONS  
**Intern**: Visha Jain  
**Intern ID**: C0DF230  
**Domain**: AI/ML  
**Duration**: 4 weeks  
**Mentor**: Neela Santosh  

## 📌 Overview

This project is a sleek and accurate **Speech Recognition System** built using the **Wav2Vec2** model from Hugging Face. It allows users to upload or record audio and instantly get text transcriptions. Designed with a clean and modern **Gradio UI**, it focuses on user experience, accuracy, and performance.


## ✅ Features

- 🎤 Converts speech to text using the `facebook/wav2vec2-base-960h` model.
- 💾 Supports both uploaded audio and microphone input.
- 📄 Outputs transcribed text in real-time.
- ⏳ Displays live progress and status feedback.
- 🧪 Includes a sample audio file for testing.
- 🔁 Clear button to reset input and output areas.
- 🎨 Beautiful and responsive Gradio UI with custom CSS styling.
- ⚠️ Graceful error handling and validation messages.



## ⚙️ Technologies Used

- **Model**: facebook/wav2vec2-base-960h
- **Libraries**: PyTorch, Hugging Face Transformers, Librosa
- **UI Framework**: Gradio with custom CSS
- **Language**: Python 3.8+



## 🛠 How to Use

1. Install Python 3.8+ and required libraries: `torch`, `transformers`, `librosa`, `gradio`.
2. Run the Python file `transcriber.py` to launch the app.
3. Open the Gradio interface in your browser.
4. Upload or record your audio using the interface.
5. Click the **"Transcribe"** button to view the output text.
6. Use the **"Load Sample Audio"** button to test with a sample file.
7. Click **"Clear"** to reset all fields and inputs.



## 🧪 Sample File

The app includes a sample audio file named `harvard.wav`. You can test the functionality using this file or upload your own `.wav` audio recordings.



## 🗂 Project Structure

- `task2CODTechs(1).ipynb`: Main source code
- `harvard.wav`: Sample audio file (replaceable)
- `README.md`: Project documentation



## 💡 Advantages

- ✅ **High Accuracy**: Pretrained on 960 hours of speech data (LibriSpeech).
- ✅ **Real-Time Processing**: Fast transcription with clear status updates.
- ✅ **User-Centric Design**: Clean, card-based UI with intuitive controls.
- ✅ **Lightweight**: Can run on CPU with low resource consumption.
- ✅ **Open & Extendable**: Easily replace the model or customize the UI.
- ✅ **Web-Based**: Accessible via any modern browser, no installation required on client side.



## 📚 Learning Outcomes

- Hands-on experience with **speech recognition using deep learning**.
- Integration of **pretrained models** via Hugging Face Transformers.
- UI development with **Gradio** and custom **responsive design**.
- Audio data preprocessing and conversion using **Librosa**.
- Error handling, UI feedback, and production-level application design.



## 🔗 Model Details

- **Model Name**: `facebook/wav2vec2-base-960h`
- **Framework**: PyTorch
- **Language**: English
- **Training Data**: 960 hours of LibriSpeech
- **Fine-tuned for**: Automatic Speech Recognition (ASR)




