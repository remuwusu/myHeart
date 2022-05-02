bueno dia mi gente hoy vamo a hacé uno proyeto to guapo un abraso grasia
este corazón se supone que lo tengo que crear en python pero como alacritty no soporta imagenes (gracias dev), entonces vamos a usar una cosa sencilla en una shell de bash
pero para eso hay que correr:

[terminal@remuwusu]$ cd ~/.config |
[terminal@remuwusu / .config]$ sudo mkdir yourHeart/ |
[terminal@remuwusu / .config]$ cd yourHeart/ |
[terminal@remuwusu / yourHeart]$ sudo touch myLove.ini |
[terminal@remuwusu / yourHeart]$ sudo nano myLove.ini |

# GNU nano 6.3
#! bin/sh/
exec_always --no-startup-id $HOME/remuwusu/.config/yourHeart/myLove.ini

# myLove.ini
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

# end
