# Fancy Lockscreen
## Layered images, image gallery, clock, and weather
![Demo of the wallpaper lock screen with all features present](https://raw.githubusercontent.com/F-alling/fancy-lockscreen/refs/heads/main/.gitignore/demo.gif)


# Install guide:

## Note: I am not responsible if you mess up anything on your KDE install using this.

1: Download the project as a .zip file by clicking [here](https://github.com/F-alling/fancy-lockscreen/archive/refs/heads/main.zip)

2: Extract the downloaded `main.zip` file

3: 
- a: Move the items in the `qml-files` folder to `/usr/share/plasma/shells/org.kde.plasma.desktop/contents/lockscreen/`
- b: Move the items in the `plasma-plugin` folder to `/home/arch/.local/share/plasma/wallpapers/`
  
4: Log out and back out of your KDE Session

5: Change settings for correct lockscreen appearance
- a: Open the `config.js` file in `wallpaper-foss` folder.
- b: Change the `basePath` variable to the absolute path of the `wallpaper-foss` folder. (keep `file://`)
- c: Change the Latitude, Longitude, and Elevation to the correct points for your location
- d: Change the `galleryImages` files to the name of your specificed media. (optional)
- e: Change the `wallpaper` and `foreground` files to the name of your background (optional, requires setup)
- f: Save your changes
  
6: Change KDE Settings
- a: Open the KDE Settings app (System Settings)
- b: Go to the Screen Locking catagory
- c: Click "Configure Appearance"
- d: Change "Wallpaper type" to "HTML Wallpaper" 
- e: Change the website location to `file://` followed by the absolute path of your wallpaper-foss folder and `index.html`
- f: Save your settings

7: Lock your screen and enjoy!








## Copyright notices

This is project uses the following assets owned by the following creators:
- MacOS Montery Dark - Apple Inc.
- San Francisco typeface - Apple Inc.
- HTML Wallpaper Plugin - [MarcelRichter](https://github.com/MarcelRichter-GitHub)
- QML Files - KDE e.V.
- Example Gallery Images - [Me](https://github.com/f-alling)
