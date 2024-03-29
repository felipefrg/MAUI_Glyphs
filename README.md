
# MAUI Glyphs

This project has the purpose of showing how to use custom fonts in MAUI

It was made using Visual Studio 2022 Version Version 17.9.0 and .NET 8




## First step
Add your ttf/otf file inside the Resources -> Fonts folder and make sure that build action "Mauifonts" was selected (right-click -> properties -> build action)

![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/folder.png)

## Second step
Go to MauiProgram.cs and add your ttf file and an alias for that in the builder, inside the ConfigureFonts method, like the sample below

.ConfigureFonts(fonts =>
{
	fonts.AddFont("icomoon.ttf", "icomoon");
}

![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/mauiprogram.png)

## Third step
Use your custom font in the label specifying FontFamily property
![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/label.png)

## Result
![App Screenshot](https://raw.githubusercontent.com/felipefrg/MAUI_Glyphs/main/sc/result.png)

