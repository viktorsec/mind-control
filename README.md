# mind-control
This repository contains a simple hand motor imagery BCI (brain computer interface) solution. Tested with NeuroSky's MindWave.

# OpenVibe
Core BCI is done in [OpenVibe](http://openvibe.inria.fr/).
The following scenarios are available in /OpenVibe folder and are meant to be opened with OpenVibe.

| file | description |
| --- | --- |
| signal-aquisition.xml | use to aquire and save signal
| training.xml | trains classifiers from aquired data
| classification.xml | classifies online signal with pre-trained classifiers
| bci-tests.xml | used for signal analysis when needed

The two included classifiers can be used inside the classification scenario, but it's better to train your own.

# BrainGame
Simple Unity game. Should be controled from OpenVibe via VRPN. Not done. Based on earlier project.

# Poster
Poster presented at the MEi:CogSci Conference in Vienna 2016
