# AdVerb: Visually Guided Audio Dereverberation, ICCV 2023 #

## Abstract
We present AdVerb, a novel audio-visual dereverberation framework that uses visual cues in addition to the reverberant sound to estimate clean audio. Although audio-only dereverberation is a well-studied problem, our approach incorporates the complementary visual modality to perform audio dereverberation. Given an image of the environment where the reverberated sound signal has been recorded, AdVerb employs a novel geometry-aware cross-modal transformer architecture that captures scene geometry and audio-visual cross-modal relationship to generate a complex ideal ratio mask, which, when applied to the reverberant audio predicts the clean sound. The effectiveness of our method is demonstrated through extensive subjective and quantitative evaluations. Our approach significantly outperforms traditional audio-only and audio-visual baselines on three downstream tasks: speech enhancement, speech recognition, and speaker verification, with relative improvements in the range of 18% - 82% on the LibriSpeech test-clean set. We also achieve highly satisfactory RT60 error scores on the AVSpeech dataset. We will make all our codes and models publicly available upon acceptance.

## Required Packages



The ```model``` folder contains the code for our model. You can import it from ```model/models/adverb.py```. The training code will be released soon.

Our code is inspired by [Visual Acoustic Matching](https://github.com/facebookresearch/visual-acoustic-matching).
