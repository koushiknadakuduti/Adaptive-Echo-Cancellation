# Adaptive-Echo-Cancellation

This work is submitted as a project in "EEL5840: Elements of Machine Intelligence" class at University of Florida.

Echo cancellation in telephone line using machine learning: 

Description:
The data provided for this project represents two voice channels of a long-distance telephone
conversation. The signal labeled "music" is the voice channel from caller B end, the signal labeled
"corrupted_speech" is the speech of caller A mixed with music, and "fs" is the sample frequency in
Hertz. The speech on the near end, as the name suggests, is corrupted as a result of an imperfect
two-wire to four-wire hybrid, such as commonly used in most switching stations. The data is in .txt
format.

The assumptions for this project are that the far end hybrid is working well, so that the music
signal is not corrupted by the speech of caller A, and the near end hybrid has some leakage that
causes the mixing. This causes the incoming signal and the outgoing signal to be correlated with
each other. The goal is to use a linear adaptive filter as echo canceller to restore the outgoing signal
and recover the speech of caller A. The hybrid is not linear, it produces a saturating nonlinearity
that complicates the operation, i.e. linear echo cancellation is NOT optimal.

-> May have to install some of the modules required for project

The datasets used in the project are uploaded to the repository in .txt format. They are provided by the Professor and cannot be used for anyother purpose without giving credits



Thanks to Prof. Principe P. Jose and Prof. Alina Zare for their valuable teaching and support.
