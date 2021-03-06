importance: 5

---

# Поведение "вложенная подсказка"

Напишите JS-код, который будет показывать всплывающую подсказку над элементом, если у него есть атрибут `data-tooltip`.

Условие аналогично задаче <info:task/behavior-tooltip>, но здесь необходима поддержка вложенных элементов. При наведении показывается самая вложенная подсказка.

Например:

```html
<div data-tooltip="Это – внутренность дома" id="house">
  <div data-tooltip="Это – крыша" id="roof"></div>
  ...
  <a href="http://ru.wikipedia.org/wiki/Три_поросёнка" data-tooltip="Читать дальше">Наведи на меня</a>
</div>
```

Результат в ифрейме с документом:

[iframe src="solution" height=300 border=1]

Вы можете использовать как заготовку решение задачи <info:task/behavior-tooltip>.

