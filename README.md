# SR400-GPIB
Stanford Research 400 Photon Counter GPIB Program

Most of this program has been provided through the drivers located here: 
http://sine.ni.com/apps/utf8/niid_web_display.download_page?p_id_guid=E96DA621D87834ADE0440021287E6A9E

The pulling of the data from the channels is from a VI provided by Paul Henning in the LabVIEW forum here:
https://forums.ni.com/t5/LabVIEW/Serious-bugs-in-the-SR400-gated-photon-counter-LabVIEW-drivers/td-p/422464?profile.language=en

I will be trying to organize the file more as time goes on. The version I have as the final version includes DAQ interface for wavemeter and PMT readings and should be simple to remove. Due to coding it on the fly as a colleague told me things he needed, I left the code in a big of a mess; which, again, I will be trying to clean up as time goes on. 

Using this program, I was able to fully control the SR400 through the program's interface as well as save the data. However, I wrote warnings in the interface to help avoid some bugs that occur if you try to stop the data acquisition or save at the wrong time, causing the program to have issues.
