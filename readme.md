# VideoRecorder

Dead simple video recorder, written in Python.


Dependencies
------------
* Python >= 3.4 
* Python packages
    * Numpy >= 1.11
    * OpenCV >= 3.0
    * PyQt5 >= 5.6
    * Pillow >= 4.0
    * picamera >= 1.12


Keyboard Shortcuts
------------------
* Quit Program: ESC # doesn't work properly
* Starts/stops recording: ALT + Space
* Adds tag: ALT + T # doesn't work properly
* Cancels recording: ALT + C
* Idle videocanvas: SHIFT + I
* Next Metadata-Tab: CTRL+Page-Down
* Previous Metadata-Tab: CTRL+Page-UP


== OPTIONS ==
-------------
* -u --template           -- choose your template by its name
* -k --stop_time          -- define a stop time for your recording; Formats: "HH:MM:SS" and "YY-mm-dd HH:MM:SS"
* -o --output_directory   -- define the output directory of your recordings
* -s --instant_start      -- start the recording instantly without user input
* -i --idle_screen        -- do not display the video frames; this saves quite some computational power
* -c --color              -- record in color
