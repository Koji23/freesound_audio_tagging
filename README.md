## Getting Started

Create a data/ directory
Install kaggle CLI through pip
Inside that directory run ```kaggle competitions download -c freesound-audio-tagging-2019```
Or download directly through https://www.kaggle.com/c/freesound-audio-tagging-2019/data

## Models

### Random Forest

/benchmark/
Curated data with Raw Audio - /benchmark_curated.ipynb
Noisy data with Raw Audio - /benchmark_noisy.ipynb

### Convolutional Neural Net

/explore_curated/
Curated data with Raw Audio and MFCC - /explore_curated.ipynb


/explore_noisy/
Curated data with Raw Audio - explore_noisy_raw_audio.ipynb
Curated data with MFCC - explore_noisy.ipynb


/explore_spectogram/
Curated data - explore_spectogram_curated.ipynb
Noisy data - explore_spectogram_noisy.ipynb