# indiv_epigenomics
## Краткое описание JMJD1C
- Эпигенетическая функция:
JMJD1C - ген, кодирующий фермент гистоновой деметилазы, который может удалять модификацию H3K9me. Удаляя эту модификацию, JMJD1C может активировать экспрессию генов. Таким образом, функция JMJD1C заключается в удалении модификации H3K9me и активации экспрессии генов.

- Ссылки:
1) https://probiologists.com/Article/Role-of-H3K9-demethylases-in-DNA-doublestrand-break-repair 
2) https://ashpublications.org/blood/article/122/21/1602/11942/Overexpression-Of-The-Histone-Demethylase-JMJD1C 
3) https://www.frontiersin.org/articles/10.3389/fphys.2020.00539/full


## Множественное белковое выравнивание гистонов:
При выравнивании последовательностей гистона H2A было выявлена 41 группа похожих друг на друга последовательностей с разной степенью сходства. У H2B 25 групп, у H3 13 групп, у H4 12 групп. Это можно заметить по отдельным выравниваниям, что некоторые последовательности совпадают друг с другом на 100%, а некоторые меньше, чем половина, например. Это говорит нам о том, что некоторые гены являются копиями друг друга, а некоторые изоформами с различными функциями и структурами. Небольшие различия в последовательностях могут возникнуть в результате мутаций, более серьезные скорее всего гвоорят о вариациях гена у разных организмов.
При этом у H3 и H4 гораздо больше "высоких" совпадений (у H4 почти все), что может говорить об их большей консервативности.

### H2A
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/78f5a7cc-d32f-4760-947d-d77ef10f75be)
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/488a5367-b5be-4341-8350-be89e88773d7)

### H2B
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/64ac7c52-263d-4bb5-9819-1df9f85e2fb2)
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/0c014e08-f95d-4397-805d-eb3c8f971710)

### H3
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/769e73e0-65fa-48fc-b292-d6cb8d77c39c)
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/6c9b4c62-0b0b-49a5-8d24-6a8f9721093a)

### H4
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/bca06af1-e974-455f-aff7-ab1b5d366f7d)
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/71f8ec42-6610-4a96-8213-21774c4f710d)

### Файлы с результатами выравнивания находятся в папке allign


## Таблицы
| evalue | human | mouse |	zebrafish | drosophila | c.elegans | ciliate | yeast | methanocaldococcus | thermococcus | e.coli | tuberculosis |
|--------|-------|-------|------------|------------|-----------|---------|-------|--------------------|--------------|--------|--------------|
| H2A | 0,00 | 0,00 | 0,00 | 1,22E-44 | 8,80E-48 | 1,22E-46 | 8,67E-46 | 0,26 | 6,95E-06 | 1,32E-14 | 0,10 |
| H2B	| 1,70E-88 | 1,32E-86 | 1,18E-81 | 5,93E-59 | 4,17E-64 | 9,09E-50 | 4,48E-59 | 2,20 | 1,10 | 1,60 | 3,10 |
| H3 | 2,19E-96 |	1,54E-96 | 1,77E-95 | 9,39E-96 | 4,46E-94 | 8,41E-86 | 3,31E-87 | 0,03 | 0,06 | 0,90 | 4,60 |
| H4 | 1,09E-67 | 7,60E-68 | 1,13E-68 | 8,02E-68 | 6,15E-68 | 1,96E-45 | 1,08E-52 | 8,22E-05 | 3,31E-05 | 1,30 | 0,07 |
| JMJD1C | 0,00	| 0,00 | 0,00	| 2,13E-11 | 2,10 |	0,50 | 2,40 | 0,07 | 0,85 | 4,50 | 0,60 |

| -log | human | mouse |	zebrafish | drosophila | c.elegans | ciliate | yeast | methanocaldococcus | thermococcus | e.coli | tuberculosis |
|------|-------|-------|------------|------------|-----------|---------|-------|--------------------|--------------|--------|--------------|
| H2A | 300 | 300 | 300 | 43,91 | 47,06 | 45,91 | 45,06 | 0,59 | 5,16 | 13,88 | 1 |
| H2B | 87,77 | 85,88 |	80,93 |	58,23 |	63,38 |	49,04 |	58,35 | -0,34 |	-0,04 |	-0,2 | -0,49 |
| H3 | 95,66 | 95,81 | 94,75 | 95,03 | 93,35 | 85,08 | 86,48 | 1,47 | 1,24 | 0,05 | -0,66 |
| H4 | 66,96	| 67,12	| 67,95 | 67,1 | 67,21	| 44,71 | 51,97 | 4,09 | 4,48 | -0,11	| 1,16 |
| JMJD1C | 300 | 300 | 300 | 110,67 | -0,322219295 | 0,301029996 | -0,380211242 | 1,13076828 | 0,070581074 | -0,653212514 | 0,22184875 |


## Тепловая карта
![изображение](https://github.com/PhiiaNec/indiv_epigenomics/assets/60268019/4ac10cf0-52a8-4ff2-a02c-d19219d48b00)


## Вывод
По значениям таблиц мы можем сделать вывод о том, что белок гена JMJD1C появился начиная с поздних беспозвоночных (Drosophila)
