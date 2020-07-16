# Onset-Informed NMF (OI-NMF)

This repository contains examples of the melody separation experiments by OI-NMF. For the 8 songs in MedleyDB used in the experiments, the one with the largest improvement of SI-SDR among 10 trials is taken as an example.

## onset_informed_NMF_sound_example.ipynb

This notebook shows the inferred variables and recovered spectrograms of each example.

## wav/

This directory contains the input signal, recovered signals (target and accompaniments) and its ground truth signals for each song.

+ *_mix.wav ... input signal
+ *_(target, accomp).wav ... ground truth signals of target instrument and accompaniments
+ *_est_(target, accomp).wav ... estimated signals of target instrument and accompaniments
