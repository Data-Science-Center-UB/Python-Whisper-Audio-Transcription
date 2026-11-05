#### Context audio datasets

Mozilla Common Voice Scripted Speech datasets used to provide short audio clips for testing Whisper on lower-resource languages. For the workshop, individual clips can be selected from the official `test.tsv` split and used directly in the faster-whisper notebook.

\---

### Nigerian Pidgin English

#### Reference

Mozilla Data Collective / Common Voice. *Common Voice Scripted Speech 26.0 - Nigerian Pidgin English*.  
https://mozilladatacollective.com/datasets/cmqigs4fs00jtnq07o0txdcvm  
Dataset ID: `cmqigs4fs00jtnq07o0txdcvm`  
Release date: June 17, 2026.

#### License

Creative Commons Zero v1.0 Universal (CC0-1.0).

The dataset may be used for training and evaluating automatic speech recognition (ASR) models. Common Voice additionally forbids attempts to determine the identity of speakers and forbids re-hosting or re-sharing the dataset.

#### Audio files

**Language:** Nigerian Pidgin English (`pcm`)

**Format:** MP3

**Dataset size:** 8,964 clips / 14.45 hours of recorded speech, including 7,755 validated clips from 60 speakers.

**Test split:** 326 clips

The file `test.tsv` contains the metadata for the test split. Each row corresponds to one audio clip. The column `path` gives the file name inside the `clips/` folder and `sentence` contains the corresponding reference transcription.

For the Whisper workshop, individual clips can be selected from this test split and used as separate input files.

#### .txt file

Contains the corresponding written text (transcript), derived from `test.tsv` and manually extracted for the selected audio clip.

\---

### Swahili

#### Reference

Mozilla Data Collective / Common Voice. *Common Voice Scripted Speech 26.0 - Swahili*.  
https://mozilladatacollective.com/datasets/cmqim4c1000tmnr07zq3vwhor  
Dataset ID: `cmqim4c1000tmnr07zq3vwhor`  
Release date: June 17, 2026.

#### License

Creative Commons Zero v1.0 Universal (CC0-1.0).

The dataset may be used for training and evaluating automatic speech recognition (ASR) models. Common Voice additionally forbids attempts to determine the identity of speakers and forbids re-hosting or re-sharing the dataset.

#### Audio files

**Language:** Swahili / Kiswahili (`sw`)

**Format:** MP3

**Dataset size:** 730,532 clips / 1,064.6 hours of recorded speech, including 269,130 validated clips from 1,523 speakers.

**Test split:** 12,271 clips

The file `test.tsv` contains the metadata for the test split. Each row corresponds to one audio clip. The column `path` gives the file name inside the `clips/` folder and `sentence` contains the corresponding reference transcription.

For the Whisper workshop, individual clips can be selected from this test split and used as separate input files.

#### .txt file

Contains the corresponding written text (transcript), derived from `test.tsv` and manually extracted for the selected audio clip.

