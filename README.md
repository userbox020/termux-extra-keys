# termux-extra-keys

All Arrow Keys

mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout

PAGE UP AND PAGE DOWN + Arrow Keys

mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 &&logout

Function Keys

 mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F12'],['ESC','TAB','CTRL','ALT','-','DOWN','UP']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout
 
 All Keys 
 
 mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F7'],['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout
