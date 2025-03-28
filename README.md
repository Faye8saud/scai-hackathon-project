# scai-hackathon-project
AI Hackathon Project - Sports Commentary to Visuals

This project converts sports games commentary into visual feedback for deaf audiences using (Whisper AI and spaCy)

# Main Features
-  Use of **Whisper AI** to transcribe live game commentary.
-  Filtering of key words (Natural language processing) using **spaCy** .
-  Displaying the relevant **icons/images** based on detected words as visual feedback on the video.

# Installation - how to run
first install the dependencies:

```bash
pip install openai-whisper spacy opencv-python
```

You also need to download the Arabic spaCy model:
```bash
python -m spacy download ar_core_news_md
```

Clone this repository:

```bash
git clone https://github.com/your-username/AI-Hackathon-Project.git
cd AI-Hackathon-Project
```
Run the script:

```bash
python main.py
```
