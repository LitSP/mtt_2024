В файле trust.py содержится программная реализация алгоритма расчёта индекса доверия для автономных систем.
Флагом weights_flag регулируется расчёт с весами.

Файл trusted.txt представляет собой список номеров доверенных автономных систем. (АС, размер (для отрисовки), вес для расчета индекса)

Файл semi-trusted.txt представляет собой список номеров полудоверенных автономных систем. (АС, размер (для отрисовки), вес для расчета индекса)

Файл untrusted.txt представляет собой список номеров недоверенных автономных систем. (АС, размер (для отрисовки), вес для расчета индекса)

Файл links.txt представляет собой список соединений между автономными системами. (АС, АС)

Результатом работы программы является python-словарь с расчитанными индексами доверия для автономных систем на основании их "схожести" друг на друга.

Итоговый результат для получения индекса доверия - значение "схожести" для узла "trusted".