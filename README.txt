************************************************************
	Eye - tracking with Tobii setup

Code for testing the compatibility of Tobii with psychoPy

************************************************************

1) Installing the Pro SDK and connected Tobii device via USE or network
pip install tobii_research http://developer.tobiipro.com/python/python-getting-started.html

2) Use Tobii eye Tracker Manager  to perform individual calibration (a default calibration has been implemented automatically)

3) Get connected to the python script to get GAZE data
http://developer.tobiipro.com/python/python-step-by-step-guide.html

4) Two running demo with psychopy and Tobii
https://github.com/datigrezzi/psychopy_tobii_demo


Possible to use Pupil data:  tobii_research.PupilData (diamater and validity)

Here, I provide two code examples and your could find them in the current folder: 
	- Blocked_image (ref: https://datigrezzi.com/2018/01/12/tobii-pro-sdk-in-psychopy/)
	- Gaze_contigent (ref: https://datigrezzi.com/2019/01/04/gaze-contingent-paradigms-psychopy-tobii-pro-sdk/)


