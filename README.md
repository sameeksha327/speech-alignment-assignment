 Forced Alignment using Montreal Forced Aligner (MFA)

* Objective
The objective of this project is to perform forced alignment between speech audio files and their corresponding text transcripts using the Montreal Forced Aligner (MFA), and to analyze the generated word- and phoneme-level alignments using Praat.

Forced alignment automatically determines the start and end times of words and phonemes in a speech signal when the transcript is known.


* Tools Used
- Montreal Forced Aligner (MFA)** – used to generate forced alignments
- Pretrained MSK / English MFA acoustic model** – used within MFA
- Praat – used for visualization and inspection of TextGrid files



* Dataset
The dataset consists of:
- Audio files in `.wav` format
- Corresponding transcript files in `.txt` format  

Each audio file has a matching transcript file with the same filename.  
Only a subset/sample of the dataset is uploaded to this repository for demonstration purposes.



* Workflow

1. Installed Montreal Forced Aligner (MFA) on the local system.
2. Downloaded the pretrained English acoustic model (MSK / english_mfa).
3. Organized the dataset with audio and transcript files.
4. Ran forced alignment using MFA to generate TextGrid files.
5. Opened the generated TextGrid files along with audio files in Praat.
6. Inspected and analyzed word-level and phoneme-level boundaries.
7. Observed alignment quality and noted minor variations where applicable.

---

## Alignment Command Used

```bash
mfa align corpus english_mfa english_mfa output
