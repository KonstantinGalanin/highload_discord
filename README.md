# Highload Discord

## 1. Тема и целевая аудитория

Discord — это платформа для общения, предназначенная для создания сообществ, обмена голосовыми, видео, а также текстовыми сообщениями.

### Ключевые функции

- Видеозвонки
- Текстовый чат
- Трансляция экрана
- Сервера (далее - сообщества)
- Возможность создавать множество голосовых комнат для одного сообщества
- Постоянные голосовые комнаты (можно выходить и заходить в любой момент, а не пересоздавать звонок)

### Аналоги

- Zoom
- TeamSpeak
- Microsoft Teams
- VK Звонки

### Пользователи

-  600 миллионов зарегистрированных пользователей [[10]](https://www.demandsage.com/discord-statistics/)
- Более 150 млн уникальных пользователей в месяц (MAU) [[1]](https://helplama.com/discord-statistics/)
- Более 29 млн уникальных пользователей в день (DAU) [[1]](https://helplama.com/discord-statistics/)
- Более 850 миллионов сообщений в день, 25 миллионов из них сделаны с мобильного приложения [[3]](https://venturebeat.com/business/discord-crosses-250-million-users-as-it-hits-4-year-anniversary/)
- Рекордное кол-во одновременных пользователей - 8.2 млн человек[[4]](https://www.cloudwards.net/discord-statistics/)
- 4 млрд минут голосовых разговоров в день [[5]](https://findweb3.com/posts/discord-stats)
- 90% сообществ имеет менее 15 участников [[4]](https://www.cloudwards.net/discord-statistics/)
- Самое большое сообщество - 571,000 участников [[6]](https://www.businessofapps.com/data/discord-statistics/)
- более 19 миллионов сообществ [[8]](https://thesmallbusinessblog.com/how-many-discord-servers-are-there/)
- 590 млн посещений в месяц [[2]](https://pro.similarweb.com/#/digitalsuite/websiteanalysis/overview/website-performance/*/999/1m?webSource=Total&key=discord.com)

#### Целевая аудитория

- Геймеры
- Студенты
- Профессиональные сообщества
- Фандомы
  и т.д.

#### Местоположение аудитории [[2]](https://pro.similarweb.com/#/digitalsuite/websiteanalysis/overview/website-performance/*/999/1m?webSource=Total&key=discord.com)

![location](./images/locations.png)

## 2. Тема и целевая аудитория

### Месячная аудитория

- MAU = 150,000,000

### Дневная аудитория

- DAU = 29,000,000


####

В среднем пользователь отправляет **29,3 сообщения в день**  
// *Всего сообщений в день / DAU = 850,000,000 / 29,000,000 = 29.3 сообщения в день*

На основе проанализированных данных (1291 сообщение):

- Среднее число символов в сообщении составило - 30.75 символов / сообщение
- 4.57% сообщений имели вложенную картинку
- 0.08% сообщений имели вложенный файл

Также на основе проанализированных данных:  
*Рассчитывалось по [таблице](https://www.bankmycell.com/blog/number-of-discord-users/#section-1) с количеством зарегистрированных аккаунтов за каждый год*

- В среднем аккаунту в дискорд ~ 4 года

### Хранилище

Максимальный размер аватарки - 10 Мбайт  
Максимальный размер вложенного файла - 10 Мбайт  
Максимальный размер вложенной картинки - 10 Мбайт, в среднем 2 Мбайт  
Допустим в среднем размер символа равен 2 байта (UTF-8).

#### Средний пользователь отправляет в день:

- Сообщения: 29.3 * 30.75 * 2(байт) = 1,802 байт
- Картинки: 29.3 * 4.57% * 2(Мбайт) = 2,808,108 байт
- Файлы: 29.3 * 0.08% * 10(Мбайт) = 245,787 байт

Итого: 2.915 Мбайт / день = 1.04 Гбайт / год

Память на сообщения для всех пользователей:

- 850,000,000 * (30.75 * 2 + 4.57% * 2(Мбайт) + 0.08% * 10(Мбайт)) = 80.6 Тбайт / день = **28.73 Пбайт / год**

#### Авторизационные данные:

- Аватарка: 2,000,000 байт
- Email: 30 \* 1 байт = 30 байт (254 - макс. размер)
- Пароль: 16 \* 1 байт = 16 байт
- id: 20 \* 1 байт = 20 байт
- Никнейм: 15 \* 1 байт = 15 байт

Итого: 2081 байт на пользователя

На всех пользователей:
600,000,000 \* 2081 = 1,1356 Тбайт

#### **Итого необходимое хранилище:**

- Хранилище на 1 пользователя = 1.04(Гбайт/год) \* 4(года) + 2081(байт) = **4.16 Гбайт**
- Общее хранилище = 28.73(Пб/год) \* 4(года) + 1,1356(Тбайт) = **114.33 Пбайт**

| Параметр               | Хранилище (1 пользователь) |         Общее |
| ---------------------- | -------------------------: | ------------: |
| Текстовые сообщения    |                  7208 байт |   0.004 Пбайт |
| Картинки               |            11,232,432 байт |  105.63 Пбайт |
| Файлы                  |               983,148 байт |    9.24 Пбайт |
| Авторизационные данные |                  2081 байт |   0.001 Пбайт |
| Общее                  |                 4.16 Гбайт | 114.875 Пбайт |

### Сетевой трафик

&nbsp;&nbsp;&nbsp;&nbsp;Пиковая нагрузка дискорд в 2018 году составила одновременно более 2.6 миллиона пользователей голосового чата с исходящим с трафиком более 220 Гбит/с и 120 млн пакетов/с [[7]](https://habr.com/ru/articles/423171/)
<br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;В 2018 году DAU составлял 8.9 миллионов пользователей, с учетом текущего DAU рассчитаем примерную пиковую нагрузку на данный момент:

- 2.6 миллиона \* 29,000,000 / 8,900,000 = **8.47 миллиона пользователей голосового чата**
- 220 Гбит/с \* 29,000,000 / 8,900,000 = **717 Гбит/с**
- 120 млн пакетов/с \* 29,000,000 / 8,900,000 = **391 млн пакетов/с**

=> В среднем на одного пользователя видео-чата трафик = 88 Кбит/с

#### Средний трафик в секунду для видео звонков

- Каждый день в среднем в дискорде происходит 4 млрд минут голосовых разговоров в день
- Средний трафик звоноков в день: 4 (млрд мин) * 60 * 88 Кбит/с = 20,141,602 Гбит/день
- Средний трафик в секунду: 20,141,602 Гбит / (24 * 60 * 60) = 233.2 Гбит/с

#### Средний трафик отправки сообщений в секунду

- Общий трафик отправки сообщений в день = 80.6 Тбайт/день = 82,534.4 Гбит/день (из предыдущих вычислений)
- Общий трафик отправки сообщений в секнуду: 80.6 Тбайт/день / (24 * 60 * 60) = 7.64 Гбит/с

#### Общий (средний) трафик

- 233.2 Гбит/с + 7.64 Гбит/с = **240.84 Гбит/с**

### Итого трафик:

Коэффициент запаса на пиковое потребление относительно среднего для видеочата = 717 Гбит/с / 233.2 Гбит/с = 3.08 Гбит/с  
Пиковый трафик для сообщений = средний трафик для сообщений * коэффициент запаса = 7.64 Гбит/с * 3.08 Гбит/с = 23.53 Гбит/с

| Тип трафика |    Общий суточный |       Средний |       Пиковый |
| ----------- | ----------------: | ------------: | ------------: |
| Видеочат    |   20,141,602 Гбит |  233.2 Гбит/с |    717 Гбит/с |
| Сообщения   |     82,534.4 Гбит |   7.64 Гбит/с |  23.53 Гбит/с |
| Всего       | 20,224,136.4 Гбит | 240.84 Гбит/с | 740.53 Гбит/с |

#### Метрики запросов:

Сообщества:  
&nbsp;&nbsp;&nbsp;&nbsp;Существует более 19 млн сообществ, 90% из которых имеют менее 15 подписчиков  
&nbsp;&nbsp;&nbsp;&nbsp;Предположим, что в среднем 90% сообществ имеею 7 подписчиков, а оставшиеся 10% - 100 подписчиков

- Всего подписчиков = 19 млн * 90% * 7 + 19 млн * 10% * 100 = 309,700,000 подписчиков
- Кол-во запросов на подписку в секунду = 309,700,000 / ( 9(лет) * 365 * 24 * 60 * 60) = 1.1 запрос/секунду

Предположим, что чтения сообщений в 10 раз больше, чем отправки сообщений  
Предположим, что средний активный пользователь заходит в 3 голосовые комнаты в день  

| Запрос                     | Пользователь (раз/день) | Общее количество (раз/день) |    RPS |
| -------------------------- | ----------------------: | --------------------------: | -----: |
| Отправить сообщение        |                    29.3 |                 850,000,000 |   9838 |
| Чтение сообщения           |                     293 |               8,500,000,000 |  98380 |
| Вход/выход в голосовой чат |                       6 |                  90,000,000 |   1041 |
| Подписка на сообщество     |                         |                             |    1.1 |
| Всего                      |                         |                             | 109260 |

<!-- | Отправить картинку    | 1.4    | 38,845,000    |
| Отправить файл| 0.02 | 680,000| -->

## Список источников

1. https://helplama.com/discord-statistics/
2. https://pro.similarweb.com/#/digitalsuite/websiteanalysis/overview/website-performance/*/999/1m?webSource=Total&key=discord.com
3. https://venturebeat.com/business/discord-crosses-250-million-users-as-it-hits-4-year-anniversary/
4. https://www.cloudwards.net/discord-statistics/
5. https://findweb3.com/posts/discord-stats
6. https://www.businessofapps.com/data/discord-statistics/
7. https://habr.com/ru/articles/423171/
8. https://thesmallbusinessblog.com/how-many-discord-servers-are-there/
9. https://www.bankmycell.com/blog/number-of-discord-users/#section-1
10. https://www.demandsage.com/discord-statistics/
