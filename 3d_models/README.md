# Сборка робота Tinker 

## 🔍 Навигация
- [🛠 Подготовка к сборке](#-подготовка-к-сборке)
- [🦿 Сборка ног](#-сборка-ног)
- [👕 Сборка туловища](#-сборка-туловища)
- [👤 Сборка головы](#-сборка-головы)
- [🪛 Электроника](#-электроника)
- [🦾 Изображения деталей](#-изображения-деталей)

---

## 🛠 Подготовка к сборке

Для сборки робота Tinker изначально необходимо подготовить следующий список комплектующих
- **Печатные детали**:
- 1.[СтопаV3-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/СтопаV3.jpg)
- 2.[Булка-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Булка.jpg)
- 3.[НагрудникV2](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/НагрудникV2.jpg)
- 4.[Скамейка](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Скамейка.jpg)
- 5.[Наполнитель_Голени-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Наполнитель_Голени.jpg)
- 6.[Расширитель_РюкзакаV2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Расширитель_РюкзакаV2.jpg)
- 7.[Рамка_Рюкзака](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Рамка_Рюкзака.jpg)
- 8.[Кассета1](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кассета1.jpg)
- 9.[Крышка_Рюкзака](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Рюкзака.jpg)
- 10.[Рюкзак](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Рюкзак.jpg)
- 11.[Кассета2](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кассета2.jpg)
- 12.[Крышка_Тумблера](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Тумблера.jpg)
- 13.[Наполнитель_Бедра2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Наполнитель_Бедра2.jpg)
- 14.[Шея_Верх](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Шея_Верх.jpg)
- 15.[Стул](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Стул.jpg),
- 16.[Шея_Низ](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Шея_Низ.jpg)
- 17.[Голова](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Голова.jpg)
- 18.[Тазовая_Прокладка-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Тазовая_Прокладка.jpg)
- 19.[Голень-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Голень.jpg)
- 20.[Крышка_Корпуса](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Корпуса.jpg)
- 21.[Днище_Корпуса](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Днище_Корпуса.jpg)
- 22.[Переднее_Ребро-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Переднее_Ребро.jpg)
- 23.[Заднее_Ребро-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Заднее_Ребро.jpg)
- 24.[Пластина](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Пластина.jpg)
- 25.[БедроV2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/БедроV2.jpg)
- **Алюминиевые детали**:
- 1.[Кость таза-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кость%20таза.jpg)
- 2.[Держатель_ТазаV2-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Держатель_ТазаV2.jpg)
- **Провода**.
- **Платы**:
- 1)Тумблер
- 2)Power_board
- 3)Jetson nano v1
- 4)Odroid-C4 v28
- **Моторы**:
- 1.DM_8006-6шт
- 2.DM-J6006-4шт
- 3.Feetech_SERVO_SCS125
- 4.FeeTech_SCS40-2шт.
- **Крепежные детали**:
- **1.Гайка М2,5-6H ГОСТ 5916-7** - 16шт (далее Гайка М2,5),
- **2.Винты с плоской головкой ГОСТ Р ИСО 580** М3x6 - 8шт (далее Винт М3 х 6V2), М3x8 - 24шт (далее Винт М3 х 8V2),
- **3.Винты с цилиндрической головкой и шестигранным углублением под ключ ГОСТ Р ИСО 4762** М2,5х12 - 16шт, М3х5 - 4шт, М3х6 - 20шт, М3х10 - 16шт, М3х12 - 32шт, М3х16 - 16шт, М3х20 - 2шт, М4х8 - 50шт, М4х10 - 24шт, М4х12 - 4шт, М4х16 - 4шт, М4х20 - 4шт, М5х16 - 4шт, **4)Гайки ГОСТ Р 50273-92** М3-6H.NF - 30шт, М4-6H.NF - 12 шт.

[🔝 Наверх](#-навигация)

---

## 🪛 Электроника
- **🛠️ Простота**: Никаких сложных передаточных механизмов — только 3D-печать и лазерная резка карбона.  
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 🦿 Сборка ног
В данном разделе описана пошаговая инструкция по сборке левой ноги для ее последующего соединения с корпусом. Правая нога собирается аналогично левой.

**Шаг 1:** 
Подготовьте следующие детали: мотор DM-J6006, левую СтопаV3, а также 6 винтов М3х10. (рис. 1)
<div align="right">
<img src="https://drive.google.com/file/d/11yJMNnp8TH_rq5XdZ-ExNwUxdluhTlNM/view?usp=drive_link" height="60" />
</div>
Прикрутите 6 винтов через стопу в мотор так, чтобы шляпки винтов находились с внешней стороны стопы, а разъемы смотрели  вверх. (рис. 2)
<div align="right">
<img src="https://drive.google.com/file/d/1VTg4vbpsR0MtCKVQsDplbbpYQ8sgiKG3/view?usp=drive_link" height="60" />
</div>

**Шаг 2:** 
Подготовьте следующие компоненты: ногу - заготовку, полученную на предыдущем шаге, шины питания и управления, левую Голень, а также 5 винтов М3х8.  (рис. 3)
<div align="right">
<img src="https://drive.google.com/file/d/1CuYiA4xt8F-XuetU2P8JqBMFTeS-ewvm/view?usp=drive_link" height="60" />
</div>

Подключите шины питания и управления к мотору выводами 1, после чего приложите  к мотору с внутренней стороны стопы Голень и прикрутите её на 5 винтов. При этом выводы проводов должны проходить углубление в голени и не должны  препятствовать сборке. (рис. 4)
<div align="right">
<img src="https://drive.google.com/file/d/1Faq402JzystNEKC_7rQi1Zuz663qekHA/view?usp=drive_link" height="60" />
</div>

**Шаг 3:**
Подготовьте следующие компоненты: ногу (заготовку, полученную на предыдущем этапе), мотор DM_8006, Наполнитель_Голени, 6 винтов М4х8, 4 винта М3х12, а также 4 гайки М3.  (рис. 5)
<div align="right">
<img src="https://drive.google.com/file/d/1XaQHnQpkZqNwRG8arQuQ6WGu4RowvcB-/view?usp=drive_link" height="60" />
</div>

Для начала проложите провода, выходящие из мотора 1, по дну голени так, чтобы они проходили через Т-образный вырез в детали и выходили в направлении “носка” стопы. Будьте внимательны: нельзя, чтобы провода сильно наползали друг на друга, они не должны выступать  из углубления  детали, иначе мотор не сможет провернуться! Далее возьмите мотор и прикрутите Мотор на 6 винтов М4х8 к Голени. Проверьте, вращается ли мотор, если да, то вы все сделали правильно (рис.6), если нет, то это значит, что во время сборки провода вылезли из Т-образного паза и мешают вращению мотора (рис. 7). Снимите мотор и соберите все заново.
<div align="right">
<img src="https://drive.google.com/file/d/1vkj1TKxJdXQSkv5ku237LTR8sL3keAt3/view?usp=drive_link" height="60" />
</div>
<div align="right">
<img src="https://drive.google.com/file/d/1WdYB9shPNUyp3685t3lJzG8PvKkb6wvw/view?usp=drive_link" height="60" />
</div>

Далее возьмите Наполнитель_Голени и вкрутите в него 4 винта М3х12. Перед тем, как прикручивать его к голени проверьте, устанавливаете ли вы его той стороной: радиусы на скруглениях этой детали с двух сторон отличаются, деталь нужна устанавливать большим радиусом со стороны DM_8006, а меньшей со стороны DM-J6006. (рис.8)
<div align="right">
<img src="https://drive.google.com/file/d/10eGe1BQRNiTXANoTgo-RNladPzj_JfCw/view?usp=drive_link" height="60" />
</div>

Прикрутите гайки с обратной стороны Голени для фиксации наполнителя. (рис. 9)
<div align="right">
<img src="https://drive.google.com/file/d/19E9ocX3-dM7zLp_egVq4oZHHB5Qzqn6p/view?usp=drive_link" height="60" />
</div>

**Шаг 4:**
Подготовьте следующие компоненты: ногу - заготовку, полученную на предыдущем шаге, мотор DM_8006, Наполнитель_Бедра2, БедроV2 , 14 винтов М4х8, 2 винта М3х10, 2 винта М3х16 а также 4 гайки М3.  (рис. 10)
<div align="right">
<img src="https://drive.google.com/file/d/17te-ol66zBZgjGmaaTJOTrDl1o_n5G6P/view?usp=drive_linkv" style="transform: rotate(90deg); height="60" />
</div>

Прикрутите БедроV2 к мотору DM_8006 заготовки так, чтобы выходы шин мотора смотрели в направлении паза БедраV2. При этом бедро не симметрично и та часть, которая визуально находится ближе к внутренней части мотора, после сборки должна “смотреть” в сторону носка Стопы.Прикрутите к БедруV2 второй мотор DM_8006 так, чтобы его порты также смотрели в направлении порта Бедра. Подключите выходы шин питания и управления к обоим моторам так, как показано на картинке.(рис. 11)
<div align="right">
<img src="https://drive.google.com/file/d/1ep-xEV4ymm5vQeGkoTQNOniv36sV2fOz/view?usp=drive_link" height="60" />
</div>

Возьмите наполнитель бедра и прикрутите его на 4 оставшихся винта так, чтобы визуально большая сторона наполнителя находилась внутри бедра. При этом винты, вкручивающиеся в толстые места - М3х16, а в тонкие - М3х10. Прикрутите их гайками с обратной стороны. (рис. 12) 
<div align="right">
<img src="https://drive.google.com/file/d/1r4ilFmAp9kMkTPzdt8dVMx1kQc_ljFES/view?usp=drive_link" height="60" />
</div>

Выходы же проводов должны проходить через отверстия в детали наполнителя. Если вы все сделали правильно, то должна получится нога как на изображении (рис. 13).
<div align="right">
<img src="https://drive.google.com/file/d/1r4ilFmAp9kMkTPzdt8dVMx1kQc_ljFES/view?usp=drive_link" height="60" />
</div>

**Шаг 5:** 
Подготовьте следующие компоненты: ногу - заготовку, полученную на предыдущем шаге, Кость_Таза, Тазовую_Прокладку, а также 4 винта  М4x10  (рис. 14)
<div align="right">
<img src="https://drive.google.com/file/d/1yY9tXRrz9HfXUHb5Wsug-j8ERClIheCp/view?usp=drive_link" height="60" />
</div>

Сначала возьмите Кость_Таза, с ее малой стороны приложите к ней Тазовую_Прокладку. Через эти две детали проденьте 4 винта М4х10, получив данную заготовку. (рис. 15)
<div align="right">
<img src="https://drive.google.com/file/d/1qjZm3lE2txBLu37Wx1HSPoAjzaEWKrud/view?usp=drive_link" height="60" />
</div>


Прикрутите полученную заготовку к вашей ноге, получив данную конструкцию. (рис. 16)
<div align="right">
<img src="https://drive.google.com/file/d/1VFhcNNQxgkQGOXVDwmXHmOJ8JxoDzgRT/view?usp=drive_link" height="60" />
</div>


На данном этапе вы завершили подготовку заготовки ног, далее можно приступать к сборке туловища и их соединению с ним.

[🔝 Наверх](#-навигация)

---

## 👕 Сборка туловища
- **🛠️ Простота**: Никаких сложных передаточных механизмов — только 3D-печать и лазерная резка карбона.  
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 👤 Сборка головы
- **🛠️ Простота**: Никаких сложных передаточных механизмов — только 3D-печать и лазерная резка карбона.  
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 🦾 Изображения деталей
- **СтопаV3**:<div align="right">
<img src="https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/СтопаV3.jpg" height="60" />
</div>

[🔝 Наверх](#-навигация)

---
✨ Больше открытых проектов: [OpenLoong](https://www.openloong.org.cn/cn).This folder contains the 3D models and design files for Tinker.
