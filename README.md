# Implementation of Speech Recognition on PYNQ Z2

`This project was started in 2022.02 and finished in 2022.06.`
## Content
* [Abstract](#abstract)
* [Preparation](#preparation)
* [Approach](#approach)
* [How to Reproduce](#how-to-reproduce)
* [Thanks](#thanks)

## Abstract
Independently implement a speech recognition Python project. Score: 95/100. 

## Preparation
- PYNQ Z2 board
- ReSpeaker
- A computer with Jupyter Notebook

## Approach
1. Import all packages needed. Download the bitstream.
2. Configure the audio in/out and HDMI in/out.
3. Load and encode.
4. Detect and recognize the voices.
5. Release the cache and memory.

## How to Reproduce
1. Download the file [Speech_Recognition.ipynb](/Speech_Recognition.ipynb).
2. Turn on the PYNQ Z2 board; ReSpeaker. And make sure all components work well.
3. Run the code.

## Thanks
- Many, many thanks to my teacher, Prof. Pan.
- Thanks to TA, Dr. Wang and Dr. Huang.
