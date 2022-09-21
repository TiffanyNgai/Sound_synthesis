# Sound_synthesis

Data used in Sound_synthesis.ipynb (the script) is collected from analysing the audio in audacity
- Sampling frequency: 44.1kHz
- Time (entire audio): 2.548s

The audio can be viewed as 4 sections:
- Section 0: Silient (0s - 0.0465s)
- Section 1: 389Hz (0.0465s - 0.425s)
- Section 2: 389Hz + 662Hz (0.425s - 0.815s) + decreasing amplitude
- Section 3: 389Hz + 662Hz + 518Hz (0.815s - 2.548s) + decreasing amplitude

Approach:
- Synthesize the three base frequencies
- Add harmonics to the fundamental structure of the waveform
- Apply fade out
