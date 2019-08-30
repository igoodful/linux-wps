https://linux.wps.cn/
sudo apt-get remove libreoffice-common
sudo apt-get remove unity-webapps-common
sudo apt autoremove
unzip wps_symbol_fonts.zip
sudo cp mtextra.ttf  symbol.ttf  WEBDINGS.TTF  wingding.ttf  WINGDNG2.ttf  WINGDNG3.ttf  /usr/share/fonts/
sudo mkfontscale
sudo mkfontdir
sudo fc-cache
