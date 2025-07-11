# The Assistant

A Python web application using Flask for summarizing and translating text, and extracting text from audio files, documents, and images.

## Main Features
- Automatic summarization of long texts (Arabic/English)
- Summarize and translate between Arabic and English
- Extract text from audio files (supports: wav, mp3, ogg, flac, m4a, webm)
- Extract text from documents (txt, docx, pdf)
- Extract text from images (OCR)
- Supports file upload and audio URLs
- Automatic error logging

## Requirements
- Python 3.8+
- All packages listed in `requirements.txt`
- ffmpeg (must be installed and available in your system PATH)

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Make sure `ffmpeg` is installed and available in your PATH.
3. Run the application:
   ```bash
   python app.py
   ```
4. Open your browser at: [http://localhost:5000](http://localhost:5000)

## Project Structure
- `app.py` : Main application code
- `requirements.txt` : Required Python packages
- `static/` : CSS and JS files
- `templates/` : HTML templates
- `audio_cache/` : Audio transcription cache
- `error_logs.json` : Error log file

## Notes
- Make sure to set the `GROQ_API_KEY` variable in the code or as an environment variable.
- If you encounter issues with OCR or audio processing, ensure `ffmpeg` and `easyocr` are properly installed.

---

This project is ready to be pushed to GitHub. For any questions or suggestions, feel free to open an issue or contact the maintainer! 
