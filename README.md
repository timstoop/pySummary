# PySummary, a frontend for OTS

Since I switched from OSX to Linux, I've generally been very happy. There is however one tool that I occassionally miss: OSX's excellent Summarize tool. Apparantly, although there's a library for making summaries on Linux, there is no easy frontend for it. So I took and hour and a half and created something in wxPython that works for me.

## Dependencies

* wxPython
* OTS

On Debian/Ubuntu/Mint, you're can install these with `sudo apt-get install libots0 python-wxgtk2.8`.

## Usage

* Make pySummary.py executable: `chmod +x pySummary.py`
* Run it: `./pySummary.py`
* Paste a long text in the top textfield.
* Press Enter.
* Read the bottom textfield.
