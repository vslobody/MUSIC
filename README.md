# MUSIC
Python implementation of the MUSIC Algorithm

Accurate estimation of the Direction of Arrival (DOA) is of paramount importance for Radar Application.

In the automotive applications we have to overcome the challenge of the limited number of antenna elements, which is resulting in poor angular resolution when using Digital Beam Forming methods.

Respectively, substantial efforts are underway to improve the angular resolution of the automotive radar system.

In this post we will summarize the results of the application MUSIC algorithm to the radar signal.

For the description of the python code, please check the MUSIC depository on the GitHub.

The code can process either real radar scan, or synthetic radar image. In order to process synthetic image, we need to comment out line 149:

[python light="true"]d31 = real_signal();#real signal;[/python]
Script is outputting multiple plots:

Time Series Plot
Range Plot (Based on FFT of the Time Series from individual antenna)
Range-Azimuth Plot in Polar coordinates.
Plot comparing MUSIC vs DBF accuracy of the peak finding.
