# Deposits
Deposits in different banks

per_cent - словарь с распределением процентных ставок по вкладам в различных банках (ключ - название банка, значение - процент):

per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}

На вход программы с клавиатуры вводится сумма money, которую пользователь планирует положить под проценты.

Программа выводит на экран:
- список deposit значений - накопленные средства за год вклада в каждом из банков;
- максимальное значение списка deposit и его вывод на экран в формате:

"Максимальная сумма, которую вы можете заработать — deposit[i]", где вместо deposit[i] будет выведено максимальное значение списка.
