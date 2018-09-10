Сетка фреймворка состоиз из строки и колонок которые имеются по принципу БЭМ. Главный центровщик имеет класс "wrapper".
Строка имеет класс "line". Колонки имеются line__child_(размер колонки xl, lg, md или всегда фиксированный размер)_(кол-во места которое занимает блок от 1 до 12). Например:
  <div class="line">
    <div class="line_child_xl_6 line_child_lg_9"></div>
    <div class="line_child_xl_6 line_child_lg_3"></div>
  </div>
Также созданы классы для технологии flex: .flex, .flex-row, .flex-column, .space-between, .x-start, .x-end, .y-center
Классы для плавающих элементов: .pull-left, .pull-right.
Классы для выравнивания текста: .text-right, .text-left, .text-center.
Раздел с демонстрацией работы колонок: в верхней части страницы это header и его потомки; в центральной часть - aside и article.
Работа классов flex продемонстрирована в блоке aside.
