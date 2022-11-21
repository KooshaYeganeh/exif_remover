# exif_remover
Scripts for Find Exif Data in images and Try to remove them

**Note: For security reasons, it is better to run this script from time to time to clear all the EXIF information in the system**


# Install
[Installing ExifTool](https://exiftool.org/install.html)  
[GitHub](https://github.com/exiftool/exiftool.git)

**1- for First Install exiftool**

## Ubuntu

`sudo apt install exiftool`

## Fedora

`sudo dnf install perl-Image-ExifTool`

## OpenSuse

`sudo zypper install perl-Image-ExifTool`

**2- Download ExirRemover**

`wget https://github.com/KooshaYeganeh/exif_remover/archive/refs/heads/main.zip`

`unzip main.zip`

`cd exif_remover-main`

`sudo mv exifremover /usr/bin`


# Remove

## Ubuntu

`sudo apt remove exiftool`

## Fedora

`sudo dnf remove perl-Image-ExifTool`

## OpenSuse

`sudo zypper remove perl-Image-ExifTool`


> Remove exifremover: `sudo rm /usr/bin/exifremover`
