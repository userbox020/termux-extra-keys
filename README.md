
# Setup storage if you havent, is not needed for extra keys but it's something you going to use a lot

termux-setup-storage


# termux-extra-keys

All Arrow Keys

mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout

![image](https://user-images.githubusercontent.com/47074021/203642733-f18f6e21-85aa-4f24-9b25-b68426b9af2c.png)


PAGE UP AND PAGE DOWN + Arrow Keys

mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 &&logout

![image](https://user-images.githubusercontent.com/47074021/203642772-979fd8c0-1c9a-4f3d-bc51-639258a1cfba.png)


Function Keys

 mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F12'],['ESC','TAB','CTRL','ALT','-','DOWN','UP']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout
 
 ![image](https://user-images.githubusercontent.com/47074021/203642803-6b1f7f9a-0b2d-4fd0-97aa-62d1bfbb0fab.png)

 
 All Keys 
 
 mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F7'],['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout

![image](https://user-images.githubusercontent.com/47074021/203642829-e80ec35a-23cb-4946-a331-5a70d76b9c2a.png)
