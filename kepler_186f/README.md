# Kepler 186f

Simple Sci-Fi styled GRUB Theme. It is based on the artistic rendering of the planet Kepler 186f.
The rendering is available from NASA [here](https://www.jpl.nasa.gov/images/pia17999-kepler-186f-the-first-earth-size-planet-in-the-habitable-zone-artists-concept/)

## Installation:

Download and unzip or clone the repository and then move the `kepler_186f` folder into `/boot/grub/themes` directory.
Make sure you are pointing at the right theme by editing the /etc/default/grub.
Change the line 
```
#GRUB_THEME=
```
to
```
 #GRUB_THEME=/boot/grub/themes/kepler_186f
```

I have used the following command to generate the font
```commandline
sudo grub-mkfont --output=/boot/grub/fonts/FragileBombers.pf2 --size=20 /usr/share/fonts/Fragile\ Bombers.otf
```

Run the command sudo update grub theme. `grub-mkconfig -o /boot/grub/grub.cfg`



