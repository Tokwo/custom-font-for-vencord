# custom-font-for-vencord
An editable file that you can use to customize Discord font as a theme in Vencord

# Instructions
Download CustomDiscordTheme.theme.css

Open Discord settings > go to Vencord section > find Themes > make sure you are in the Local Themes tab > Click "Open Themes Folder" > Place the CustomDiscordTheme.theme.css file in your themes folder. 

You can edit the file as you wish. As long as the font you want is on https://fonts.google.com

Here's an example with the following font: https://fonts.google.com/specimen/Epunda+Slab

Change the import url text between "css2?" and ":ital," with the name of the font in the url. Like so: "Epunda+Slab".

Next change the other font names on lines 10 and 11 (after it says "--font-prinmary:") to the same name with a space instead of "+"; ex: "Epunda Slab". Only do this for the first font on each line. I haven't tested, but it may break your discord if you delete the others.

That's it. Make sure to save. You can change the @description or @name or whatever you want in the file, but I reccomend to do that last.
