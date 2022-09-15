# Homework2
 №1 Написать программу для печати указанного списка после удаления 0-го, 4-го, и 5-го элементов
print("задание №1:")
print("Обычный список:");
list_favorite_colors = ['Красный', 'Зеленый', 'Белый', 'Черный', 'Розовый', 'Желтый']
print (list_favorite_colors);

print ("преобразованный список:");
del list_favorite_colors [0]
del list_favorite_colors [3:5]
print(list_favorite_colors)


# №1 Написать программу, чтобы добавить список ко второму списку.
print("\n\nзадание №2:")
first_favorite_color = set (["оранжевый", "салатовый", "коричневый"]);
print("первый список :",first_favorite_color )
second_favorite_color = (["синий", "розовый"]);
print("второй список", second_favorite_color);
all_favorite_color = first_favorite_color.union(second_favorite_color);
print("все цвета (два списка):", all_favorite_color );
