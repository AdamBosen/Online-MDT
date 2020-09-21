# Online-AMDT
Website built in javascript using the jsPsych library to dynamically generate a 3 alternative forced choice modulation detection task.
A running example of the most recent version of this script can be found here: https://vrxfbjz4bn.cognition.run/

This script requires jsPsych 6.1, which can be downloaded here: https://github.com/jspsych/jsPsych/releases/tag/v6.1.0

Once you have downloaded jsPsych 6.1 and the 3AFC-AMDT.html file, you can open the website in a web browser and it should bring up a prompt to initiate a trial. The initial version of this script will present five trials of a three alternative forced choice task, in which two intervals are unmodulated white noise and one interval is sinusoidally amplitude modulated at 100 Hz. Feedback will be given after each trial, although no data are saved.

This script is currently under development to implement an 2-down, 1-up adaptive task to find modulation detection thresholds.  It will be periodically updated to reflect progress toward that goal.
