[![GitHub][github-shield]][github-url] [![License][license-shield]][license-url]   [![Email][gmail-shield]][gmail-url] ![Discord: landomrandom Status][discord-shield-static]

[github-shield]: https://img.shields.io/badge/GitHub-121727?style=for-the-badge&color=080c19&logo=github&logoColor=00c6ff
[github-url]: [https://github.com/LandoNikko/Pilko-Frame-Capture-Studio](https://github.com/LandoNikko/Kaira-Transcribe-Panel)

[license-shield]: https://img.shields.io/badge/License-MIT-121727?style=for-the-badge&labelColor=080c19&messageColor=e0e6f7&logo=gnu&logoColor=00c6ff
[license-url]: LICENSE

[gmail-shield]: https://img.shields.io/badge/Email-00c6ff?style=for-the-badge&color=080c19&logo=gmail&logoColor=00c6ff
[gmail-url]: landonikko@gmail.com

[discord-shield-static]: https://img.shields.io/badge/Discord-landomrandom-121727?style=for-the-badge&labelColor=080c19&messageColor=e0e6f7&logo=discord&logoColor=00c6ff

# Kaira Transcribe Panel

Kaira Transcribe Panel is a web app for local & cloud speech-to-text (STT) using Whisper models and major cloud APIs (using your own API Key). Compare model speed, quality and pricing.

Try it here: https://landonikko.github.io/Kaira-Transcribe-Panel

![Image](https://github.com/user-attachments/assets/25cf5827-1fed-4d17-8a44-f09f64f9a64e)

## ![Features Shield][features-shield]

- **Local Models:** Tiny, Base, Small, Medium, Turbo, Large (via `openai-whisper`).
- **Cloud Models (BYOK):** OpenAI (Whisper-1, GPT-4o Mini, GPT-4o), Deepgram Nova-3 (Summarization & Topics), Gladia (EN), ElevenLabs Scribe v1.
- **Outputs:** Paragraphs, Segments, SRT, VTT, TSV.
- **Media Sync:** Player with waveform, real-time highlighting, click-to-seek.
- **Themes:** E Ink, Nova, Minty, Toffee.
- **Queue Support:** Batch processing.
- **Price Calculator:** Estimates API costs.
- **Utilities:** Copy/download, notifications, stats.

[features-shield]: https://img.shields.io/badge/Features-5f43f2?style=for-the-badge&color=0b0b0b

| E Ink | Nova |
|:----:|:-----:|
| ![E Ink](https://github.com/user-attachments/assets/0f14eb9c-9302-4b29-bdbe-5a4f47f5547c) | ![Nova](https://github.com/user-attachments/assets/2655da4d-6ca0-4dc7-9a1a-a6a24c42e341) |
| Minty | Toffee |
| ![Minty](https://github.com/user-attachments/assets/91b3fc27-2354-41f1-b7a2-f124b1df3839) | ![Toffee](https://github.com/user-attachments/assets/b2f3ba76-b3b7-471e-a1b7-5ef104ffa45f) |

## ![Installation Shield][installation-shield]

1.  **Clone:** `git clone https://github.com/kairauser/KairaTranscribePanel.git && cd KairaTranscribePanel`
2.  **Python & PyTorch:** Python 3.8+. Install PyTorch from [pytorch.org](https://pytorch.org).
3.  **FFmpeg:**
    -   macOS: `brew install ffmpeg`
    -   Ubuntu/Debian: `sudo apt install ffmpeg`
    -   Windows: Download from [ffmpeg.org](https://ffmpeg.org/download.html) & add to PATH.
4.  **Dependencies:** `pip install -r requirements.txt`

[installation-shield]: https://img.shields.io/badge/Installation-5f43f2?style=for-the-badge&color=0b0b0b

## ![Usage Shield][usage-shield]

1.  **Run:** `python Launch_Kaira.py`
2.  **Open:** `http://localhost:5000` in your browser.
3.  **Cloud API Keys:** Paste into UI when prompted (stored in browser localStorage).
    -   [OpenAI](https://platform.openai.com/account/api-keys)
    -   [Deepgram](https://console.deepgram.com/signup)
    -   [Gladia](https://gladia.io)
    -   [ElevenLabs](https://elevenlabs.io/app/settings/api-keys)

[usage-shield]: https://img.shields.io/badge/Usage-5f43f2?style=for-the-badge&color=0b0b0b

## ![Roadmap Shield][roadmap-shield]

-   Translation features (API & LLM).
-   Additional transcription models.
-   In-browser Whisper (ONNX, Transformers.js).
-   ARIA compliance.
-   Local WaveSurfer.js bundling.
-   Modular cloud support.

[roadmap-shield]: https://img.shields.io/badge/Roadmap-5f43f2?style=for-the-badge&color=0b0b0b

## ![Contributing Shield][contributing-shield]   [![License][license-shield]][license-url]

Contributions, bug reports, and feature requests are welcome! Fork the repo, create a branch, make changes, test, commit, push, and open a Pull Request.

[contributing-shield]: https://img.shields.io/badge/Contributing-5f43f2?style=for-the-badge&color=0b0b0b