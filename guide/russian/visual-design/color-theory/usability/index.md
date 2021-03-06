---
title: Color and Usability
localeTitle: Цвет и удобство использования
---
## Цвет и удобство использования

Подобно отклонениям в [представлении цвета визуальными проявлениями](/visual-design/color-theory/index.md) , человеческие глаза и мозг интерпретируют цвета различными способами.

Около одного из двадцати человек имеют цветную слепоту. \[2\] Это почти миллиард человек! Цветовая слепота заключается в том, что диапазон разных цветов интерпретируется как оттенки одного цвета. Иногда человек не знает, что они испытывают цветную слепоту, потому что цвета «выглядят нормальными» для них. Это имеет серьезные последствия для контрастных цветов между буквами и их фоном, а также для предупреждений, в которых, например, цвет представляет собой контекст важности. Даже что-то такое же простое, как передача «стоп» и «идти», проблематично, так как наиболее распространенная форма цветовой слепоты - это то, где красный и зеленый появляются одинаково.

Более одного процента населения имеет [другие виды значительных визуальных потерь (Wikipedia.org)](https://en.wikipedia.org/wiki/Visual_impairment) . Убытки могут включать в себя чувствительность к слишком большому или слишком малому контрасту, искажениям и ограничениям в пределах видимости обзора (близорукость или дальнозоркость).

Экран компьютеров способен отображать контрасты, которые примерно на два контраста доступны на бумаге.

Вот рекомендации, которые помогут решить проблемы проектирования, позволяющие учитывать эти отклонения, не отрицательно влияя на опыт других людей. Эти рекомендации также помогают более эффективно [адаптировать технологию (Wikipedia.org)](https://en.wikipedia.org/wiki/Assistive_technology#Visual_impairments) .

### Определения

**яркость** Чтобы определить яркость для рекомендаций, суммируйте значения цвета RGB. Если шрифт имеет цвет RGB (255,0,0), это означает, что он имеет 100% красный цвет и 0% зеленого и синего света. Яркость составляет 255 + 0 + 0 = 255. Максимальная яркость белого цвета равна 255 + 255 + 255 = 765.

**контраст** Чтобы определить контраст для рекомендаций, вычтите _яркость_ между двумя цветами.

### Методические рекомендации

1.  Избегайте превышения контрастности на бумаге в тексте. Разница яркости между текстом и текстом не менее 300, если не 400 - немного больше для маленьких шрифтов, меньше для больших шрифтов. Если цвет шрифта Красный, значение RGB может быть (255,0,0) - яркость 255 из 765. Если фон желтый, значение RGB может быть (255,255,0) = 510. Разница между 510 и 255 равна 255. Этот пример контрастности слишком низок и приводит нас к следующему руководству.
    
2.  Для проверки контраста и адаптации цветовой слепоты предположим, что красный и зеленый цвета основного цвета имеют один и тот же цвет. Самая распространенная форма цветной слепоты - красная и зеленая. Это означает, что для эффективности с важным сообщением следует учитывать, что цвета Red RGB (255,0,0), Green RGB (0,255,0) и «Olive» \[1\] RGB (127,127,0), по сути, одного цвета с тем же цветом контраст. Для расчета контраста желтый RGB (255,255,0) имеет двойную яркость любого основного цвета. Два основных цвета по-прежнему дают вдвое большую яркость.
    

### Резюме

Хорошей новостью является то, что по-прежнему существует большая гибкость при выборе эффективного цветового палета, который подходит для читателей.

[Это руководство по быстрому стилю поможет вам принять ваш запрос на тягу](https://github.com/freecodecamp/guides/blob/master/README.md) .

#### Дополнительная информация:

1.  [Веб-цвета (Wikipedia.org)](https://en.wikipedia.org/wiki/Web_colors#Web-safe_colors)
    
2.  [Цветная слепота (Wikipedia.org)](https://en.wikipedia.org/wiki/Color_blindness)