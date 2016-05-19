## About MIDI toolbox


## History

The current version of the MIDI Toolbox is 1.1. The previous version was released 23rd Jan 2006. Originally it was released in 18.5.2004.

## Reference
Eerola, T. & Toiviainen, P. (2004). MIDI Toolbox: MATLAB Tools for Music Research. University of Jyväskylä: Kopijyvä, Jyväskylä, Finland. Available at https://github.com/miditoolbox/

## This release
Toiviainen, P., & Eerola, T. (2016). MIDI Toolbox 1.1. URL: https://github.com/miditoolbox/

## Update

At the time of the release of the MIDI toolbox 1.0 in May 2004, we never thought this small collection of functions for meant for analyses inspired by models of music cognition would be used by hundreds of scholarly studies ranging from neuroscience to ethnomusicology. Ironically, we have not really embraced the tool ourselves, since we only a couple of publications that actually use the tool (Toiviainen & Eerola, 2006; Eerola et al., 2006). Other toolboxes, such as MIR Toolbox (Lartillot & Toiviainen, 2007) and Motion Capture toolbox (Burger & Toiviainen, 2013), became more important in our research.

The main purpose of release MIDI toolbox 1.1 was to make the MIDI toolbox functional again. The original release in 2004 utilised mex files in Matlab to read and write MIDI files. These compiled run files were soon obsolete since they were specific to different operating systems and Matlab versions. In 2006 this problem of reading MIDI files became all too frequent a complaint and we created a simple fix for the problem. This extension bypassed the problematic mex-based read/write functions within the toolbox. However, it did not handle tempo change information properly and was inconvenient for the users, since it needed to be installed separately.

The version 1.1 finally sorts outs this issue by relying on the work carried out by Music Dynamics Lab (http://musicdynamicslab.uconn.edu/) run by Ed Large, who have used the same original source (Ken Schutte) for reading MIDi files as we did in our earlier fix. This also fixes the tempo change issues in reading MIDI files. We also added the possibility of looking at tempo curve (the relative duration of the onsets in BPM), updated few functions, and removed all the obsolete functions. We also switched to github for a more transparent and easy sharing of the code.

## Manual

The documentation provides a description of the Toolbox (Chapter 1), installation and system requirements (Chapter 2). Basic issues are explained in Chapter 3. Chapter 4 demonstrates the Toolbox functions using various examples and Chapter 5 constitutes the function reference section.

Download MidiToolbox User's Manual (1.2 Mb pdf file)

## Toolbox is free for academic use

MIDI toolbox is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License. See readme.md for full details.

## Installation

Unpack the MIDI Toolbox file package you have downloaded. For this, use a program like Winzip for Windows and Stuffit Expander for Macintosh. This will create a directory called miditoolbox. Secondly, a version of the Matlab program needs to be installed (see www.mathworks.com). Thirdly, the Toolbox needs to be defined in the Matlab path variable. Under the File menu, select Set Path. Under the Path menu, select Add to Path. Write here the name of the directory where this toolbox has been installed. Then click OK. Finally, under the File menu, select Save Path, and then Exit.

## Compatibility

Windows (98, 2000, XP): The MIDI Toolbox version 1.0 is compatible with Matlab 5.3 and Matlab 6.5.

Macintosh (OS X): The MIDI Toolbox version 1.0 is compatible with Matlab 6.5 for Macintosh.

Linux: Currently not tested but should be compatible.
