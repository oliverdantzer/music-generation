# music-generation

## Description

The goal of this project was to predict the notes given the beat and note times of classical music songs, and generate new songs using the predicted notes and the timings.

## Methods

I used a decision tree regression model, and fit to the the [musicnet dataset](https://www.kaggle.com/datasets/imsparsh/musicnet-dataset "musicnet dataset").

## Demos

Make sure to press the unmute button to hear the audio!

https://user-images.githubusercontent.com/104586131/229006975-2c82e4ba-5728-4b4b-b712-fc40845e6e7c.mov

Result for Prelude and Fugue in E-flat major, BWV 852 by Bach (Played with steel drums)



https://user-images.githubusercontent.com/104586131/229006981-b3ba5035-ed8c-49e9-9695-2f23fd8c0100.mov

Result for Prelude and Fugue in D major, BWV 850 by Schubert (Played with music box)



https://user-images.githubusercontent.com/104586131/229006637-afce49b5-bcaf-42e4-8d17-485bf52c0c7f.mov

Result for Piano Sonata in C minor, D. 958 by Schubert (Played with grand piano)

## To run things
### Required packages
 - `sklearn`
 - `pandas`
 - `numpy`
 - `midiutil`
 - `jupyter notebook`

### Running
 - Run jupyter notebook
 - Open ai_generated_midi.ipynb
 - Edit song_id to a song id in the musicnet dataset of your choice
 - Run all cells
 - Open in the resulting `output.midi` in [a midi player](https://cifkao.github.io/html-midi-player/ "online midi player (volume warning)") (volume warning).
