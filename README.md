# Tauon Music Box

Tauon Music Box is a streamlined standalone desktop music player with a focus on minimal configuration and user file organisation.
Designed to have an easy to use, comfortable and compact user interface.

### Features

  - Playback support for MP3, OGG, FLAC + others
  - CUE sheet support
  - Large album art display
  - Last.fm scrobbling
  - Playtime representation
  - Quick search
  - Asynchronous outbound streaming
  - Multi-platform (Windows and Linux)

### Getting Started

Download latest binary release from releases section (todo).
Extract archive to a user directory of your choosing.
On Windows start program by running 'tmb.exe'. On linux use the following commands to install dependencies:

Arch Linux:

        $ sudo pacman -S python3 sdl2 sdl2_image sdl2_ttf xclip python-pip python-pillow
        $ sudo pip3 install hsaudiotag3k pylast pyperclip pysdl2 python3-xlib flask

Ubuntu (not recently tested):

        $ sudo apt-get install libsdl2-2.0-0 libsdl2-ttf-2.0-0 libsdl2-image-2.0-0 python3-pip xclip python3-pil
        $ sudo pip3 install hsaudiotag3k pylast pyperclip pysdl2 python3-xlib flask

Finally run using python 3, alternatively create a desktop or launcher shortcut
(Make sure to set the working directory to the directory you extracted the program files to).

    $ python3.5 tmb.py



