# Themes for Grub
Two simple themes for Grub. One based on the artistic rendering of planet Kepler 186f and the other based on the extraordinary Hayao Miyazaki _lungometraggio_ Porco Rosso.

## Kepler 186f

Simple Sci-Fi styled GRUB Theme. It is based on the artistic rendering of the planet Kepler 186f.
The rendering is available from NASA [here](https://www.jpl.nasa.gov/images/pia17999-kepler-186f-the-first-earth-size-planet-in-the-habitable-zone-artists-concept/)

## Porco Rosso
The [iconic masterpiece](https://en.wikipedia.org/wiki/Porco_Rosso) from Hayao Miyazaki, means to me more than I can utter. 
With every day that the world keeps destabilizing and de-humanizing people, I believe this opera can serve the purpose 
of showing the importance kindness and the importance of making a stand when you detached yourself from the absurdity 
embracing life around.

I have two versions of this:
* simple
* colourful

Simple version is inspired by the fonts of [Space Isolation](https://www.gnome-look.org/p/2296342) theme.
![Porco Rosso](porco_rosso/Screenshot_20260108_135640.png "Porco Rosso - Simple theme")

The colourful version is still only a prototype in GIMP.
![Porco Rosso](porco_rosso/prototype.png "Porco Rosso - Simple theme")

## Installation:

Download and unzip or clone the repository and then move the theme you want `kepler_186f` or `porco_rosso` folder into `/boot/grub/themes` directory.
Make sure you are pointing at the right theme by editing the /etc/default/grub.
Change the line regarding GRUB_THEME to the path (in the example, I selected the kepler theme)
```
GRUB_THEME=/boot/grub/themes/kepler_186f/theme.txt
```

Run the command sudo update grub theme. `grub-mkconfig -o /boot/grub/grub.cfg`
