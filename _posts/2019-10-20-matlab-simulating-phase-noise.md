---
layout: post
title:  "MATLAB: Simulating Phase Noise"
date:   2019-10-20
categories: [jitter, phase noise, MATLAB]
---

The function pn_generator generates a phase noise signal with a given PSD.
{% include pn_generator/pn_generator.html %}

The following script tests pn_generator.

{% include pn_generator/test_pn_generator.html %}

Running the above code gives the following results:
{% include pn_generator/test_pn_generator_results.html %}
