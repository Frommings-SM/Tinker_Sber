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
- **Печатные детали**: 1)[СтопаV3-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/СтопаV3.jpg), 2)[Булка-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Булка.jpg), 3)[НагрудникV2](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/НагрудникV2.jpg), 4)[Скамейка](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Скамейка.jpg), 5)[Наполнитель_Голени-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Наполнитель_Голени.jpg), 6)[Расширитель_РюкзакаV2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Расширитель_РюкзакаV2.jpg), 7)[Рамка_Рюкзака](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Рамка_Рюкзака.jpg), 8)[Кассета1](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кассета1.jpg), 9)[Крышка_Рюкзака](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Рюкзака.jpg), 10)[Рюкзак](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Рюкзак.jpg), 11)[Кассета2](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кассета2.jpg), 12)[Крышка_Тумблера](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Тумблера.jpg), 13)[Наполнитель_Бедра2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Наполнитель_Бедра2.jpg), 14)[Шея_Верх](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Шея_Верх.jpg), 15)[Стул](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Стул.jpg), 16)[Шея_Низ](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Шея_Низ.jpg), 17)[Голова](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Голова.jpg), 18)[Тазовая_Прокладка-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Тазовая_Прокладка.jpg), 19)[Голень-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Голень.jpg), 20)[Крышка_Корпуса](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Крышка_Корпуса.jpg), 21)[Днище_Корпуса](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Днище_Корпуса.jpg), 22)[Переднее_Ребро-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Переднее_Ребро.jpg), 23)[Заднее_Ребро-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Заднее_Ребро.jpg), 24)[Пластина](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Пластина.jpg), 25)[БедроV2-2шт(одна зеркально)](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/БедроV2.jpg).
- **Алюминиевые детали**: 1)[Кость таза-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Кость%20таза.jpg), 2)[Держатель_ТазаV2-2шт](https://github.com/EgorSolodnikov/Tinker_Sber/blob/main/3d_models/images/Держатель_ТазаV2.jpg), 
- **Провода**.
- **Платы**: 1)Тумблер, 2)Power_board, 3)Jetson nano v1, 4)Odroid-C4 v28, .
- **Моторы**: DM_8006-6шт, DM-J6006-4шт, Feetech_SERVO_SCS125, FeeTech_SCS40-2шт.
- **Крепежные детали**: **1)Гайка М2,5-6H ГОСТ 5916-7** - 16шт (далее Гайка М2,5), **2)Винты с плоской головкой ГОСТ Р ИСО 580** М3x6 - 8шт (далее Винт М3 х 6V2), М3x8 - 24шт (далее Винт М3 х 8V2), **3)Винты с цилиндрической головкой и шестигранным углублением под ключ ГОСТ Р ИСО 4762** М2,5х12 - 16шт, М3х5 - 4шт, М3х6 - 20шт, М3х10 - 16шт, М3х12 - 32шт, М3х16 - 16шт, М3х20 - 2шт, М4х8 - 50шт, М4х10 - 24шт, М4х12 - 4шт, М4х16 - 4шт, М4х20 - 4шт, М5х16 - 4шт, **4)Гайки ГОСТ Р 50273-92** М3-6H.NF - 30шт, М4-6H.NF - 12 шт.

[🔝 Наверх](#-навигация)

---

## 🪛 Электроника
- **🛠️ Простота**: Никаких сложных механизмов: робота можно собрать с помощью напечатнных на 3д принетере компонентов.  
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 🦿 Сборка ног
- **🛠️ Простота**: Никаких сложных механизмов: робота можно собрать с помощью напечатнных на 3д принетере компонентов
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 👕 Сборка туловища
- **🛠️ Простота**: ННикаких сложных механизмов: робота можно собрать с помощью напечатнных на 3д принетере компонентов
- **💰 Доступность**: Низкая стоимость компонентов, 90% деталей (моторы, контроллеры) доступны в рознице, что позволяет собрать его широкому числу энтузиастов.  
- **🤖 Упор на работу с ИИ**: Фреймворк **OmniRobLab** упрощает работу с сервоприводами, позволяя сосредоточиться на алгоритмах.  

[🔝 Наверх](#-навигация)

---

## 👤 Сборка головы
- **🛠️ Простота**: Никаких сложных механизмов: робота можно собрать с помощью напечатнных на 3д принетере компонентов
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
