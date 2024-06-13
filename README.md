This project compares the ASR systems Whisper and wav2vec. It uses 2 different types of audios: clean and noisy audios.

final_proj.ipynb includes the code used to create transcriptions_wav2vec.csv, transcriptions_whisper.csv, and masterfile.csv
The csv files that start with transcriptions have two columns: the name of the file and the transcription of that file using the corresponding model.
masterfile includes both model transcriptions for the clean and noisy data as well as the WER for those transcriptions.
masterfile-excelsheet.xlsx is where I have highlighted different aspects of the data that are important to my experiment.

In the data folder, there is all of the audio files I used for my experiment. The entire dataset was unable to fit when moving it to github so it can be referrenced at https://www.kaggle.com/datasets/rtatman/speech-accent-archive

In order to run the code you must make sure the following libraries are installed: whisper, transformers, torch, librosa, os, csv, and jiwer.
Once all the libraries are installed, the third cell in final_proj.ipynb creates the masterfile.csv used for the experiment.
