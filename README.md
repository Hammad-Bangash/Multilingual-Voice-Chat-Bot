# Voice Transformation Model for Multilingual Communication

Welcome to our Final Year Project (FYP) repository, dedicated to developing a voice transformation model for enabling multilingual communication. This project focuses on transforming speech between Urdu and English, demonstrating how speakers of different native languages can communicate effectively.

## Project Overview

In our project, we've developed a system where a native Urdu speaker's speech is translated and transformed into English for the listener, and vice versa. This allows seamless communication between individuals speaking different languages. Users can set their native languages to facilitate smooth interaction.

## TTS Model for Urdu

We trained a custom Text-to-Speech (TTS) model for Urdu to convert text into synthesized speech. Our initial version achieved 60% accuracy using a dataset of 300 male Urdu voice samples. The model preprocesses audio through normalization, trimming, and resampling to 16kHz. Transcriptions were manually handled, with subsequent phonetization and transliteration into English.

## Couqii TTS Integration

For languages beyond Urdu and English, we integrated the Couqii TTS for additional language support. Couqii TTS provides a robust platform for generating synthetic speech in various languages, enhancing our model's multilingual capabilities. [Couqii TTS](https://www.couqii.com)

## Telegram Interface

To facilitate easy interaction, we developed a Telegram bot interface. This bot allows users to set their native language preferences and engage in real-time multilingual conversations. The Telegram interface simplifies the process of accessing and utilizing our voice transformation capabilities.

## Demo Video

Watch our demo video showcasing the voice transformation model in action:



https://github.com/Hammad-Bangash/Multilingual-Voice-Chat-Bot/assets/129145452/a0e0ee74-f3a3-435d-9225-57f67a3dc375


## How to Use

1. **Set Native Languages:** Users specify their native languages using the Telegram bot interface.
2. **Start Communication:** Speak in your native language, and the system will translate and transform the speech for the recipient.
3. **Real-Time Translation:** The translated speech is delivered in the recipient's native language.

## Future Enhancements

- **Dataset Expansion:** Increase the dataset size to cover more vocabulary and improve accuracy.
- **Module Refinement:** Enhance the translation and transcription modules for better performance.
- **Additional Language Support:** Extend language support using Couqii TTS for more diverse communication capabilities.

## Contact

For questions or dataset requests, please contact us at [hammadraza12304@gmail.com](mailto:hammadraza12304@gmail.com).

## Acknowledgements

- **Microsoft SpeechT5:** Utilized as the foundation for our Urdu TTS model.
- **Couqii TTS:** Integrated for supporting additional languages beyond Urdu and English.
- **Telegram Bot Platform:** Enabled seamless user interaction through the Telegram interface.

---

Thank you for your interest in our project. We are committed to advancing multilingual communication through innovative voice transformation technology.
