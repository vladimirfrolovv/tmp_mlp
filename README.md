# MLP
Implementation project Multilayer Perceptron on c++

В данном проекте реализована искусственная нейронная сеть в виде многослойного перцептрона для рапосзнавания 26 букв латинского алфавита на языке С++. Реализован графический интерфейс на QT. 

## Features

- Обучение нейросети на открытом датасете emnist.

- 2 различных архитектуры нейросети матричная(нейроны и веса хранятся в виде векторов матриц) и векторная (каждый нейрон представляется в виде некоторого объекта узла).

- Использован стохастический градиентный спуск.

- В качестве функции активации была использовалась сигмоида.

- Выбор колличества слоев в сети (2-5), колличества эпох, а также применение кросс-валидации.
  
- Загрузка и сохранение весов нейросети.

- Распознавание буквы с картинки либо рукописно в интерфейсе.

- Проверка результатов на тестовой выборке с выводом контрольных значений.


## Installation

1. Для cборки проекта, находясь в директории MLP, прописать:
```sh
make
```
2. Запустить проект:
```sh
make open
```

  
