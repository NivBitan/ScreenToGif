﻿#ScreenToGif  

This is the current project of ScreenToGif.  

VS 2017 and .Net 4.6.1 required.  


Version 2.8:

• New recorder UX. It allows you to select the region of your recording such as other programs like Snipping Tool (region, window, fullscreen).  
• Encoding with FFmpeg now will respect the variable framerate of your recording.  
• The app will remember the output folder and filename for each export type.  
• Other minor visual adjustments.  

Fixed:

♦ Openning the Crop panel could cause a crash (if the new frame size was smaller).  
♦ Getting new frames (by a new recording or by loading something else) while the Crop panel was open might throw an exception.

Known Bugs:

♠ 