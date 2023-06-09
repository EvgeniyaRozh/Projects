## **Описание проекта**  
В компании подготовлен список гипотез для увеличения выручки. Задача проекта - приоритизировать гипотезы, запустить A/B-тест и на основе результатов принять подходящее решение. Первоначальные данные представляют собой 3 таблицы, в которых содержатся данные о 9 гипотезах с оценками приоритетных признаков, данные о заказах и о пользователях контрольной и тестируемой групп. Для выполнения задачи проекта сделано следующее:  

- проверены данные на корректность названия колонок для удобства дальнейшей работы с ними, на соответствие типов данных, на наличие дубликатов, пропусков, аномалий в таблицах;  
- двумя методами опеределена, какая гипотеза будет являться наиболее успешной;  
- проанализированы результаты проведения А/Б тестирования и посчитаны наиболее важные метрики, такие как, кумулятивная выручка, кумулятивный средний чек, кумулятивное среднее количество заказов на посетителя по группам;  
- очищены данные от значений, которые могут исказить результаты;  
- выяснено, насколько значимыми являются рассматриваемые метрики.  


По результатам сделан вывод, необходимо ли продолжать А/Б тестирование или данных достаточно для успешности/неуспешности проведения эксперемента.

## **Навыки и инструменты**  

- Python
- Pandas
- Matplotlib
- SciPy
- A/B-тестирование
- проверка статистических гипотез

## **Выводы**  

Есть статистически значимое различие по среднему чеку между группами как по сырым данным, так и после фильтрации аномалий.  
Нет статистически значимого различия по конверсии между группами как по сырым данным, так и после фильтрации.  
Конверсия в группе B держалась стабильно выше конверсии группы A.  
График различия среднего чека колеблется: он-то и позволил нам найти аномалии. Сделать из этого графика определённые выводы нельзя.  
В целом эксперемент можно остановить и признать успешным, т.к. группа B показала лучшие результаты относительно группы А.  
