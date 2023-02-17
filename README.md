# exif_remover
Scripts for Find Exif Data in images and Try to remove them

**Note: For security reasons, it is better to run this script from time to time to clear all the EXIF information in the system**

**READ More About Exif Data**
[Link1](https://beaglesecurity.com/blog/vulnerability/exif-data-information-leakage.html)  
[Link2](https://www.kaspersky.com/blog/exif-privacy/13356/)


# Install
[Installing ExifTool](https://exiftool.org/install.html)  
[GitHub](https://github.com/exiftool/exiftool.git)

**1- for First Install exiftool**

## Ubuntu

```
sudo apt install exiftool
```
## Fedora

```
sudo dnf install perl-Image-ExifTool
```
## OpenSuse

```
sudo zypper install exiftool
```
**2- Download and Install ExifRemover**

```
wget https://github.com/KooshaYeganeh/exif_remover/archive/refs/heads/main.zip && unzip main.zip && cd exif_remover-main && sudo mv exifremover /usr/bin && echo "ExifRemover Installed [ OK ]"
```

# Remove

## Ubuntu

```
sudo apt remove exiftool
```

## Fedora

```
sudo dnf remove perl-Image-ExifTool
```
## OpenSuse

```
sudo zypper remove exiftool
```
**Remove exifremover :**

```
sudo rm /usr/bin/exifremover
```
