Курс теории типов, КТ, осень 2019
==========================
## Материалы
+ [конспект лекций] (https://github.com/shd/tt2018-conspect)
+ [теоретические домашние задания] (https://github.com/shd/tt2019/blob/master/hw-theory.pdf)
+ [материал для первой половины курса] Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 1
### Лямбда-исчисление, базовые определения, примеры
+ Немного об истории
+ Лямбда-выражения, синтаксис
+ Альфа-эквивалентность, бета-редекс, бета-редукция
+ Булевские выражения, чёрчевские нумералы
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 2
### Теорема Чёрча-Россера, Y-комбинатор
+ Бета-редуцируемость и параллельная бета-редукция
+ Теорема Чёрча-Россера
+ Комбинаторы: определение и примеры (I,S,K)
+ Рекурсия и Y-комбинаторы
+ Ленивые вычисления, нормальный порядок редукции
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ Сказка про лень да отеть
https://russkaja-skazka.ru/len-da-otet/

## Лекция 3
### Просто типизированное лямбда-исчисление
+ Почему бестиповое лямбда-исчисление не подходит в качестве исчисления высказываний
+ Импликационный фрагмент интуиционистского исчисления высказываний
+ Просто типизированное лямбда-исчисление по Карри
+ Исчисление по Чёрчу
+ Комбинаторы, базис SK
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 4
### Свойства просто типизированного лямбда-исчисления
+ Теорема о полноте импликационного фрагмента ИИВ
+ Сильная нормализация просто типизированного лямбда-исчисления
+ Класс вычислимых в просто типизированном лямбда-исчислении функций (формулировка)
+ Три задачи: обитаемость типа, вывод (реконструкция) типа, проверка типа
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 5
### Алгоритм унификации, вывод типа
+ Алгебраические термы, задача унификации
+ Алгоритм унификации
+ Алгоритм вывода типов в просто типизированном лямбда-исчислении
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ Alberto Martelli, Ugo Montanari: An Efficient Unification Algorithm
http://moscova.inria.fr/~levy/courses/X/IF/03/pi/levy2/martelli-montanari.pdf

## Лекция 6
### Увеличение выразительности языка
+ Интуиционистское исчисление высказываний (связки: конъюнкция, дизъюнкция, ложь) и
соответствующие новым связкам конструкции в лямбда-исчислении.
+ Логика второго порядка
+ Выразимость всех связок через импликацию и квантор всеобщности
+ Система F
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 7
### Экзистенциальные типы
+ Экзистенциальные типы
### Где почитать
+ Пример использования экзистенциальных типов в Хаскеле
https://github.com/shd/tt2014/blob/master/existential.hs
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ Abstract Types Have Existential Type
http://homepages.inf.ed.ac.uk/gdp/publications/Abstract_existential.pdf
+ On Understanding Types, Data Abstraction, and Polymorphism
http://lucacardelli.name/Papers/OnUnderstanding.pdf

## Лекция 8
### Типовая система Хиндли-Милнера
+ Ранг типа
+ Типы и типовые схемы, уточнение/обобщение типов, конструкция let.
+ Типовая система Хиндли-Милнера.
### Где почитать
+ Бенджамин Пирс, Типы в языках программирования. Издательство «Лямбда пресс» & «Добросвет», Москва, 2011
+ Robin Milner, A theory of type polymorphism in programming (1978) // Journal of Computer and System Sciences, 1978, vol. 17, pp. 348--375
https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.67.5276
+ Статья на Википедии Hindley-Milner_type_system, вполне информативна в этом вопросе.
https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system
