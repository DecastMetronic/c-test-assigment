# Тестовое задание на позицию "Программист-микроконтроллеров"
[![career.habr](https://img.shields.io/static/v1?label=career&message=habr&color=65A3BE&logo=habr)](https://career.habr.com/companies/decast)

## Задание

Есть строковый идентификатор, который строится по правилам:
1. В строковых идентификаторах используются только согласные буквы: B, C, D, F, G … Z и цифры от 1 до 9;
2. Первый строковый идентификатор имеет вид "B1". Второй строковый идентификатор в последовательности - "B2", третий - "B3" и так далее. За "B9" следующий - "C1". Следующий после "Z9" имеет вид "B1-B1", потом "B1-B2" и так далее. После "B1-Z9" следующим идет "B2-B1";
3. Максимальная длина идентификатора - десять групп по два символа.

Нужно:
1. Написать модуль на языке С. Функция модуля должна получать в качестве входного параметра строковый идентификатор из описанной последовательности, и генерировать выходную строку, содержащую следующий идентификатор последовательности;
2. Покрыть код модуля тестами.

Пример: функция получает "B1-Z9" и возвращает "B2-B1".

## Дополнительное задание

Можно сделать дополнительное задание: настроить автоматическую сборку и тестирование кода с помощью github actions.

## С чего начать

1. [Зарегистрируйтесь на github](https://github.com/signup);
2. Создайте свой репозиторий, используя этот репозиторий [как шаблон](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template);
3. Напишите код решения задачи;
4. Зафиксируйте (commit) изменения и отправьте их в upstream;
5. Пришлите ссылку на ваш репозиторий с решением рекрутеру или на почту [hr@decast.com](mailto:hr@decast.com?subject=Решение%20тестового%20задания&cc=rnd@decast.com).
