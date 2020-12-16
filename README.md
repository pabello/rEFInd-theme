# Kimono rEFInd theme

![Screenshot_1]()
![Screenshot_2]()

## Installation

1. Clone this repo
2. Remove unnecessary files i.e `.git` folder
3. Figure your refind directory. It usually is `/boot/efi/EFI/refind`
4. Create a folder named `themes`
5. Move `rEFInd-theme` into `themes`
6. Open `/boot/efi/EFI/refind/refind.conf`
7. Add `include themes/rEFInd-theme/theme.conf` at the end of the file.

#### TLDR;
You can use this short shell script although it is not guaranteed to work correctly.
```
git clone https://github.com/pabello/rEFInd-theme.git
rm -rf rEFInd-theme/.git rEFInd-theme/README.md
sudo mkdir /boot/efi/EFI/refind/themes
sudo mv rEFInd-theme /boot/efi/EFI/refind/themes/rEFInd-theme
echo 'include themes/rEFInd-theme/theme.conf' | sudo tee -a /boot/efi/EFI/refind/refind.conf
```

## Attribution
OS icons from [refind-ambience](https://github.com/lukechilds/refind-ambience)
Background by [Thomas Dubois](https://www.artstation.com/thomas_dubois)
