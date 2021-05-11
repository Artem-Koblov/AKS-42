# Анализ стартапа по продаже продуктов питания  
Проект представляет собой пайплайн продуктового аналитика.
## Данные  
В качестве данных был использован датасет 240к+ строк со следующими столбцами:  
  - EventName — название события;  
  - DeviceIDHash — уникальный идентификатор пользователя;
  - EventTimestamp — время события;
  - ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
  
Необходимо проследить воронку событий - на каком этапе теряется больше всего клиентов и обсчитать результаты А/А/В теста по изменению шрифтов на лендинге.</div>  
## Использованные библиотеки Python  
pandas общие вычисления

numpy общие вычисления

plotly отображение воронки

matplotlib  гистограммы

re регулярные выражения

scipy критерий Шапиро-Уилка, Манна-Уитни и пр.

math вычисление z-критерия вручную

statsmodels использование z-критерия из библиотеки