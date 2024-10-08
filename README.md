# ProceduralGen
# Генерация процедурного ландшафта с использованием Pygame

Этот проект демонстрирует базовую реализацию процедурной генерации ландшафта с использованием шума Перлина на Python с библиотекой Pygame. Генерируется 2D-игровой мир, который делится на чанки, каждый из которых содержит разные типы тайлов (например, почва, пустое пространство, враги, ресурсы). Игрок может перемещаться по миру, и новые чанки создаются динамически по мере того, как игрок приближается к границам текущих загруженных чанков.

![image](https://github.com/user-attachments/assets/a3d46046-37b1-4773-ad95-8f51392c136c)


## Возможности

- **Процедурная генерация ландшафта:** Используется шум Перлина для создания 2D массива, представляющего игровой мир, который разделен на разные типы местности.
- **Мир на основе чанков:** Игровой мир разделен на чанки, и новые чанки генерируются по мере перемещения игрока.
- **Перемещение игрока:** Базовое перемещение игрока с проверкой столкновений с определенными типами местности.
- **Отрисовка с помощью Pygame:** Мир и игрок отрисовываются с помощью Pygame, с простой системой камеры, которая удерживает игрока в центре экрана.

## Начало работы

### Необходимые зависимости

- Python 3.x
- Pygame
- NumPy
- Библиотека Perlin Noise

Вы можете установить необходимые пакеты с помощью pip:

pip install pygame numpy perlin-noise

## Управление
W, A, S, D: Перемещение игрока вверх, влево, вниз и вправо соответственно.

##  Будущие улучшения
- Расширение мира с добавлением более разнообразных типов местности.
- Добавление дополнительных игровых элементов, таких как враги или собираемые ресурсы.
- Реализация более продвинутой системы столкновений и взаимодействия игрока с окружением.
