# Text-to-Speech-using-My-voice

# Tacotron2 Text-to-Speech Model Training

This repository outlines the steps to train a Tacotron2 model using a set of 50 audio files. The following steps will guide you through the process of converting, renaming, transcribing, preprocessing, training, and testing the model.

## Steps

### 1. Record 50 Audio Files
- Record 50 audio files and store them in `.m4a` format.

### 2. Convert Files from M4A to WAV
- Convert the recorded `.m4a` files to `.wav` format.

### 3. Rename the Files from 1-50
- Rename the converted `.wav` files from `audio_1.wav` to `1.wav`, `audio_2.wav` to `2.wav`, and so on.
- You can use the following Google Colab notebook for renaming:
  [Rename Files (Colab Notebook)](https://colab.research.google.com/drive/1jwK5iqtUQ0Wlq8yGD9k62ZulWuLtpmSB?usp=sharing)

### 4. Create Metadata (Transcripted Data)
- Use Hugging Face's `facebook/wav2vec2-large-960h` model to transcribe the audio files and generate metadata.
- You can use this Colab notebook to create the metadata:
  [Generate Metadata (Colab Notebook)](https://colab.research.google.com/drive/15ceZiLD4JslNY2Kln3Y0OYtW8yssh7I7?usp=sharing)

### 5. Preprocess WAV Files
- Normalize and preprocess the `.wav` files to get them ready for training.
- Use this Colab notebook for preprocessing:
  [Preprocess WAV Files (Colab Notebook)](https://colab.research.google.com/drive/13glFhBLVzjhKi2ekNfJ8gvcfkM_aKBvt?usp=sharing)

### 6. Title Metadata for Tracking
- Ensure that the metadata file is properly structured with the file names and their corresponding transcriptions.
- You can use this Colab notebook to title the metadata for tracking:
  [Title Metadata (Colab Notebook)](https://colab.research.google.com/drive/1D1jLP0GnNE3DEbtnWeRDJaBzlB14qEHm?usp=sharing)

### 7. Train Tacotron2 Model
- Train the Tacotron2 model using the preprocessed `.wav` files and metadata.

### 8. Test the Model
- Once the model has been trained, test the model by generating speech from text.
## References

1. YouTube: [Watch Video](https://www.youtube.com/watch?v=e71H--vxRvo&t=352s)
2. GitHub Repo: [View Repository](https://github.com/justinjohn0306/FakeYou-Tacotron2-Notebook?tab=readme-ov-file)



