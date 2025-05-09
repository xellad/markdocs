## How to calculate PPI

#### Исходные данные:

- **Диагональ**: 23.8" дюймов
- **Разрешение**: 1920 × 1080 пикселей
#### Теория:

Формула PPI  основана на геометрическом соотношении между цифровым разрешением и физическим размером экрана. 

Ключевым является вычисление диагонального разрешения через **теорему Пифагора** - корень квадратный из суммы квадратов горизонтального и вертикального разрешений (√(W²+H²)), что даёт общее количество пикселей по диагонали. 

Это значение затем делится на физический размер диагонали в дюймах, что и определяет линейную плотность пикселей (PPI). 
#### Формула PPI:
$$
PPI = \frac{\sqrt{W^2 + H^2}}{D}
$$
- $W$ = ширина в пикселях (1920)
- $H$ = высота в пикселях (1080)
- $D$ = диагональ в дюймах (23.8)
#### Пошаговый расчёт

1. **Вычисляем пиксели на диагонали**:
   
$$
\sqrt{1920^2 + 1080^2} = \sqrt{3,686,400 + 1,166,400} = \sqrt{4,852,800} \approx 2203 \text{ пикселя}
$$

- 1920² = 3 686 400 (пикселей по ширине)
- 1080² = 1 166 400 (пикселей по высоте)

2. **Подставляем в формулу**:

$$
PPI = \frac{2203}{23.8} \approx 92.56
$$

3. **Результат**:

$$
\text{PPI} \approx 93 \text { (округляем до целого)}
$$

