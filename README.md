# YouTube MP3/MP4 Downloader & Transcript Generator

## Description
This project allows users to download YouTube videos in **MP3 (audio) or MP4 (video) format** and also provides a **transcript of the video's spoken content** in a text file. It is useful for extracting audio from videos, saving videos for offline use, and obtaining transcripts for accessibility or reference purposes.

## Features
- **Download YouTube videos** as MP3 (audio) or MP4 (video) format.
- **Automatic transcript generation** from the video's spoken content.
- **User-friendly interface** for easy video downloading.
- **Supports multiple languages** for transcripts (depending on video captions availability).
- **Efficient and fast processing** using APIs.

## Installation
To use this project, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Youtube-Mp3-Mp4-Downloader-Transcript.git
   cd Youtube-Mp3-Mp4-Downloader-Transcript
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python main.py
   ```

## Dependencies
This project requires the following dependencies:
- `pytube` - for downloading YouTube videos.
- `ffmpeg` - for converting videos to MP3 format.
- `whisper` or `SpeechRecognition` - for transcript generation.

You can install them using:
```bash
pip install pytube ffmpeg-python openai-whisper SpeechRecognition
```

## Usage
1. **Enter the YouTube video URL** in the application.
2. **Choose the desired format** (MP3 or MP4).
3. **Download the file** to your system.
4. If required, **generate the transcript** and save it as a text file.

## Example
```bash
python main.py --url "https://www.youtube.com/watch?v=example" --format mp3 --transcript True
```
This command will download the video as an MP3 file and generate a transcript.

## Future Improvements
- Add a **GUI** for better user experience.
- Support **batch processing** for multiple videos.
- Provide **subtitle files (SRT format)** along with text transcripts.
- Improve **speech-to-text accuracy** using AI models.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it.

## Contributors
- **Pragya Dwivedi** - [GitHub Profile](https://github.com/pragya169)

## Contact
For any issues or suggestions, feel free to open an issue on GitHub or reach out via email at **dwivedipragya16@gmail.com**.


