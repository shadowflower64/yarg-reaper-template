# YARG Template for REAPER

## About
This REAPER project template contains pre-defined tracks and MIDI note names to help you create charts for YARG in the notes.mid format. Apart from the template, this directory also contains a couple of extra helpful files, such as colormaps and separate MIDI note name files.

### Contents
* `ProjectTemplates/YARG.rpp` - This is the main project template file.
* `MIDINoteNames/` - This directory contains text files with note names used in the template. Names of the files are self-explanatory.
* `Data/`
   * `color_maps/` - This directory contains three color maps used in YARG:
      * `colormap_grybo.png` - for charting 5-Fret Guitar, 5-Fret Bass and 5-Lane Keys.
      * `colormap_drums.png` - for charting Pro Drums.
      * `colormap_elitedrums.png` - for charting Elite Drums.
   * `text_strings/` - This directory contains text files with lists of text events for specific tracks. Names of the files are self-explanatory.

## Installation
To properly install the YARG template into REAPER, you must copy all of the folders and files from here into REAPER's application directory:
* Windows: `%APPDATA%\REAPER`
* MacOS: `~/Library/Application Support/REAPER`
* Linux: `~/.config/REAPER`

So, on Windows for example, the color map for drums should end up in:

`C:\Users\<username>\AppData\Roaming\REAPER\Data\color_maps\colormap_drums.png`

## Usage

Once you copy everything correctly, you should be able to open REAPER, and select `File > Project templates > YARG` to create a new project. After that, start placing notes and then you can save the project in a directory of your choice.

**Tip:** if you name your project `notes.rpp`, the exported .mid file will be automatically called `notes.mid`. Very convenient for iterating quickly!

Happy charting!
