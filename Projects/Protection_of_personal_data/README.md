# Защита персональных данных клиентов
## Описание проекта
Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. \
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.Подбирать наилучшую модель не требуется.
## Инструкция по выполнению проекта
Загрузите и изучите данные. \
Ответьте на вопрос и обоснуйте решение. \
Признаки умножают на обратимую матрицу. Изменится ли качество линейной регрессии? (Её можно обучить заново.)
1. Изменится. Приведите примеры матриц.
2. Не изменится. Укажите, как связаны параметры линейной регрессии в исходной задаче и в преобразованной.

Предложите алгоритм преобразования данных для решения задачи. Обоснуйте, почему качество линейной регрессии не поменяется. \
Запрограммируйте этот алгоритм, применив матричные операции. Проверьте, что качество линейной регрессии из sklearn не отличается до и после преобразования. Примените метрику R2.
## Описание данных
Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи. \
Целевой признак: количество страховых выплат клиенту за последние 5 лет.
