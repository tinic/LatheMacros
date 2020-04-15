# LatheMacros

This config demonstrates the Lathe macros described here:
 http://www.linuxcnc.org/index.php/english/forum/41-guis/26550-lathe-macros
To add the macros to your own config you need to add this line to the INI file [DISPLAY] section:
[DISPLAY]
EMBED_TAB_NAME=Cycles
EMBED_TAB_COMMAND=halcmd loadusr -Wn gladevcp gladevcp -c gladevcp -u lathehandler.py -x {XID} lathemacro.ui

Then put these files in the same directory as the INI file. 
Bore.png
boring.ngc
chamfer.png
chamfer.ngc
facing.ngc
Facing.png
radius.ngc
radius.png
Threading.png
threading.ngc
turning.ngc
Turn.png
lathehandler.py
lathemacro.ui
