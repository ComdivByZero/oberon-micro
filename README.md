# Oberon в редакторе micro

Редактор [micro](https://micro-editor.github.io/) для терминала.
Проверено для версии 2.0.11

## Установка плагина для сниппетов из самого редактора через Ctrl-e
    plugin install snippets

## Установка из командной оболочки поддержки синтаксиса и сниппетов Oberon
    git clone https://github.com/ComdivByZero/oberon-micro &&
    mkdir -p ~/.config/micro/syntax &&
    cp oberon-micro/oberon.yaml ~/.config/micro/syntax/ &&
    cp oberon-micro/oberon.snippets ~/.config/micro/plug/snippets/snippets/

