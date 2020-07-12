---
layout: post
title:  "MATLAB: Spectral Analysis"
date:   2020-03-13
categories: [jitter, phase noise, MATLAB]
---

The function fft_probe calculates the spectrum (FFT and PSD) of a given signal.
{% include fft_probe/fft_probe.html %}

The following script tests fft_probe using a noisy sine wave signal.

{% include fft_probe/test_fft_probe.html %}
