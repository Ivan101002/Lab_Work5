# Lab_Work5
# Виртуальная и дополненая реальность
Отчет по лабораторной работе #5 выполнил
- Попович Иван Алексеевич
- РИ-300022
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- 
- 
- 


Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Изучить принципы создания и настройки передвиженияпользователя в VR с помощью стиков на контроллерах и с помощью телепортации.

### Пошагово выполнить каждый пункт по примеру предоставленных видеоматериалов:
## Задание 1
### Пошагово выполнить каждый пункт по примеру предоставленных видеоматериалов:
- Открыть проект из 4 лабораторной работы;
Добавить на сцену дверь из ассетов;
- Добавить штурвал;
- Добавить кнопку;
- Сделать из 2 кубов кнопку и подложку для нее;
- Добавить rigidbody и зададим блок по не нужным осям, а также поставим continuous speculative в типе коллизии;
- Добавить Configurable Joint для того, чтобы кнопка возвращалась;
- Настроить его;
- Сделать блоки, чтобы кнопку нельзя было поднять;
- Запустить проект и проверить работоспособность;
- Сделать дверь с ручкой из блоков;
- Установить rigidbody на дверь и ручку;
- На дверь добавить скрипт XRGrabInteractable и ставимVelocityTracking в MovementType;
- В поле Colliders установить коллайдер ручки;
- На дверь и ручку добавить компонент HingeJoint и выставляем углы по которым они будут вращаться;
- Сделать скрипт, чтобы дверь нельзя было открыть, не повернув ручку;
- Добавить штурвал;
- Добавить вращение с помощью hinge joint;
- Добавить Collider на ручки;
- Добавить на сам штурвал компонент GrabInteractable и в поле Colliders добавить все ручки;
- Запустить проект и проверить корректность его работы.


## Вывод
За время лаб. работы я научился взаимодействию и созданию интерактивных объектов, созданию рычагов и прописыванию реакгирования с помощью скриптов на обытия переключения.

Скриншот сцены в Unty 3d после выполнения всех указаных действий в задании №1
![](/L5.png)

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**


