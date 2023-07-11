## Setup

- [ ] npx storybook@latest init
- [ ] ng g c components/card --standalone --skip-tests
- [ ] ng g c components/navbar -standalone --skip-tests

## Navbar

### Template

```html
<nav>
  <div class="logo">
    <h1>chillflix</h1>
  </div>
</nav>
```

### Styles

```scss
nav {
  position: sticky;
  top: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem;
  background: rgb(255 255 255 / 40%);
  backdrop-filter: blur(8px);

  .logo h1 {
    font-size: 30px;
    text-transform: uppercase;
  }
}
```

## Card

### image urls

- [kung fu panda](https://upload.wikimedia.org/wikipedia/en/9/99/Kung_Fu_Panda_Game_Cover.jpg)
- [star wars](https://media.timeout.com/images/105863223/image.jpg)

### mock data

```ts
const cards: Card[] = [
  {
    title: "Star Wars IV",
    content: `Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora earum
    quibusdam in. Doloremque et autem, nam doloribus laborum suscipit
    accusamus.`,
    publishedDate: new Date(),
    imgUrl: "https://media.timeout.com/images/105863223/image.jpg",
  },
  {
    title: "Kung Fu Panda",
    content: `Kung Fu Panda is based on the movie Kung Fu Panda. Players initially control Po, who differs from the movie in that he possesses a basic level of martial arts skill.`,
    publishedDate: new Date(),
    imgUrl: "https://upload.wikimedia.org/wikipedia/en/9/99/Kung_Fu_Panda_Game_Cover.jpg",
  },
  {
    title: "Kung Fu Panda",
    content: `Kung Fu Panda is based on the movie Kung Fu Panda. Players initially control Po, who differs from the movie in that he possesses a basic level of martial arts skill.`,
    publishedDate: new Date(),
    imgUrl: "https://upload.wikimedia.org/wikipedia/en/9/99/Kung_Fu_Panda_Game_Cover.jpg",
  },
  {
    title: "Star Wars IV",
    content: `Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora earum
    quibusdam in. Doloremque et autem, nam doloribus laborum suscipit
    accusamus.`,
    publishedDate: new Date(),
    imgUrl: "https://media.timeout.com/images/105863223/image.jpg",
  },
  {
    title: "Kung Fu Panda",
    content: `Kung Fu Panda is based on the movie Kung Fu Panda. Players initially control Po, who differs from the movie in that he possesses a basic level of martial arts skill.`,
    publishedDate: new Date(),
    imgUrl: "https://upload.wikimedia.org/wikipedia/en/9/99/Kung_Fu_Panda_Game_Cover.jpg",
  },
  {
    title: "Kung Fu Panda",
    content: `Kung Fu Panda is based on the movie Kung Fu Panda. Players initially control Po, who differs from the movie in that he possesses a basic level of martial arts skill.`,
    publishedDate: new Date(),
    imgUrl: "https://upload.wikimedia.org/wikipedia/en/9/99/Kung_Fu_Panda_Game_Cover.jpg",
  },
];
```
