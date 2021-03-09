# FFT_SoundWave

For Public Engagement use.

### Run Through Binder - Click the Badge Below:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KyleAcheson/FFT_SoundWave/main?urlpath=https%3A%2F%2Fgithub.com%2FKyleAcheson%2FFFT_SoundWave%2Fblob%2Fmain%2FSoundWave_FFT.ipynb)

It may take a few minutes to load the notebook through Binder.
If there are any problems (e.g. with memory), click kernel -> restart kernel.


#### To Run Locally: 

Clone this repo and spawn your Jupyter session.

``` git clone https://github.com/KyleAcheson/FFT_SoundWave.git ~/FFT ```

- Tested with Python 3.8.6.
- Requires: Librosa, IPython, matplotlib, numpy, and scipy.

#### Notebook Includes:

- A basic example of a Fourier transform for a combination of sine waves with differing frequencies.
- Uses randomly generated frequencies.
- Uncomment the freq variable in line 1 of the cell to specify frequencies yourself and see the effect on the Fourier transform (Remember to comment line 2 if you do).
- Select sample sounds from different animals, listen to them, plot the sound waveform as a function of time, and Fourier transform the waveform to the frequency domain to see how what animal sounds occur at what frequencies.

