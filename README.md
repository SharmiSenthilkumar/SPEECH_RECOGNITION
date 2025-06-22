# SPEECH_RECOGNITION

COMPANY: CODETECH IT SOLUTIONS

NAME: SHARMI S

DURATION: 4 WEEKS

INTERN ID:CT04DF1534

DOMAIN: ARTIFICIAL INTELLIGENCE

**The Speech Recognition System project focuses on converting spoken language into written text using modern machine learning techniques. The objective is to create a basic yet functional system capable of transcribing short audio clips, using pre-trained models to reduce development complexity and improve accuracy. This system is developed using Python and integrates two key components: audio generation and speech-to-text transcription. For generating the audio input, the Google Text-to-Speech (gTTS) library is used to synthesize speech from a given sentence. This audio is saved as a .wav file, which becomes the input for the transcription process. The transcription part of the system is powered by Facebook AI’s Wav2Vec2.0 model, a powerful transformer-based model pre-trained for automatic speech recognition. It is available via the Hugging Face transformers library and performs well even with real-world audio data due to its robust self-supervised learning capabilities. The audio is loaded and resampled to a 16,000 Hz frequency using the librosa library to match the requirements of the model. The waveform is then tokenized and passed to the Wav2Vec2 model, which outputs a series of predictions in the form of logits. These logits are interpreted using an argmax operation to get the most likely predicted tokens, which are finally decoded into readable text using the tokenizer. This process converts raw spoken audio into clear, machine-readable language. The final transcription result is printed to the console and optionally saved to a text file for record-keeping or downstream use. The complete system functions offline after model loading and can be extended to support real-time input, different languages, or even GUI interfaces. This task provides practical insights into the real-world application of AI in speech processing and introduces concepts like tokenization, deep learning inference, and audio preprocessing. Moreover, it integrates multiple tools and libraries, such as gTTS, librosa, torch, and Hugging Face's transformers, offering a cohesive experience in building intelligent audio-processing applications. Through this task, learners understand the entire pipeline from generating audio content to interpreting it with deep learning models. The process also includes error handling for missing files and sample rate conversion, ensuring smooth operation even for beginners. This project highlights how pre-trained models reduce the need for large datasets and training time, making advanced AI applications accessible to everyone. It also demonstrates how powerful transformer models can be adapted for real-time applications. The final deliverable is a standalone Python script that takes a line of text, generates an audio file, and accurately transcribes it into text, showcasing a full-circle speech recognition system in action.**



