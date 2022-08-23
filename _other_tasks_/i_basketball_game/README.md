<h1 class="title">I. Баскетбольный матч</h1>
<p><b>Время: 1 сек.<br>Память: 512 Мб</b></p>
<p>Перед вами журнал результативных бросков в баскетбольном матче. Ваша задача — определить итоговый результат матча.</p>
<p>Правила начисления очков в баскетболе таковы:</p>
<ul>
    <li>за заброшенный со штрафного броска мяч команда получает 1 очко;</li>
    <li>за заброшенный с близкой дистанции мяч команда получает 2 очка;</li>
    <li>за заброшенный с дальней дистанции мяч команда получает 3 очка.</li>
</ul>
<p>Если расстояние до корзины во время броска было не более 6 метров, то дистанция считается близкой, в противном случае — дальней. Конечно, это несколько упрощённые правила игры в баскетбол.</p>
<h2>Формат ввода</h2>
<p>В первой строке записано целое число n — количество заброшенных мячей (1 <= n <= 1000). В следующих n строках содержатся сведения о заброшенных мячах.
Каждая строка содержит два целых числа t<sub>i</sub> и d<sub>i</sub> (1 <= t<sub>i</sub> <= 2, -1 <= d<sub>i</sub> <= 20). Если d<sub>i</sub> >= 0,
то это означает, что игрок из команды t<sub>i</sub> забросил мяч с расстояния d<sub>i</sub> метров до корзины. Если d<sub>i</sub> = -1, то это означает, что игрок из команды t<sub>i</sub> забросил мяч со штрафного броска.</p>
<h2>Формат вывода</h2>
<p>Выведите результат матча — количества очков, набранных первой и второй командой, записанные через двоеточие.</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>3<br>
            1 2<br>
            2 5<br>
            1 10</td>
        <td>5:2</td>
     </tr>
     <tr>
        <td>4<br>
            1 2<br>
            1 -1<br>
            1 20<br>
            1 20</td>
        <td>9:0</td>
     </tr>
     <tr>
        <td>10<br>
            1 -1<br>
            1 -1<br>
            2 -1<br>
            2 -1<br>
            1 1<br>
            1 5<br>
            2 6<br>
            2 7<br>
            1 11<br>
            1 12</td>
        <td>12:7</td>
     </tr>
  </tbody>
</table>