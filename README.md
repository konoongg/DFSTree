# DFSTree
Маша совсем уработалась и решила взять отпуск. Она планирует совершить грандиознейшее в ее жизни путешествие и хочет очень основательно к нему подготовиться. Помогите ей в этом нелегком деле.

----

Маша уже несколько лет коллекционирует список мест, в которых она мечтала бы побывать. Маша настолько грезит их посетить, что даже присвоила каждому месту некоторое число: чем оно меньше, тем больше она хочет там побывать. Как именно формируется число? Это известно одной Маше: например Парижу она присвоила 5, а кофейне за углом - 28412.

Сейчас Маша размышляет о том, в каком порядке ей следует двигаться: ведь очень разумно было бы передвигаться от места с самым маленьким номером к месту с самым большим номером. Однако наша подруга находит этот порядок несколько скучным... Вместо этого Маша придумала особую схему: все номера она поместила в бинарное дерево поиска, а затем вывела его в preorder-порядке. Получилось интересно, но Маша хочет посмотреть и другие варианты: postorder и inorder.

Увы, Маша забыла куда-нибудь записать дерево с номерами, так что его preorder-обход - это все, что имеется. Помогите Маше из него сформировать оставшиеся два.

## Формат ввода
В первой строке указано количество вершин в дереве (≤100000). Во второй строке перечислены разделенные одним пробелом номера из исходного дерева preorder-порядке (значения номеров неотрицательны и не превосходят 
1000000000).

## Формат вывода
Программа должны вывести две строки: в первой запись дерева в порядке postorder, во второй — в порядке inorder. Все значения должны быть разделены одним пробелом.
