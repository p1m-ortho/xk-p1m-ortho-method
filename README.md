# Методичка для участников p1m-ortho

*Оповещение*

> Поскольку состав участников `p1m-ortho` на момент этого коммита выполнен целиком студентами и ординаторами, то и методичка рассчитана сейчас сугубо на эти контингенты. По мере расширения круга участников методичка может быть значительно изменена.

> Методичку предлагается читать с конца. Идея — в том, чтобы ее разделы выстраивались в хронологическом порядке, по мере их добавления, и наиболее свежие сразу оказывались на виду, а наиболее старые как наиболее фундаментальные, как и полагается, оказывались в фундаменте. Как видно из истории коммитов, методичка — пока в очень и очень черновом варианте, и со временем может быть полностью переписана.

> `p1m` — это [Pavlov 1st Medical](http://en.1spbgmu.ru). `ortho`, понятное дело, это ортопедия, травматология и ортопедия, ортопедическая хирургия и все такое.

> Авторы: [@pussiatoday](https://github.com/pussiatoday)

## 5 Рекомендуемая литература

* Studying a Study and Testing a Test Ричарда Ригелмана в 5-м издании.

* CDC Principles of Epidemiology, веб-издание.
Введение в эпидемиологию от CDC (Centers for Disease Control and Prevention — Роспотребнадзор в США).

* Biostat Handbook доктора Джона Макдоналда.

* Cochrane Handbook 5.1 и главы из черновой редакции 6-го издания.

* PRISMA с расширениями.
Доступно на EQUATOR Network. 

* CONSORT с расширениями.
Доступно на EQUATOR Network.

* PubMed Help.
Справочная документация к поисковому интерфейсу PubMed.

## 4 Техническая часть

## 4.8 Где пишутся методы по репозиторию
См. историю коммитов для файла `METHOD.md` в интересующем репозитории. См. например для этого репозитория: https://github.com/p1m-ortho/xk-p1m-ortho-method/commits/master/METHOD.md.

Конкретно для этого репозитория, предназначенного для ведения методического пособия по p1m-ortho, история коммитов `METHOD.md` отражает изменения, происходящие с самим предметом этого методического пособия, а именно с организацией работы самого p1m-ortho. Данная методичка уже суммирует их в обобщенном виде (иначе говоря, предмет изучения в нашей методичке — сайт p1m-ortho, в истории коммитов файла `METHOD.md` для этой методички — изменения, происходящие с p1m-ortho). Так же по аналогии и для других репозиториев в p1m-ortho.

Все правки по методам для некоторого репозитория, очевидно, необходимо вносить туда же, в `METHOD.md` этого самого репозитория.

## 4.7 Markdown
Язык разметки текста. Почитайте где-нибудь в Интернете.

### 4.6 Комментарии к коммитам. Три хороших комментария
#### 1
```
Составить из трех частей. Без точки в конце

Заголовок, пустая строка и тело. Заголовок совсем коротко, в пределах
50 символов описывает, в чем суть внесенных в файл изменений.

Пустая строка — так принято.

Тело расширенно описывает изменения. Если комментарий — короткий,
только заголовка будет достаточно.
```

#### 2
```
Разнести автоматически на два поля. Без точки в конце

GitHub делает именно это: при подаче коммита он предлагает поле
для заголовка и поле для тела коммита. Тогда разделительная пустая
строка — не нужна. Точка в конце заголовка — тоже не нужна.

Длинные строчки (более 72 символов) разбивайте переносами — вот как
здесь. Потому что, если строчка будет длинной, она не влезет в экран,
и тогда придется его прокручивать по горизонтали. А это неудобно.
```

#### 3
```
Поставить глагол в инфинитив. Без точки в конце

То есть что делать и что сделать, и только так. Такова конвенция.
```

### 4.5 Транслитерация
* С учетом того, что русские буквы в названии не используем, возникает необходимость записать кириллицу латиницей — транслитерировать. Как? Очень просто: как в загранпаспорте РФ.
* Здесь три простые причины.
    * (1) Ровно такой же системой пользуется Библиотека Конгресса США (и так же — PubMed) — за одним исключением: Ъ у них '', а не IE.
    * (2) Собственно фамилии совпадают с заграном.
    * (3) Журналы часто хотят транслитерацию именно такую.
    * А, ну и еще рентгенологи на снимках пишут также. Короче, вариантов нет — пользуйтесь этой системой. В частности «я» — это «ia», «ю» — это «iu», мягкие и твердые знаки опускаем, т. к. кавычки и апострофы в названиях не используем. 

### 4.4 Сокращения. ISO 3166-1 alpha-2. LTWA
* Часто приходится сталкиваться с необходимостью обозначить в названии страну, город или тип выполняемой работы (тезис, статья, доклад, обзор и т. д.). На этот счет уже есть установленный список сокращений, который рекомендую использовать.
* Во всяком случае, я использую и буду использовать именно его, и пусть эти сокращения не вызывают у вас вопросов.
* Страны — используем [2-буквенные коды стандарта ISO 3166 alpha-2](https://en.m.wikipedia.org/wiki/ISO_3166-1_alpha-2).
Или просто в любом поисковике написать (страна + 3166). Но 2-буквенный код.

| Страна | ISO 3166-1 alpha-2 | 
|--------|--------------------|
| Россия | RU                 | 
| США    | US                 | 
| Англия | GB                 |

* И так далее.
* Полезная особенность стандарта ISO 3166-1 alpha-2 — в том, что часть кодов в нем выделена для использования на усмотрение пользователей. Что мы и будем делать! Полужирным выделены коды, публикуемые впервые.

| Русский                     | Английский                  | ISO 3166-1 alpha-2 | 
|-----------------------------|-----------------------------|--------------------| 
| Весь мир                    | Worldwide                   | AA                 | 
| Обзор литературы            | Review                      | XR                 | 
| Клиническое исследование    | Clinical study              | XC                 | 
| Тезис                       | Abstract                    | XA                 | 
| Диссертация                 | Thesis                      | XT                 | 
| Статья в журнале            | Journal article             | XJ                 | 
| Доклад                      | Presentation                | XP                 | 
| **Организация**             | **Business administration** | **XB**             | 
| **Обучение**                | **Klassenleitung**          | **XK**             | 
| **Программное обеспечение** | **Software**                | **XS**             |

* Кроме стран также нередко возникает необходимость упомянуть в названии город. Тогда я пользуюсь [сокращениями ИАТА — международные коды-обозначения аэропортов](https://www.iata.org/publications/Pages/code-search.aspx). Или см. в поисковике по (город + код IATA).
* Еще по поводу сокращений. Есть обширнейший словарь сокращений слов под названием [LTWA ISSN](https://www.issn.org/ru/services-et-prestations/services-en-ligne/acces-a-la-ltwa/). Им пользуются, например, при сокращении названий журналов. Какое-нибудь _Int J Surg_ — это по этому словарю. Когда в каком-то названии хотите сократить слово, пользуйтесь и вы этим словарем.
* При написании названий месяцев я пользуюсь традиционными англоязычными сокращениями, чего и вам желаю: Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec — по первым трем буквам.

### 4.3 Конвенция имен
* Мы **строго** придерживаемся следующих правил: в названиях файлов, репозиториев, проектов и т. д. использовать только латинские буквы, цифры, дефис и нижнее подчеркивание.
* Никаких других символов (никаких пробелов, русских букв, точек, запятых, кавычек и так далее).
* В остальном ориентируйтесь на тот формат названий, что использую я ([@pussiatoday](https://github.com/pussiatoday)).

### 4.2 Краткий ответ на вопрос, зачем нам этот GitHub
Git — 👍. Word — 👎.

SQL — 👍. Excel — 👎.

R — 👍. PowerPoint — 👎.

### 4.1 Терминология
Эпидемиологический словарь под ред. Джона Ласта. Ред. русского издания — Василий Власов. Рекомендую всем эту книжку на случай, когда встречается очередной зарубежный термин и возникает вопрос, как его лучше перевести на русский. Правда, как показывает практика, там бывает не все. 

## 3 Деятельность

### 3.3 Клиническое исследование
Беда, беда с этими опросниками.

Не забудьте, прежде чем приступать к клиническому исследованию, проверить, а не сделано ли оно уже, а если сделано, то, может, его реплицировать?

### 3.2 Систематический обзор литературы
Что это означает? На самом деле, ряд вещей. Желающие ознакомиться с классическим определением могут сделать это в [пункте 1.2.2 кокрейновского справочника](https://handbook-5-1.cochrane.org/chapter_1/1_2_2_what_is_a_systematic_review.htm).
В частности это означает, что важно не только _что_ (какие статьи) нашли, но и _где_ нашли (откуда их взяли).

При изучении статей старайтесь составить себе представление, в первую очередь, не о том, что получили, а что делали (как набирали пациентов, что это были за пациенты, как их распределяли на группы, что затем с ними делали, по каким шкалам все же оценивали результаты, кто выбыл из исследования, а кто дошел до конца, чтобы сложился последовательный рассказ; представляйте, как бы это выглядело, если бы сами присутствовали при этом). В этом принципиальная важность.

И еще такой момент. Не стоит задача просто перевести статью. Перевести статью не роскошь. Стоит задача сложить ясное представление о том, чем занимались (см. выше) люди на другом конце шарика и что они обнаружили (какие цифры).

### 3.1 Структура
Наша наука на кафедре складывается из (а) работы с литературой и (б) работы с клиническим материалом. Принципиально литература — в приоритете, так как из нее складывается представление о том, что известно, а что нет, что требует уточнения — по сути, формирует предпосылки к проведению той иной клинической работы и определяет ее новизну. С другой стороны, всем желающим заниматься наукой предстоит выступать на конференциях, и на конференциях выступают уже обычно с каким-то клиническим материалом. С чем именно, определимся, но прежде, чем приступать к сбору материала, вам предстоит собрать литературу по этой области и ознакомиться с ней.

Каждый будет копать свою тему, но потом будет делиться накопанным с остальными. В конечном счете, все должны владеть всем. Так что пересечения будут, и этого не избежать. Это обыкновенное распределение зон ответственности.

Структура любого научного исследования: цель (какой вопрос у нас возник), актуальность (чего это вдруг он возник), методы (что планировали делать и что фактически делали, чтобы ответить на него), результаты (что получилось), обсуждение (что мы на этот счет думаем). При этом если в методах мы определяем общий шаблон данных, которые хотели получить — условно говоря, создаем названия полей пустой таблицы, которую хотим заполнить,— и планируем, как именно эти данные будем собирать и как заполнять таблицу, то в результатах мы, условно говоря, приводим эту заполненную таблицу, а уже в обсуждении рассказываем, как, на наш взгляд, полученные результаты помогают ответить на вопрос, который изначально у нас был (достигнута ли цель). Ну и в довершение всего — список литературы, и могут быть какие-то приложения. Вот общая структура всякой научной работы. В частности обзор литературы — самая настоящая работа.

Хорошее исследование — это всегда планирование, много планирования. Очень много изнурительного планирования.

## 2 Входной билет
http://www.testingtreatments.org/wp-content/uploads/2012/09/TT_2ndEd_English_17oct2011.pdf.

В русском переводе (в хорошем русском переводе):
http://www.testingtreatments.org/wp-content/uploads/2018/05/TT-RU_2nd_ed_cover_copyright_fullbook2018.pdf.

И есть даже аудиокнига:
https://m.soundcloud.com/user-300012405.

А также еще на 14 языках.
http://www.testingtreatments.org.

## 1 Членство
Расслабьтесь, вы на обучении. Вас никто не съест. Вся работа в рамках СНО — сугубо добровольная. Но полезная!

Здесь будет ссылка на список персоналий (подробнее см. в https://github.com/p1m-ortho/xb-track-record/issues/5).
