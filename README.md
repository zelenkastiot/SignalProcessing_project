# Дигитално процесирање на сигнали 

**Проект**


Временска зависност на промените на девизните курсеви. Постои база на податоци каде што се чуваат моментите на промена на девизниот курс меѓу две дадени парични единици, 
како и продажната и куповната вредност на курсот во дадениот момент https://www.histdata.com/download-free-forex-data/?/ascii/tick-data-quotes. 

Податоците се дадени за одделни месеци. Сакаме да најдеме некои правила, макар и статистички кои ги опишуваат интервалите меѓу соседните промени. 
Поинаку кажано, не интересира фреквенцијата, или честотата на промена на цената. 


Може да се проба следното:

- Да се најде хистограмот (веројатноста) на интервалите - колкав дел од интервалите имаат одредена вредност. Ова би се правело за секој ден посебно и потоа средна вредност од дневните хистограми во даден месец.
- Ако во даден момент се земе интервалот (од претходниот до него) ќе се добие низа. Со филтрирање (средна вредност од неколку соседни) би се добила некаква функција од времето. Тоа може да биде функција на интервалите од времето, или функција на фреквенциите (како мерка за активноста). Да се виде каква е таа функција. Веројатно би имала период 24 часа. 
- Некои девизни курсеви се менуваат понекогаш истовремено (на пример фунтата во однос на американскиот долар да се смени со еврото во однос на јенот. Од бројот на ваквите истовремени промени во даден интервал може да се види кои валути се поврзани.

