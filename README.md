Название: Набор адаптивных карточек  

Стек: HTML, CSS (Tailwind)

Задачи: 
1. Сверстал асимметричную сетку из 5 карточек отзывов на базе CSS Grid и Tailwind CSS, реализовав её адаптивное перестроение из десктопной матрицы 4х2 в одноколоночный поток на мобильных устройствах.
                        
Фичи:
1. Объединил повторяющиеся утилитарные классы Tailwind в семантические CSS-компоненты с помощью @apply, что значительно повысило читаемость DOM-дерева и упростило дальнейшую поддержку кода.
2. Реализовал изолированную двухколоночную Grid-сетку с точными пропорциями для шапки карточки.
3. За счет свойства row-span-2 для аватара добился идеального вертикального центрирования имени автора и его статуса без использования вложенных HTML-контейнеров.
4. Инкапсулировал генерацию кавычек для цитат непосредственно в стили Tailwind с помощью псевдоэлементов before: и after:. Это исключило появление лишних символов в HTML-разметке и гарантировало семантическую чистоту контента.
5. Расширил базовую тему Tailwind, интегрировав уникальную палитру цветов проекта без потери стандартных утилит фреймворка.


# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### Built with

- Semantic HTML5 markup
- CSS Grid
- Tailwind CSS
- Mobile-first workflow

## Author

- [Website](https://mishanep.com)
- Frontend Mentor - [@michey85](https://www.frontendmentor.io/profile/michey85)
- Twitter - [@pcgramota](https://www.twitter.com/pcgramota)
