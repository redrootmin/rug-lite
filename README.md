
###RUG - Rosa Utility for GAMING - КОВРИК###
-----------
rug-lite - простая консольная утилита, которая в автоматическом режиме изменит и оптимизирует ваш дистрибутив rosa linux (gnome) для игр и творчества с максимально удобным, информативным функционалом оболочки gnome


УСТАНОВКА RUG-LITE на ROSA FRESH 12.4+ (GNOME)
-----------

открываем терминал (CTRL+ALT+T) и вводим:
```
sudo dnf install -y yad gtksourceview3 lib64gtksourceview-3.0_1 pv;cd;rm -f rug-lite;rm -f
/home/$USER/.local/bin/rug-lite;rm -f rug-lite*;wget http://raw.githubusercontent.com/redrootmin/rug-lite/main/rug-lite;mkdir -p -v /home/$USER/.local/bin;mv -f rug-lite /home/$USER/.local/bin;chmod +x /home/$USER/.local/bin/rug-lite && echo "rug-lite-установлен"
```

после установки доступны следующие команды в терминале:
```
-t или --test           - тест системы на совместимость и проверка ресурсов
-i или --install        - автономная установка всего пакета rug-lite
```
пример: 
rug-lite --test

ВНИМАНИЕ: в начале установки утилита попросил пароль супер пользователя (root) для установки ПО и изменения настроек системы которые не доступны с обычными правами пользователя