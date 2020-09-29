# LAB3.0

Суть третей лабораторной работы заключается в том, чтобы обучить нейронную сеть MobileNetV2[1] для решения задачи классификации с использованием набора данных Intel Image Classification.


### 1) Графики со случайными весовыми коэффициентами 

### 1. lr = 0.000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/1.png)

### 2. lr = 0.00001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/3.png)

### 3. lr=0.0001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/5.png)

### Лучшие результаты показывает Сеть с lr=0.000001


### 2) Графики imagenet

### 1. lr = 0.000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/2.png)

### 2. lr = 0.00001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/4.png)

### 3. lr=0.0001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/6.png)

### Лучшие результаты показывает Сеть с lr = 0.000001


### 3) Обучение нейросети применяя процедуру модификации весов согласно метода градиентного спуска только к слоям классификатора

### 1. lr=0.000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/7.png)

### 2. lr=0.0000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/8.png)

### 3. lr=0.00001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/9.png)

### Лучшие результаты показывает Сеть с lr=0.00001


### 4) Применяем процедуру модификации весов согласно метода градиентного спуска ко всей нейронной сети, предобученной в предыдущем пункте

### 1. lr=0.000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/10.png)

### 2. lr=0.0000001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/11.png)

### 3. lr=0.00001
![Image alt](https://github.com/PavelPoukh/LAB3.0/blob/master/graphs/12.png)

### Лучшие результаты показывает Сеть с lr=0.000001
