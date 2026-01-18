<img width="1920" height="1080" alt="Снимок экрана_20260118_235130" src="https://github.com/user-attachments/assets/873e601b-d088-4699-9d04-918286a152ab" />

### Как устанавливать:

0. Иметь систему с LXQt и Openbox

1. Установить picom:

```sudo pacman -S picom```

Папку *picom* переместить в /home/username/.config (username - ваше имя пользователя). Можно командой:

``` sudo mv ~/picom /home/username/.config```

2. Папку *tema-de* переместить в /usr/share/lxqt/themes командой:

```sudo mv ~/tema-de /usr/share/lxqt/themes```

3. Через настройки OpenBox установить тему *tema-wm.obt*

4. Нижнюю панель переместить наверх, снизу создать новую панель с меню приложений, меню каталога и панелью задачь. Наверху добавить всякой хуйни по вкусу. Часы я сделал с помощью формулы:

```'<b>'H:mm' <font size="3">// 'ddd, d MMM```

5. Розовую папку для меню каталога можно сделать нажав по нему правой кнопкой мыши и выбрав в значке *folder.svg*
