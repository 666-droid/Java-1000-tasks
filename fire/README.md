<h1 class="title">Костер (24%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 24%</b></p>
<p>Во время военного похода на морского пехотинца Джо было возложено ответственное задание – развести костёр и поддерживать в нём огонь ровно m минут. Для этого у Джо есть спички и n поленьев, причём Джо известно точное время сгорания каждого полена.</p>
<p>Джо разжигает огонь в момент времени t = 0 и сразу бросает в него одно или несколько поленьев. Затем он должен подбрасывать в огонь новые поленья, не позволяя костру угаснуть (т.е. если последнее полено в костре догорает в момент времени t, то новое полено может быть брошено в огонь не позднее t – 1). Поленья, брошенные в огонь, загораются мгновенно. Одновременно Джо может бросить в огонь любое количество поленьев. Джо должен бросить в огонь все n поленьев.</p>
<p>Помогите Джо определить, сможет ли он подбрасывать поленья в огонь таким образом, чтобы костер горел ровно m минут.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит целые числа n и m (1 ≤ n ≤ 100, 1 ≤ m ≤ 1000) – количество поленьев и время, в течение которого Джо должен поддерживать огонь в костре. Вторая строка входного файла содержит n целых чисел a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>n</sub>, где a<sub>i</sub> (2 ≤ a<sub>i</sub> ≤ 1000) – время сгорания i-ого полена в минутах.</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите строку «yes», если Джо сможет поддерживать огонь в костре ровно m минут, и строку «no» в противном случае.</p>
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
        <td	3 7<br>
           2 3 5</td>
        <td>yes</td>
     </tr>
     <tr>
        <td>2 5<br>
            3 9</td>
        <td>no</td>
     </tr>
     <tr>
        <td>4 10<br>
            3 3 3 3</td>
        <td>no</td>
     </tr>
  </tbody>
</table>