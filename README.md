# **laboratornaya2**

## Требования к проекту

### Содержание

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

