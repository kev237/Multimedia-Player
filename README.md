# Multimedia-Player
The program is controlled via menus and toolbars.
The program can display/play multimedia content and supports three formats(vmw, mp4 and mp3).
The program includes the following topics:
- Use of dock widget.
- The creation menu bar.
- Creating actions.
- Creating a toolbar
- Managing resources in a project
- Activate and deactivate actions.
- set markers in a menu.
- hide and show widgets.
- show and hide toolbars at runtime
- creating a context menu.
- Sort entries in a list box.
- Creating status bars and giving them their own icon.

- The form should consist of two areas: On the left, the list of previously opened files shall appear and on the right, the display of the contents. These areas should be 
be displayed at the same time and their width can be changed as desired. 
For this we use a dock widget. What exactly is hidden behind this widget, you will learn in a moment.
- We create the list of open files with a list widget. Each time a file is 
file is opened, the path of the file should be appended to the existing entries in the list. 
list.
- The display of the contents in the right area of the form is done by the class
QMediaPlayer. This class provides all the basic functions for playback. If an audio is played, the right area remains empty.
- The operation of the program shall be done by a menu bar, several toolbars 
and a context menu. In addition we create a status bar, which 
information about the current position in the file and a slider to change the position in the file. 
to change the position in the file.
- In addition to the basic functions such as open and play, the user should also have the option to show or hide certain areas in the form if desired.

Translated with www.DeepL.com/Translator (free version)
