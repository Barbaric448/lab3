# Лабораторная работа 3

В данной лабораторной работе задача будет решена в ходе взаимодействия с терминалом и установления связи между несколькими виртуальными машинами.

# Задача

Необходимо настроить виртуальную машину А с Ubuntu (желательно, но можно и другую Linux подобную ОС) в VirtualBox. Обеспечить доступ в сеть Интернет. Осуществить проверку этого доступа и приложить скриншот из терминала. Следующим шагом настроить ещё одну виртуальную машину Б. После чего обеспечить сетевой доступ от машины А к машине Б. Приложить скриншот из терминала. Поднять ещё одну виртуальную машину В. Организовать сетевой доступ:

1. Из машины А в машину Б.
2. Из машины А в машину В.
3. Запретить доступ из машины Б в машину В.
4. Приложить скриншот, на котором видно терминалы всех трёх машин и видно что между машинами есть (или нет) доступа.

# Решение

Все три машины подключены к сети Интернет:
<p>
  <img src='4.png' width='720px', height='480px'>
</p>
<p>
  <img src='5.png' width='720px', height='480px'>
</p>
<p>
  <img src='6.png' width='720px', height='480px'>
</p>

Теперь необходимо создать две сети (для A и B, для A и C):
Обязательно настроить IPv4 префикс!
<p>
  <img src='1.png' width='720px', height='300px'>
</p>
<p>
  <img src='7.png' width='720px', height='300px'>
</p>


Вот результат:
<p>
  <img src='8.png' width='1020x', height='480px'>
</p>
<p>
  <img src='9.png' width='720px', height='480px'>
</p>

Как видно, все поставленные задачи выполнены. Машины А и B соединены, как и A с С, в то время как у B к C доступа нет.

