# Фінальний проєкт

## Критерії виконання


1. Створити папку для проекту під назвою `genius-final-project`
2. Виконати семантичку розмітку сторінки у файлі `index.html`. Макет сайту для косметологічної клініки [Dog Club](https://www.figma.com/file/rTCMsYAj44dHB4dfwo7cOZ/Dog-Club?node-id=123%3A177&t=kJwseFkErM76jFqO-1)
3. Перевірити код на валідність через [W3C Validator](https://validator.w3.org/#validate_by_uri) 
4. Задати кольори для текстових елементів (посилання, заголовки, текст, тощо ) у файлі `styles.css`, попередньо задавши до цих елементів описові класи. Також задати колір фону для елементів, де це потрібно
5. Усі кольори з макету помістити в CSS-змінні на початку файлу `styles.css`
6. Усі зображення з макету оптимізувати через [Squoosh](https://squoosh.app/) і експортувати в папку `images`
7. Підключити шрифт з [Google Fonts](https://fonts.google.com/) на сторінку, або завантажити шрифти локально в проект (краще підключити локально)
8. Задати властивості шрифту текстовим елементам
9. Виконати flex-розмітку в кожній секції, шапці та підвалі сторінки. 
10. Додати внутрішні і зовнішні відступи до елементів, де це потрібно.
11. Створити контейнер, який обмежує і вирівнює контент сторінки по центру.
12. Додати фонове зображення, градієнт і тінь до елементів, де це потрібно.
13. Всі іконки з макету експортувати, оптимізувати через [SVGOMG](https://jakearchibald.github.io/svgomg/) і додати до SVG-спрайту, створеного через [IcoMoon](https://icomoon.io/) (також можна оптимізувати одразу весь спрайт).
14. Абсолютно спозиціонувати елементи, де це потрібно (декоративні зірочки в секції "Про нас" і фонове зображення у підвалі).
15. Додати CSS-переходи до інтерактивних елементів (посилань, кнопок, полей вводу, тд). Час переходи встановити `0.2s`.
16. Додати анімацію за допомогою директиви `@keyframes` до декоративних зірочок в секції "Про нас". Анімацію створити на власний смак, як варіант - одночасне обертання і зміна масштабу.
17. Створити модальне вікно і додати функціонал його роботи, попередньо підключивши файл `modal.js`.
18. Виконати розмітку форми із полями вводу у модальному вікні і секції "Як нас знайти".
19. Додати валідацію до полей вводу:
	1. кожне поле є обовʼязковим
	2. імʼя та прізвище складається із двох слів
	3. номер телефону має формат `+380ХХХХХХХХХ`
	4. пошта має традиційний формат через `@`
20. Для стилів створити наступну структуру, розбивши CSS-файл на SCSS-файли і директорії:<img width="378" alt="Screenshot 2023-03-22 at 22 08 47" src="https://user-images.githubusercontent.com/124382088/227026318-836b83e3-888e-42b7-9b6f-52b3f04f9923.png">
21. Виконати іменування класів в проекті за методологією БЕМ.
22. Зробити адаптив сторінки за стратегією Mobile first, використовуючи медіа-запити на трьох точках перелому: `480px`, `768px`, `1200px`.
23. Всі зображення (як контентні, так і фонові) повинні бути оптимізовані під retina-дисплеї.
24. Створити мобільне меню і додати функціонал його роботи, попередньо підключивши файл `mobile-menu.js`.
