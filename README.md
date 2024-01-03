
# MAUI Glyphs

This project has the purpose to showing how to use custom fonts in MAUI

It was made using Visual Studio 2022 Version Version 17.9.0 and .NET 8




## First step
Add your ttf/otf file inside Resources -> Fonts folder and make sure that build action "Mauifonts" was selected (right click -> properties -> build action)
![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/folder.png)

## Second step
Go to MauiProgram.cs and add your ttf file and an alias for that in buider, inside ConfigureFonts method, like the sample below

.ConfigureFonts(fonts =>
{
	fonts.AddFont("icomoon.ttf", "icomoon");
}

![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/mauiprogram.png)

## Third step
Use your custom font in label specifying FontFamily
![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/label.png)
