# Мастерская

> Активные проекты

#### https://github.com/realicedicerice/aidoru

_2024_

Player-бот который играет музыку на нотных блоках на нашем майнкрафт сервере. В майнкрафте на нотных блоках можно реализовать 25 разных тональностей, что-то типа 2 октавы. Бот принимает на вход произвольный midi файл и _tries his best_ сыграть его на нотных блоках на этих тональностях. Для интерфейса с сервером майнкрафта используется minecraft-protocol. Самодельный парсер миди. Демо видео: https://www.youtube.com/watch?v=h9Xhw_L7VwQ

#### https://github.com/realicedicerice/chaosgrad

_2024_

Это самое местечко

# Лаборатория

> Эксперименты, необязательно завершенные, необязательно практичные проекты и репозитории

#### https://github.com/realicedicerice/atom-animation-webgl

_2023_

Попытка реализовать анимацию абстрактного атома в вакууме шейдерами на webgl. Демо: https://realicedicerice.github.io/atom-animation-webgl

# Музей

> Рабочие, но неподдерживающиеся проекты, проекты "на раз"

#### https://github.com/realicedicerice/twitch-suggested-graph

На твиче стример может рекомендовать других стримеров. Эта утилита делает запросы к graphql эндпоинтам твича для получения этой информации. Это не открытый апи, поэтому довелось сделать немного дебагинга на сайте твича, чтоб узнать эндпоинты, ключ апи и названия полей в схеме. А далее строит граф кто кого рекомендует. Демо: https://realicedicerice.github.io/twitch-suggested-graph. В "Root account" вписывается имя аккаунта от которого начинать поиск (breadth-first search получается).

![](https://media.discordapp.net/attachments/312761588778139658/1168097678614331442/IMG_20231029_130221_941.jpg?width=320&height=610)

# Кладбище

> Очень давние и уже неработающие или ненужные проекты

#### https://github.com/macsmac/modexplorer

_2018_

modexplorer - Утилита для сайта CurseForge, где выложены моды на майнкрафт. Позволяла искать и скачивать моды. Также позволяла сверять sha256 чексуммы имеющихся файлов с актуальными версиями на сайте, это делалось для обнаружения возможных несанкционированных (ну либо же непреднамеренных) изменений файлов. Открытого апи у сайта нет, парсинг страниц реализовывался самостоятельно.

#### https://github.com/yioyo3/ruminepp

_2018_

Расширение для сайта ru-minecraft. Основная идея была расширить функционал сайта, так как админы этим почти никогда не занимались. Функционал включал в себя: Автообновление сообщений на форуме, поддержку мультиаккаунта, сохранение истории редактирования сообщений на форуме и другие мелкие улучшения.

# Святыня

> Проекты, для которых не сохранился код, но которые были значимыми и о которых можно рассказать

#### Легенда о боте вк "Гена"

_circa 2015-2017_

В далеком 2015 году я начинал заниматься разработкой на Node.JS. Бот Гена стал моим первым большим начинанем. Когда ещё во вконтакте не было возможности отправлять сообщения группам, мы занимались разработкой ботов на пользовательских страницах. А "мы" - это некая банда (беседа в вк) разработчиков ботов, в которую я уже точно не помню как попал. Во главе кстати был Котляров https://vk.com/eee, shout out ему. Апи вконтакте позволял слушать сообщения и отвечать, боты принимали команды в виде сообщений от пользователей. У нас были свои боты, мой бот был Гена (Крокодил Гена). У Гены было много различных команд - поиск картинок, поиск по википедии, генератор случайных чисел, выбор случайного пользователя, обработка картинок (реализованная на node-canvas-е) и т.д. А еще с Геной можно было общаться. Для этого нагло использовался сайт xu.su (типа чат-бот), куда с Гены посылался текст сообщений, и откуда пользователям возвращались ответы. Аудитория на пике была довольно большая, заявки в друзья на странице Гены принимались автоматически и уже через некоторое время достигли лимита друзей в вк - 10000. А потом про бота узнали в моем тогда ещё 7-ом классе и все начали его пользовать :). От частоты запросов к апи вк часто требовал вводить каптчу, это решалось внедрением сервиса человеческого распознавания каптч rucaptcha. В целом этот проект многому меня научил, здесь применялось много разных технологий и решений - от баз типа mongodb и redis, до решений обработки изображений, прокси, обхода cloudflare, каптчи. А хостилось это всё у меня дома на малинке.

#### Побасёнка о Geometry Memes

_circa 2017_

Некоторое время участвовал в администрировании паблика вк по игре Geometry Dash называемому Geometry Memes. В частности я зачем-то сделал веб-интерфейс, единственной целью которого было показывать этот паблик. Зачем? Не помню... Оно было с bootstrap и jquery.

- https://web.archive.org/web/20240115114810/https://vk.com/wall-127306075_14999

#### Напасть о JS визуализаторе музыки

В этот период я также занимался проектом визуализатора аудио в браузере. Использовался нативный fft и визуальные элементы отрисовывались на канвасе. А потом... напасть приключилась! В Geometry Memes у меня был знакомый, назовём его Л. Л взял мой визуализатор и пошёл с ним на местную олимпиаду по программированию и выиграл. Л спёр мой визуализатор!
