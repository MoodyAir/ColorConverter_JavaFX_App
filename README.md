# ColorConverter
<p>Компьютекная графика. Лабораторная работа №1.</p>

## Задача
<p>Изучить цветовые модели: RGB, CMYK, HSV, HLS, XYZ, LAB, переход от одной модели к другой, исследовать цветовой график МКО.</p>
<p>Создать приложение/веб-приложение, позволяющее пользователю выбирать, а затем интерактивно менять цвет, показывая при этом его составляющие в трех моделях одновременно.</p>

## На проверку сдаются
* exe, который должен работать на ПК преподавателя под Windows/веб-приложение, размещенное в общем доступе;
* исходный код приложения на gitHub;
* сопроводительная документация.

## Основные требования к приложению
<p>В интерфейсе дать возможность пользователю задавать точные цвета (поля ввода), выбирать цвета из палитры (аналогично графическим редакторам), плавно изменять цвета (например, ползунки).</p>
<p>При изменении любой компоненты цвета все остальные представления этого цвета в двух других цветовых моделях пересчитываются автоматически. При «некорректных цветах» (например, при переходе из XYZ в RGB в вашем расчете получился выход за границы изменения рассчитываемого параметра) выдавать некое ненавязчивое предупреждение, что происходит обрезание-округление и т.п.</p>

## Вариант 18
<p>CMYK - XYZ - RGB</p>
