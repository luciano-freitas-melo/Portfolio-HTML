# Coisinhas para adicionar no portfolio
## root para ter uma cor padrão no projeto
```css
:root {
    --main-color: #d12929;
    --text-color: #8793ae;
    --text-color2: #bdbdbd;
    --bg-color: #06192e;
    --big-font: 5rem;
    --big-font2: 3rem;
    --h2-font: 2rem;
    --p-font: 0.9rem;
}
```
## Link para os contatos - Smitizndsf
``` html
<div>
  <a href="https://www.linkedin.com/in/jo%C3%A3o-matheus-de-oliveira-schmitz-a40055269/"
   target="_blank">
    <i class='bx bxl-linkedin-square'> LinkedIn</i>
  </a>
  <a href="https://github.com/JoaoSchmitz"
    target="_blank">
    <i class='bx bxl-github' target="_blank"> GitHub </i>
  </a>
  <a href="mailto:jmatheus12349@gmail.com">
    <i class='bx bxl-gmail'> jmatheus12349@gmail.com </i>
  </a>
</div>
```
```css
.footer {
    padding: 10px 0;
}
.col {
    width: 25%;
}
.col a {
    color: #8793ae;
    font-size: 1.2rem;
    display: block;
    text-transform: capitalize;
    transition: .4s;
}
.col a:hover {
    color: var(--main-color);
    transform: translateX(-12px);
}

```
