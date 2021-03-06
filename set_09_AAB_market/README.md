# Анализ поведения пользователей приложения для покупки продуктов питания

## [Ссылка на проект в nbviewer](https://nbviewer.org/github/KSingular/yp_da_projects/blob/2f266b9b1e79c5b14c4bdec6c13fd3607e9055e6/set_09_AAB_market/set_09_AAB_market.ipynb)

## Описание
**Цель:** проанализировать поведение пользователей мобильного приложения для покупки продуктов питания.  

**Задачи:**
1. Изучить воронку продаж - узнать как пользователи доходят до покупки.
2. Исследовать результаты A/A/B-эксперимента - изучить как изменение шрифтов в приложении повлияет на поведение пользователей. 
    * *Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную - с новыми.*     

## Вывод
Целью исследования было проанализировать поведение пользователей мобильного приложения для покупки продуктов питания. 

Изучение данных позволило определить актуальный период за который они были собраны - с 1 по 8 августа 2019 года.  

Анализ событий, совершенных пользователями в приложении, показал следующее:
* Большинство пользователей завершило работу с приложением после посещения окна "Главное меню" - в контрольных группах 246 - 37% и 247 - 39%, в экспериментальной группе 248 - 39%. подобное поведение пользователей вероятно связано с неудобным и/или непривлекательным интерфейсом.
* От первого события до оплаты дошли в контрольных группах 246 - 49% и 247 - 47%, в экспериментальной группе 248 - 47%.
* Cреди пользователей, которым удалось разобраться с экраном "Главное меню" и изучить предложения о товарах, переходят на карточку товара (добавляют товар в корзину) в контрольных группах 246 - 82%, 247 - 81% и в экспериментальной группе 248 - 80%.
* Среди пользователей, которые перешли на карточку товара (добавили товар в корзину) завершают покупку в контрольных группах 246 - 95%, 247 - 94% и в экспериментальной группе 248 - 96%.   

Во время анализа результатов А/А/В-теста ни одна из проверок гипотез не выявила статистически значимых различий между контрольными и экспериментальной группой.    

По результатам анализа эксперимента можно сделать вывод, что изменение шрифтов в приложении не привело к изменениям в поведении пользователей. 

## Используемые библиотеки
`Pandas` `NumPy` `os` `Seaborn` `Plotly` `statsmodels / proportions_ztest` 

## Ключевые слова
`А/A/B-тестирование` `продуктовые метрики` `событийная аналитика` `воронки событий`