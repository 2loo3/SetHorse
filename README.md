"# SetHorse" 
Дана доска nхn содержащая n­­2 полей. Конь, который ходит согласно шахматным правилам, помещается на поле с начальными координатами x0, y0. Нужно покрыть все доску ходами коня, т.е. вычислить обход доски, если он существует, из n2-1 ходов, такой, что каждое поле посещается ровно один раз.

Алгоритм решения
1.    Помечаем клетку, в которой находится конь.
2.    Перемещаем коня в доступную для хода клетку.
3.    Если ход невозможен, то возвращаем коня в предыдущую клетку (отмена хода).
4.    Повторяем шаги 1-3 до тех пор, пока не посетим все клетки поля или не останется доступных ходов.
n=8

