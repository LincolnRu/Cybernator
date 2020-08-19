### Параметры
|           Имя             |                     Тип                     |По умолчанию|                           Информация                                |
|:-------------------------:|:-------------------------------------------:|:----------:|:-------------------------------------------------------------------:|
|           ctx             | `discord.Client` `discord.ext.commands.Bot` |            |                                                                     |
|         message           |              `discord.Message`              |            |       Сообщение, которое будет использовано для Paginator`a         |
|          embeds           |                    `list`                   |   `None`   |                        Список embeds.                               |
|    timeout `<optional>`   |                    `int`                    | `30`секунд |        Время после которого Paginator заканчивает работу.           |
|   use_more `<optional>`   |                    `bool`                   |   `False`  |            Добавление 2/4 реакций (По умолчанию 2)                  |
|   use_exit `<optional>`   |                    `bool`                   |   `False`  |            Добавление отключения пагинатора реакцией                  |
|delete_message `<optional>`|                    `bool`                   |   `False`  |Удалить Paginator по истечении таймера(если False, то уберет реакции)|
|      only `<optional>`    |              `discord.abc.User`             |   `None`   |    Позволит использовать команду тому, кто её вызвал (ctx.author)   |
|  time_stamp `<optional>`  |                    `bool`                   |   `False`  |                 Добавление времени вызова команды                   |
|    footer `<optional>`    |                    `bool`                   |   `True`   |                     Подпись Раздел-Страница                         |
|   reactions `<optional>`  |                    `list`                   |["⬅", "➡"] | Можно стандартные смайлики поменять на свои (['👀', '<:bot:673508314008649749>']|
|more_reactions `<optional>`|                    `list`                   |["⬅", "➡", "⏪", "⏩"]|           Можно стандартные смайлики поменять на свои    |
| exit_reaction `<optional>`|                    `list`                   |["⏹"]|           Можно стандартный смайлик поменять на свой    |
|   language `<optional>`   |                     `str`                   |    `ru`    |                     Выбор языка (`ru`, `en`)                        |
|     color `<optional>`    |                     `int`                   |   `None`   |      Можно установить 1 цвет на все страницы, HEX (0x000000)        |
|   footer_icon `<optional>`   |                     `str`                   |    `None`    |  URL-адрес значка нижнего колонтитула. Поддерживается только HTTP(S).    |
