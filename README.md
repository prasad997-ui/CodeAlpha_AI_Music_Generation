# AI Music Generation using LSTM

## Project Description

This project generates new music using Artificial Intelligence and a Long Short-Term Memory (LSTM) neural network.

MIDI music data was collected and processed using the `music21` library. The MIDI files were converted into note sequences and prepared as training data.

An LSTM-based deep learning model was trained to learn patterns from the music sequences. After training, the model generated a new sequence of musical notes.

The generated notes were converted back into a MIDI file.

## Technologies Used

- Python
- TensorFlow / Keras
- LSTM Neural Network
- music21
- NumPy
- MIDI

## Dataset

The Nottingham MIDI dataset was used for training.

## Generated Output

The generated music is available in:

`AI_Generated_Music.mid`

## Workflow

1. Collect MIDI music data
2. Preprocess MIDI files using music21
3. Convert music into note sequences
4. Prepare input and output sequences
5. Build an LSTM neural network
6. Train the model
7. Generate new musical notes
8. Convert generated notes into MIDI
9. Save the generated MIDI file

## Result

The trained LSTM model successfully generated a new sequence of 100 musical notes and saved it as a MIDI file.
