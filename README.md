# Description

bueno dia mi gente hoy vamo a hacé uno proyeto to guapo un abraso grasia
este corazón se supone que lo tengo que crear en python pero como alacritty no soporta imagenes (gracias dev), entonces vamos a usar una cosa sencilla en una shell de bash
pero para eso hay que correr:

# Cosas de la terminal

[terminal@remuwusu]$ cd ~/.config 

[terminal@remuwusu / .config]$ sudo mkdir yourHeart/ 

[terminal@remuwusu / .config]$ cd yourHeart/ 

[terminal@remuwusu / yourHeart]$ sudo touch myLove.sh

[terminal@remuwusu / yourHeart]$ sudo nano myLove.sh


# i3 config

#! bin/sh/

exec_always --no-startup-id $HOME/(yourUsr)/.config/yourHeart/myLove.sh


# myLove.sh

#! bin/sh/

cat << EOF

 
 \e[0;91m   █████      █████     \e[0m
 
 \e[0;91m ████████    ████████    \e[0m
 
\e[0;91m ██████████████████████     \e[0m

 \e[0;91m ████████████████████    \e[0m
 
 \e[0;91m   ████████████████      \e[0m
 
  \e[0;91m    ████████████        \e[0m
  
  \e[0;91m     ██████████       \e[0m
  
  \e[0;91m       ██████       \e[0m
  
  \e[0;91m        ████    \e[0m
  
  \e[0;91m         ██  \e[0m
  
          
EOF

# ////////// End /////////
