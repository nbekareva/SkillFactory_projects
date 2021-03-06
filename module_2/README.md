<h1>Skillfactory project 2</h1>
<h2>0_project_2-анализ_данных</h2>
<b>Цель проекта</b> <br>
Выполнить EDA датасета о школьниках.<br>
<br>
<b>Задачи:</b><br>
	1. Провести первичную обработку данных.<br>
	2. Посмотреть на распределение признака для числовых переменных, устранить выбросы.<br>
	3. Оценить количество уникальных значений для номинативных переменных.<br>
	4. По необходимости преобразовать данные.<br>
	5. Провести корреляционный анализ количественных переменных.<br>
	6. Отобрать не коррелирующие переменные.<br>
	7. Проанализировать номинативные переменные и устранить те, которые не влияют на предсказываемую величину (score).<br>
	8. Сформулировать выводы относительно качества данных и тех переменных, которые вы будете использовать в дальнейшем построении модели.<br>
<br>
<details>
  <summary><b>Инфо о данных</b></summary>

	1. school — аббревиатура школы, в которой учится ученик
	2. sex — пол ученика ('F' - женский, 'M' - мужской)
	3. age — возраст ученика (от 15 до 22)
	4. address — тип адреса ученика ('U' - городской, 'R' - за городом)
	5. famsize — размер семьи('LE3' <= 3, 'GT3' >3)
	6. Pstatus — статус совместного жилья родителей ('T' - живут вместе 'A' - раздельно)
	7. Medu — образование матери (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
	8. Fedu — образование отца (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
	9. Mjob — работа матери ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
	10. Fjob — работа отца ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
	11. reason — причина выбора школы ('home' - близость к дому, 'reputation' - репутация школы, 'course' - образовательная программа, 'other' - другое)
	12. guardian — опекун ('mother' - мать, 'father' - отец, 'other' - другое)
	13. traveltime — время в пути до школы (1 - <15 мин., 2 - 15-30 мин., 3 - 30-60 мин., 4 - >60 мин.)
	14. studytime — время на учёбу помимо школы в неделю (1 - <2 часов, 2 - 2-5 часов, 3 - 5-10 часов, 4 - >10 часов)
	15. failures — количество внеучебных неудач (n, если 1<=n<=3, иначе 0)
	16. schoolsup — дополнительная образовательная поддержка (yes или no)
	17. famsup — семейная образовательная поддержка (yes или no)
	18. paid — дополнительные платные занятия по математике (yes или no)
	19. activities — дополнительные внеучебные занятия (yes или no)
	20. nursery — посещал детский сад (yes или no)
	21. higher — хочет получить высшее образование (yes или no)
	22. internet — наличие интернета дома (yes или no)
	23. romantic — в романтических отношениях (yes или no)
	24. famrel — семейные отношения (от 1 - очень плохо до 5 - очень хорошо)
	25. freetime — свободное время после школы (от 1 - очень мало до 5 - очень мого)
	26. goout — проведение времени с друзьями (от 1 - очень мало до 5 - очень много)
	27. health — текущее состояние здоровья (от 1 - очень плохо до 5 - очень хорошо)
	28. absences — количество пропущенных занятий
	29. score — баллы по госэкзамену по математике

</details>

<b>Ответы на вопросы саморефлексии:</b>
1. Какова была ваша роль в команде?<br>
Проект выполнялся мной лично.<br>
2. Какой частью своей работы вы остались особенно довольны?<br>
Функции для построения графиков.<br>
3. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?<br>
Заполнение пропусков.<br>
4. Что интересного и полезного вы узнали в этом модуле?<br>
Ttest из модуля stats, как тестировать нулевую гипотезу на массиве данных.<br>
5. Что является вашим главным результатом при прохождении этого проекта?<br>
По этому проекту не вижу особого личного прогресса.<br>
6. Планируете ли вы менять стратегию изучения последующих модулей?<br>
Возможно, забегать вперед по теории перед выполением проекта.<br>
