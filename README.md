# rEFInd-theme
My theme for the [rEFInd](http://www.rodsbooks.com/refind/) boot manager.

![Screenshot](https://github.com/pixix4/rEFInd-theme/blob/master/screenshot.png?raw=true)

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-theme/theme.conf` at the end of
    `refind.conf`.

This theme is inspired from [rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal).
