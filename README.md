# cash-Drawer-Ubuntu-20.04-opening
This is script , an app and explanation on how to use cash drawer opening it worked for Epson Thermal printer and for SNBS thermal printer equally well
Use lpstat -p to find out your ptiner name

Following line should open till in terminal:
echo -en '\033p011' | lp -d EPSON_TM-T20III -o raw

of course replace EPSON with your printer name. 

If that works it is reocmmended to create shorter alias in ~/.bashrc or /etc/bash.bashrc

modify opentill.sh with your pritner name and make it executable place it in ~/Documents/ or modify patch in myGuiapp.desktop

place icons folder in ~/Documents/ or modify it as above

put myGuiapp.desktop in ~/.local/share/applications

this app should open cash drawer connected to thermal printers




