# Конструктор сайта
---
Используя этот конструктор вы можете создать свой сайт.

Для этого в файле ```main.js``` укажите нужные данные при вызове функции ```movieConstructor()```

```js
movieConstructor('.app', {
  title: 'Ведьмак',
  background: 'witcher/background.jpg',
  favicon: 'witcher/logo.svg',
  fontColor: '#fff',
  backgroundColor: '#141218',
  subColor: '#9D2929',
  header: {
      logo: 'witcher/logo.png',
      social: [
          {
              title: 'Twitter',
              link: 'http://twitter.com',
              image: 'witcher/social/twitter.svg'
          },
          {
              title: 'Instagram',
              link: 'http://instagram.com',
              image: 'witcher/social/instagram.svg'
          },
          {
              title: 'Facebook',
              link: 'http://facebook.com',
              image: 'witcher/social/facebook.svg'
          }
      ],
      menu: [
          {
              title: 'Описание',
              link: '#'
          },
          {
              title: 'Трейлер',
              link: '#'
          },
          {
              title: 'Отзывы',
              link: '#'
          }
      ]
    },
  main: {
      genre: '2019, фэнтези',
      rating: 8,
      description: 'Ведьмак Геральт, мутант и убийца чудовищ, на своей верной лошади по кличке Плотва путешествует по Континенту. За тугой мешочек чеканных монет этот мужчина избавит вас от всякой настырной нечисти — хоть от чудищ болотных, оборотней и даже заколдованных принцесс.',
      trailer: 'https://www.youtube.com/watch?v=P0oJqfLzZzQ',
      slider: [
            {
                img: 'witcher/series/series-1.jpg',
                title: 'Начало конца',
                subtitle: 'Серия 1'
            },
            {
                img: 'witcher/series/series-2.jpg',
                title: 'Четыре марки',
                subtitle: 'Серия 2'
            },
            {
                img: 'witcher/series/series-3.jpg',
                title: 'Предательская луна',
                subtitle: 'Серия 3'
            },
            {
                img: 'witcher/series/series-4.jpg',
                title: 'Банкеты, ублюдки и похороны',
                subtitle: 'Серия 4'
            }
      ]
  }
})
```

В результате получится страница с фильмом:
![preview website](preview-witcher.png)