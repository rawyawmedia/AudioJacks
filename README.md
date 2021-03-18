# WARNING NOT YET COMPLETE, DO NOT USE, PLEASE CHECK AGAIN OR FOLLOW FOR FINAL RELASE
https://github.com/clacktronics/AudioJacks

# AudioJacks
KiCAD footprint library and 3D models for commonly used connectors used in synths and other audio equipment.

# Directory structure
* 3Dmodels - The .step files used by KiCAD for the PCB rendering
* AudioJacks.pretty - the KiCAD footprint library
* Assets - Images and other items used for this documentation
* FreeCAD_Drawings - The modifiable FreeCAD used to generate the 3dmodels

# Installation (KiCAD 5.1)

### Footprints via footprint editor
* Copy to chosen location for your custom KiCAD libraries, this could be the default one or anywhere on your disk.
* Open the footprint editor and choose `File > Add Library` pick the `AudioJacks.pretty` folder and click open
* Choose `Global` as the file table to add it to 

### Footprints via PCBnew
* Select `Preferences > Manage footprint libraries`
* Under `Global Libraries` tap, choose the folder icon `Add existing library to table`
* Find `AudioJacks.pretty` and press open

### Using the 3D models
I am still undecided how this works, I need to investigate how best this works. Adding 3D files manually puts in an absolute directory based on it's location on the computer so when the project is shared the models can not be found.

# Connectors in library
Here is a summary of the contents, please not they may not be the original manufacturers but where I sourced the reference connector.

### Cliff FCR1281 / CL1384
Common type used on Doepfer and Expert Sleepers
![FCR1281](assets/FCR1281.jpg)

### QuingPu PJ301BM
Sheilded connector a little like the PJ398SM, popularised by [Earthenvar](http://erthenvar.com/blog/improved-jacks-now-shipping/)

### QuingPu PJ301CM
Stereo jack

### QuingPu PJ302M
Commonly used side mounting mono jack in Eurorack

### QuingPu PJ366ST
Stereo jack in a similar shape to PJ398SM but not exactly the same

### QuingPu PJ398SM
AKA [Thonkiconn](https://www.thonk.co.uk), very commonly used eurorack jack sold by many suppliers like Thonk. 3D model options with Knurled nut, hex nut and no nut.

### QuingPu PJ301M-12
The original "Thonkiconn" looks a little different (different 3D model) but same footprint as PJ398SM

### QuingPu PJ3410
'NV' jack (Kits by ['NV'](https://www.muffwiggler.com/forum/viewtopic.php?t=79912) on Muffwiggler) Taller vertical mount 3.5mm jack

# FAQ
* Can you add xxx jack to the library? - Yes add a feature request to issues on Github
* My footprint did not work when after I got it from the manufacturer! - I try to test the files the best I can, but I can not guaruntee it, it is up to you to take responsibility for the design. If you have a problem with a footprint please open an issue on Github
* Can I contribute my files to this library? - Yes, read `CONTRIBUTING.md` to check a few simple design rules I follow. I can not guaruntee my response speed.
* Your descriptions are wrong for the parts! - Please let me know if you see any errors, the descriptions try and hint what audio/Eurorack kits they are used in to help finding the right ones, they may not be complete.

# Licence

I have attached an MIT licence, it is free to use and modify for any use. I don't beleive in licences as they are only useful for the super wealthy who can afford gambling on litigation and in the end the only people that really win are the lawyers. Hopefully it will help if you need the proof that I won't come after you, all work here is original, no files are derivative of other copyrighted work such as manufacturer 3D models for example.
