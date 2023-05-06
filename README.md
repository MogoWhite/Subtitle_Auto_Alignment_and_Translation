# Subtitle_Auto_Alignment_and_Translation
Whisper Timestamped GPT Subtitle Auto Alignment and Translation Tool


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MogoWhite/Subtitle_Auto_Alignment_and_Translation/blob/main/Whisper_Timestamped_GPT%E5%AD%97%E5%B9%95%E8%87%AA%E5%8A%A8%E8%BD%B4%E7%BF%BB%E5%B7%A5%E5%85%B7.ipynb)

Use the Whisper extension library, Whisper Timestamped, to convert speech to text and perform word-level timing alignment, generating SRT format subtitle files.

This tool accomplishes the following three tasks:

1. Use the Whisper extension library, Whisper Timestamped, to convert speech to text and perform word-level timing alignment, generating SRT format subtitle files.

2. Adjust the start and end times of subtitles in SRT format files:

    1. Shift the start time of subtitles forward or backward.
    2. Shift the end time of subtitles backward.
    3. Adjust the time interval between adjacent subtitles.

3. Call the API to implement the following features:

    1. Translate subtitle files line by line into the target language.
    2. Support generating bilingual subtitles or translated subtitles only.
    3. Support exporting in ASS or SRT format.
    4. Add multithreaded GPT processing.
    5. Add multi-line input for better context linking.
    6. Adjust the prompt to improve the translation accuracy of proper nouns to some extent.
