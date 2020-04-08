Установка Pygame
```bash
pip3 install pygame
```
Таблица с кодами для комбинации
------------------------------------------------------------------------------------------------
| 0 – части тела                 | 30 частей тела                                               |
| 1 – вид движения               | остановка, нарушение баланса, падение, поворот, прыжок, раскрытие, свободное передвижение, сжатие, скручивание, смена опоры |
| 2 – продолжительность движения | длительно, мгновенно                                         |
| 3 – качество движения          | взмах, касание, покачивание, скольжение, удар, хлесткий удар |
| 4 – пространство               | единственный фокус, подвижный фокус                          |
| 5 – способ исполнения движения | импакт, импульс, непрерывное движение, отскок, свинг         |
| 6 – фигура                     | круг, линия, ломаная линия, точка, треугольник, четырехугольник |

## Принцип работы программы

1. Пользователь вводит интервал между повторами комбинации в секундах, например, **5**
2. Далее вводит комбинацию, состоящую из цифр от 0 до 6, например, **6125**
3. Затем вводит количество повторов комбинации, например, **3**

![img](https://lh6.googleusercontent.com/49jLRMphIfYsjpMgDK4TINFBZmzVBh9_8Q5ec_bl5nd-Uq3NGS3J3kQb5MOW8g4VsD_UiSy9b3bo2KLKqz3Cb7ktNFW7bTqV71x0BbdncQUU4ETLdFagk1Sh8CUnCMMwej0Seo-f)

Видео демонстрация работы программы: https://youtu.be/D2S3VfFqfTY

Текстовая демонстрация:

- случайная фигура(6)-случайный вид движения(1)-случайная продолжительность движения(2)-случайный способ исполнения движения(5)
  **...5 секунд тишины…**
- случайная фигура(6)-случайный вид движения(1)-случайная продолжительность движения(2)-случайный способ исполнения движения(5)
  **...4 секунды тишины…**
- случайная фигура(6)-случайный вид движения(1)-случайная продолжительность движения(2)-случайный способ исполнения движения(5)
  **...3 секунды тишины…**

Если количество повторов (например, 10) больше пауз (например, 5), то пауза будет убывать до единицы: 5, 4, 3, 2, 1, 1, 1, 1, 1, 1
