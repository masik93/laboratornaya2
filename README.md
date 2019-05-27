# **laboratornaya2**

## Требования к проекту

### Содержание
[1 Введение](https://github.com/masik93/laboratornaya2#1-%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5)
[1.1 Назначение](https://github.com/masik93/laboratornaya2#11-%D0%BD%D0%B0%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)
[1.2 Бизнес-требования](https://github.com/masik93/laboratornaya2#12-%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
[1.2.1 Исходные данные](https://github.com/masik93/laboratornaya2#121-%D0%B8%D1%81%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D0%B5-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5)
[2 Требования пользователя](https://github.com/masik93/laboratornaya2#2-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)
[2.1 Программные интерфейсы](https://github.com/masik93/laboratornaya2#21-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D1%8B%D0%B5-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D1%8B)
[2.2 Интерфейс пользователя](https://github.com/masik93/laboratornaya2#22-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)
[2.3 Характеристики пользователей](https://github.com/masik93/laboratornaya2#23-%D1%85%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B8-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)
[2.4 Предположения и зависимости](https://github.com/masik93/laboratornaya2#24-%D0%BF%D1%80%D0%B5%D0%B4%D0%BF%D0%BE%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8-%D0%B7%D0%B0%D0%B2%D0%B8%D1%81%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8)
[3 Системные требования](https://github.com/masik93/laboratornaya2#3-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
[3.1 Функциональные требования](https://github.com/masik93/laboratornaya2#31--%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
[3.2 Нефункциональные требования](https://github.com/masik93/laboratornaya2#32-%D0%BD%D0%B5%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
[3.2.1 Атрибуты качества](https://github.com/masik93/laboratornaya2#321-%D0%B0%D1%82%D1%80%D0%B8%D0%B1%D1%83%D1%82%D1%8B-%D0%BA%D0%B0%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B0)
[3.2.2 Требования к безопасности]

### 1 Введение

  Тип приложения: Архиватор Desktop-приложение.
Название продукта: Архиватор.

#### 1.1 Назначение

  Назначение программ-архиваторов заключается в экономии места на диске за счет сжатия (упаковки) одного или нескольких файлов в архивный файл. Программы-архиваторы используют для хранения в упакованном виде больших объемов информации, которая понадобится в будущем; переноса информации между компьютерами с помощью дискет или электронной почты; создания в сжатом виде резервных копий файлов; для защиты от компьютерных вирусов. В результате работы программ-архиваторов создаются архивные файлы (архивы).
  
1. извлечение файлов из архивов;

2. создание новых архивов;

3. добавление файлов в имеющийся архив;

4. создание самораспаковывающихся архивов;

5. создание распределенных архивов на носителях малой емкости;

6. тестирование целостности структуры архивов;

7. полное или частичное восстановление поврежденных архивов;

8. защита архивов от просмотра и несанкционированной модификации.

#### 1.2 Бизнес-требования

##### 1.2.1 Исходные данные

  Внедрение архиватора позволит сократить место на диске компьютера(или внешнего накопителя) одного или нескольких файлов в архивный файл.
 1. Архивация выбранных файлов и папок на случай сбоя жесткого диска или случайного удаления файлов (архивировать можно на жесткий диск или съемный диск и т.д.). Backup восстанавливает архивированные файлы и папки на жесткий диск.
 2. Архивация данных состояния системы. Программа позволяет архивировать копии важных системных компонентов, таких как реестр, загрузочные файлы и база данных службы каталогов. Программа архивации позволяет восстанавливать копии важных системных компонентов, таких, как реестр, загрузочные файлы и база данных службы каталогов.
  
### 2 Требования пользователя

#### 2.1 Программные интерфейсы
  
  1. Графический интерфейс пользователя должен обеспечиваться встроенными в Windows системными библиотеками Windows API.
  
 #### 2.2 Интерфейс пользователя
 
 ![Image alt](https://github.com/masik93/laboratornaya2/blob/master/image/top.7f66cff1.png?raw=true "Optional Title")
 
 Рисунок 1. Главное окно программы
 
 Главное окно содержит две основные кнопки Созздать и Открыть. 
 В зависимости от необходимой функции выполенния программы пользователь нажимает на олну из данных кнопнок. Затем следует инструкция,
 всплываемыми на экране (диалоговые окна). 
 
 Также есть кнопки Настройки, Помощь и Выход - стандарные кнопки. 
 
 Главным моментом данной программы является архивация и разорхивация компонента. 
 Чтобы происходило более удобное функционирование процесаа, польщователь может выбрать один или несколько компоненотов для 
 данного процесса, а также может выбрать локальное расположение сохранения.
 
 #### 2.3 Характеристики пользователя
 
 Пользователи не имеют каких-либо разделений, так как основная аудитория и является пользователь ПК.
 
  #### 2.4 Предположения и зависимости
  
  Дополнительные требования к диспетчерам архивов:
  
1. просмотр файлов различных форматов без извлечения их из архива;

2. поиск файлов и данных внутри архивов;

3. установку программ из архивов без предварительной распаковки;

4. проверку отсутствия компьютерных вирусов в архиве до его распаковки;

5. криптографическую защиту архивной информации;

6. декодирование сообщений электронной почты;

7. «прозрачное» уплотнение исполнимых файлов .ЕХЕ и .DLL;

8. создание самораспаковывающихся многотомных архивов;

9. выбор или настройку коэффициента сжатия информации.
 
 ### 3 Системные требования
 
 Информационная автоматизированная система может работать под управлением семейства операционных систем Win32 (Windows 95, Windows 98, Windows 2000, Windows NT и т.д.) 
 

#### 3.1  Функциональные требования

1. извлечение файлов из архивов;

2. создание новых архивов;

3. добавление файлов в имеющийся архив;

4. создание самораспаковывающихся архивов;

5. создание распределенных архивов на носителях малой емкости;

6. тестирование целостности структуры архивов;

7. полное или частичное восстановление поврежденных архивов;

8. защита архивов от просмотра и несанкционированной модификации.
  
#### 3.2 Нефункциональные требования

##### 3.2.1 Атрибуты качества

Как правило, говоря о нефункциональных требованиях, чаще всего говорят об атрибутах качества (т.е. требованиях, определяющих качественные характеристики разрабатываемого программного обеспечения или системы, такие как производительность, надежность, масштабируемость), не обращая внимания на другие виды нефункциональных требований, а именно:

 Атрибуты качества:
 
 Атрибуты, важные для разработчиков:
 1. Ограничения - Разработка должна вестись на платформе дл ПК
 2. Бизнес-правила - Конечный файл обязательно должен быть уменьшен в размере в сравнении с исходным, как минимум в 0.8
 
 Атрибуты, важные для пользователей:
 1. Внешние интерфейсы - Удобство в использовании.
 2. Лёгкость в эксплуатации - Во время загрузки и в процесее работы, программа должна быть интуитивно понятна, и требовать минимальное количество действий.
 3. Скорость процесса - Особенно важный пункт для работы с большими данными.
 
 ##### 3.2.2 Требования к безопасности
 
Требования к безопасности, как правило, включают в себя три большие категории: требования, связанные с разграничением доступа, требования, связанные с работой с приватными данным, и требования, направленные на снижение рисков от внешних атак.
Надежное функционирование автоматизированной системы должно быть обеспечено выполнением организационно-технических мероприятий, таких как:

1.скорость ввыполнения процессов;
2.использование лицензионного программного обеспечения;
3.организация бесперебойного питания путем использования блоков бесперебойного питания;
