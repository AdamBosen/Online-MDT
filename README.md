# Online-MDT
Website built in javascript using the jsPsych library to dynamically generate a 3 alternative forced choice modulation detection task.
A running example of the most recent version of this script can be found here: https://vrxfbjz4bn.cognition.run/

This script requires:
jsPsych 6.1, which can be downloaded here: https://github.com/jspsych/jsPsych/releases/tag/v6.1.0
fft.js, which can be downloaded here: https://www.nayuki.io/res/free-small-fft-in-multiple-languages

Once you have downloaded jsPsych 6.1, fft.js, and the 3AFC-AMDT.html and/or 3AFC-SMDT.html file, you can open the website in a web browser and it should bring up a prompt to initiate a trial.

This script implements a 2-down, 1-up adaptive task to find modulation detection thresholds for a 100 Hz sinusoidally amplitude modulated bandlimited noise (350 - 5600 Hz), or a 0.5 ripple per octave spectral modulation of the same bandlimited noise. Clicking Start Trial will play three noise bursts, two of which are unmodulated bandlimited noise and one is sinusoidally amplitude modulated at 100 Hz (AMDT) or spectrally modulated at 0.5 ripples per octave (SMDT). Feedback is given after each trial, and the modulation depth is adjusted to find threshold. The task stops and reports a final threshold after 8 reversals of the adaptation direction.

