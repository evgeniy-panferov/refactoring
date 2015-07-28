Завистливые функции

Чаще всего предметом зависти являяются данные другого объекта\класса.

Лечение: перемещение метода.
Иногда завистью страдает только часть метода; в таком случае к завистливому фрагменту применяется "выделение метода", дающее ему то о чем он мечтает.

Выигрыш:
1. Уменьшение дублирования кода (если код работы с данными переехал в одно общее место).
2. Улучшение организации кода (т.к. методы работы с данными находятся возле этих данных).

Исключение: паттерны "Стратегия" и "Посетитель", которые позволяют легко изменить поведение, потому что они изолируют небольшой объем функций, которые должны быть заменены, ценой увеличения косвенности.