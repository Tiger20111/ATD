**В папке homework1**

Задание 1: визуализация деревьев 
Срок сдачи: до 4 апреля включительно. 
Дерево задаётся как ориентированный граф, все рёбра которого ориентированы от корня к листьям. 
Нужно реализовать укладку с помощью HV-подхода или алгоритма Layered-Tree-Draw. Можно выбрать и другой алгоритм, но требуется указать описание или ссылку на описание при сдаче проекта. 

**В папке homework2**

Задание 2: визуализация ациклических орграфов 
Срок сдачи: до 11 апреля включительно. 
На входе алгоритма ациклический орграф и, опционально, число W (максимально допустимая ширина слоя). 
Требуется при наличествующем W реализовать распределение по слоям с помощью алгоритма Грэхема—Коффмана. При отсутствующем W нужно реализовать алгоритм минимизации количества dummy-вершин. 
После укладки по слоям требуется добавить нужно число dummy-вершин и минимизировать (эвристическими средствами) количество пересечений рёбер, идущих между соседними слоями. 


**В папке homework3**

Срок сдачи: до 25 апреля включительно. 
На входе алгоритма набор пар целочисленных координат точек от 0 до 500, а также для каждой точки размеры подписи к ней (два целых числа — ширина и высота рамки подписи) и некоторое подмножество возможных расположений подписи (см. картинки справа). Кодирование входных данных — на ваш выбор, но лучше согласовать друг с другом в Телеграме, чтобы удобно было обмениваться примерами входных данных. 
На выходе — картинка с точками и неперекрывающимися метками (в частности, не вылезающими за пределы холста 500×500) либо указание, что такое расположение недостижимо. 
Задачу можно решать  
либо в постановке, когда для каждой точки задан выбор не более чем из двух вариантов расположения подписи, и написать самостоятельно 2-SAT решатель,  
либо без ограничений на количество вариантов, и тогда допустимо воспользоваться сторонним SAT-решателем, указав, как Вы кодируете задачу. 