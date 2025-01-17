---
description: Пошаговая инструкция как настроить и установить mastercomfig
...

# Как установить mastercomfig

1. [Скачать](https://mastercomfig.com/app) VPK файлы на ваш выбор.
2. Перейдите в свою библиотеку Steam и щелкните правой кнопкой мыши по Team Fortress 2 в списке.
3. Выберите Свойства...
4. Нажмите Локальные файлы...
5. Нажмите Обзор...
6. Перейдите в папку `tf/custom`.
7. Перетащите файлы VPK в папку custom.
8. Установите эти параметры запуска: `-novid -nojoy -nosteamcontroller -nohltv -particles 1 -precachefontchars -noquicktime`. Для получения дополнительной информации прочтите руководство [параметры запуска](../customization/launch_options.md).

## Кастомные конфиги

Если у вас есть какой-либо из следующих файлов, вам нужно будет выполнить некоторые дополнительные действия, чтобы заставить их работать с mastercomfig:

```txt
autoexec.cfg
listenserver.cfg
scout.cfg
soldier.cfg
pyro.cfg
demoman.cfg
heavyweapons.cfg
engineer.cfg
medic.cfg
sniper.cfg
spy.cfg
```

1. Создайте папку `user`, в паке `tf / cfg`.
2. Перетащите эти файлы в созданную папку `user`.

!!! Совет
    Хотя это и не обязательно, если вы перемещаете какие-либо другие файлы (например, `binds.cfg`), вам придется обновить команду `exec` с `exec binds.cfg` на `exec user/binds.cfg`.

## Следующие шаги

### Быстрые исправления

Возникли проблемы? Посмотрите руководство [Быстрые исправления](../next_steps/quick_fixes.md).

### Кастомизация

Хотите еще больше персонализировать свой TF2?

* Посмотри, как ты можешь [настроить индивидуальные настройки](../customization/custom_configs.md)
* Хотите легко настроить сразу несколько настроек? [Ознакомьтесь с модульной системой](../customization/modules.md)
* Настройте свои [параметры запуска](../customization/launch_options.md) для повышения производительности вашей игры
* Вдохновляйтесь чужими [кастомизироваными конфигами](../customization/custom_config_list.md)
* Взгляните на другие [отличные модификации для TF2](../customization/see_also.md)
* [Оптимизируйте свою ОС](../os/index.md) чтобы выжать еще больше производительности
