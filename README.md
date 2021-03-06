В данной лабораторной работе было проведено детектирование объектов на наборе снимков с беспилотных летательных аппаратов VisDrone-Dataset с использованием нейронных сетей глубокого обучения примере сети SSD. Также был проведен анализ, а именно посчитаны средняя точность детектирования объектов, количество пропущенных объектов, количество ложных тревог для различных порогов IoU.

1) КАЧЕСТВЕННЫЙ АНАЛИЗ НЕСКОЛЬКИХ СНИМКОВ

Сделав анализ снимков, можно заметить некоторое несовпадение объектов входных данных и данных после обучения сети. Можно выделить несколько тому объяснений:
- сеть была обучена на других данных
- из-за различных классов в входных данных и данных после обучения сети нам пришлось их совмещать самим
- кол-во классов значительно отличалось (80 - COCO, 12 - во входных данных) 

![Image alt](https://github.com/ViktSham/Lab_2/blob/master/2.PNG?raw=true)
![Image alt](https://github.com/ViktSham/Lab_2/blob/master/4.PNG?raw=true)
![Image alt](https://github.com/ViktSham/Lab_2/blob/master/6.PNG?raw=true)

2) ТАБЛИЦА ДЛЯ ПУНКТА 4

![Image alt](https://github.com/ViktSham/Lab_2/blob/master/Task_4a.PNG?raw=true)

3) ТАБЛИЦА ДЛЯ ПУНКТА 5

![Image alt](https://github.com/ViktSham/Lab_2/blob/master/Task_5.PNG?raw=true)
