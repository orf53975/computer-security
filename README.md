# Модели безопасности компьютерных систем

## Описание курса

Программа и материалы курса «Модели безопасности компьютерных систем: управление доступом и информационными потоками»
образовательной программы по направлению подготовки (специальности)
10.05.01 «Компьютерная безопасность», преподаваемого в [Национальном исследовательском Томском государственном университете](http://www.tsu.ru) на [кафедре защиты информации и киптографии](http://isc.tsu.ru)

## Вопросы

1. Основные элементы теории компьютерной безопасности
    * Термины: субъект, объект, контейнер, сущность, информационный поток, права доступов, виды доступов
    * Основная аксиома компьютерной безопасности
    * Классификация угроз компьютерной безопасности
    * Информационные потоки и скрытые каналы
    * Виды управления доступом
        * Дискреционное управление доступом
        * Мандатное управление доступом
        * Ролевое управление доступом
        * Атрибутное управление доступом
    * Политики управления доступом и информационными потоками
    * Модели безопасности управления доступом и информационными потоками
        * Зачем нужны модели безопасности
        * Модели как примитивы
        * Модели потоков данных
        * Субъектно-объектные модели
        * Субъектно-сущностные модели
2. Теорема Харрисона-Руззо-Ульмана
3. Модель типизированной матрицы доступов 
4. Классические модели дискреционного управления доступом
    * Модель Грэхэм-Деннинг
    * Модель Take-Grant
5. Классические модели мандатного управления доступом
    * Модель Белла-ЛаПадулы
    * Модель Биба
6. Классические модели ролевого управления доступом
    * Базовая модель ролевого управления доступом Сандху
    * Модель администрирования ролевого управления доступом
    * Модель мандатного ролевого управления доступом
7. ДП-модели
    * Определение ДП-моделей
    * Основные элементы и механизмы
      *   Доверенные субъекты
      *   Ассоциированные сущности
      *   Правила преобразования
      *   Замыкания
    * Базовые ДП-модели
      * БК ДП-модель
      * БД ДП-модель
      * ФАС/ФПАС ДП-модель
    * Принципы построения и применения ДП-моделей на практике
   
## Теоретические задания (необходимо выполнить все задания)
1. В доказательстве теоремы о существовании алгоритма проверки безопасности для монооперационных систем Харрисона-Руззо-Ульмана рассматривается случай 3:

   ```
q=(S,O,M), S - непустое множество и для всех (s,o) из SxS право r принадлежит M[s,o]
   ```
В данном случае может понадобится создать новый субъект или объект. Причем сначала нужно попробовать создать объект. Пусть не удалось создать субъект. Как по виду матрицы определить есть ли смысл пробовать создавать объект?
2. Построить соответствие в системе Харрисона-Руззо-Ульмана для команд Машины Тьюринга при движении считывающей головки влево и без движения.
3. Показать, что модель Take-Grant является автоматной моделью.
4. С помощью системы ХРУ построить произвольную систему дискреционного управления доступом.
5. С помощью системы ХРУ построить произвольную систему мандатного управления доступом.
6. Построить tg-замыкание графа x--t-->y<--g---z, где x,z - субъекты, а y - объект.

## Практические задания (необходимо выполнить одно из заданий)
1. Для выбранной СУБД  определить тип управления доступом и обосновать его с помощью тестов
2. На произвольном языке программирования/фрэймворке разработать простейшее веб-приложение с мандатным или атрибутным управлением доступом
3. Для произвольной компьютерной системы построить модель ее политики управления доступом: выделить основные элементы модели и определить правила преобразования системы
 

## Материалы

### Литература
* [П.Н. Девянин. Модели безопасности компьютерных систем. Управление доступом и информационными потоками](http://www.ozon.ru/context/detail/id/22403706/)
* [Matt Bishop. Computer Security: Art and Sciense](http://nob.cs.ucdavis.edu/book/book-aands/)
* [Н.А. Гайдамакин. Теоретические основы компьютерной безопасности.](http://elar.urfu.ru/bitstream/10995/1778/5/1335332_schoolbook.pdf)

### Видео
* [П.Н. Девянин. Модели безопасности логического управления доступом и информационными потоками в компьютерных системах и их практическое применение] (https://www.youtube.com/watch?v=mXGpjxMU7i4&list=PLCE64BEFE00F2BA0D)
* [Д.Н. Колегов. Моделирование безопасности управления доступом и информационными потоками на основе ДП-моделей](https://vimeo.com/97906604)
* [George Danezis. Access Control](https://www.youtube.com/watch?v=QaS_UBuPVWA)
