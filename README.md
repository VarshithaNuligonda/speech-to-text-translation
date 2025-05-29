# speech-to-text-translation
This project is a real-time, web-based speech-to-text and translation system that leverages OpenAI's Whisper model to transcribe and translate spoken audio into text across multiple languages. The system captures audio directly from the browser using JavaScript, preprocesses it into mel-spectrograms using torchaudio, transcribes it using Whisper’s “medium” model, and translates it using the translators Python module. It is accessible via a user-friendly Gradio interface, making it suitable for multilingual communication, accessibility aids, and educational tools.

**Libraries Used in the Project**:
OpenAI Whisper – For multilingual speech recognition and transcription.

torchaudio – For audio preprocessing like resampling and mel-spectrogram generation.

translators – Python module to translate text between various languages using online translation services.

Gradio – For building the interactive web interface that allows real-time audio input and displays output.

JavaScript (MediaRecorder API) – For capturing and encoding audio in the browser.

NumPy/PyTorch (implied for Whisper backend and signal processing).
