#Download filezilla
wget https://dl2.cdn.filezilla-project.org/client/FileZilla_3.62.0_x86_64-linux-gnu.tar.bz2?h=lHCuVtCL-cCNF-M67aMSOg&x=1668665280

#Extract
tar -xf FILENAME.tar.bz2




#Add desktop icon file using below command paste (code in backet) in this file 

sudo nano ~/.local/share/applications/filezila.desktop

{{{{ 
Desktop Entry]
Version=x.y
#Name 
Name=filezilla3
Comment=This is my comment
#filezilla extract path 
Exec=/home/DEV/FileZilla3/bin/filezilla
##filezilla icon 
Icon=/home/DEV/FileZilla3/bin/file.png
Terminal=false
Type=Application
Categories=Utility;Application;

}}}



