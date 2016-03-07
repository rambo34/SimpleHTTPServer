## How to install Processing HTTP Server

### Install with the Contribution Manager

Add contributed libraries by selecting the menu item _Sketch_ → _Import Library..._ → _Add Library..._ This will open the Contribution Manager, where you can browse for Processing HTTP Server, or any other library you want to install.

Not all available libraries have been converted to show up in this menu. If a library isn't there, it will need to be installed manually by following the instructions below.

### Manual Install

Contributed libraries may be downloaded separately and manually placed within the `libraries` folder of your Processing sketchbook. To find (and change) the Processing sketchbook location on your computer, open the Preferences window from the Processing application (PDE) and look for the "Sketchbook location" item at the top.

By default the following locations are used for your sketchbook folder: 
  * For Mac users, the sketchbook folder is located inside `~/Documents/Processing` 
  * For Windows users, the sketchbook folder is located inside `My Documents/Processing`

Download Processing HTTP Server from http://transfluxus.github.io/SimpleHTTPServer/

Unzip and copy the contributed library's folder into the `libraries` folder in the Processing sketchbook. You will need to create this `libraries` folder if it does not exist.

The folder structure for library Processing HTTP Server should be as follows:

```
Processing
  libraries
    Processing HTTP Server
      examples
      library
        Processing HTTP Server.jar
      reference
      src
```
             
Some folders like `examples` or `src` might be missing. After library Processing HTTP Server has been successfully installed, restart the Processing application.

### Troubleshooting

If you're having trouble, have a look at the [Processing Wiki](https://github.com/processing/processing/wiki/How-to-Install-a-Contributed-Library) for more information, or contact the author [Ramin Soleymani](http://diskordier.net).
