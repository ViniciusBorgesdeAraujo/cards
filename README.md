
**Como foi criado o card:**

1. **Estrutura HTML:**
   - O card foi estruturado usando elementos HTML como `<div>` para criar diferentes seções do card, como o contêiner principal (`<div class="card-container">`), cada cartão de usuário (`<div class="user-card">`), e dentro de cada cartão, áreas para imagem do usuário, informações e links sociais.
   - Utilizou-se `<img>` para exibir a imagem do usuário e `<h2>` e `<p>` para mostrar o nome e ocupação do usuário, respectivamente.
   - Para os links sociais, foram usados elementos `<a>` com classes específicas para estilização e ícones de fontes de ícones (Font Awesome neste caso), inseridos dentro desses elementos.

2. **Estilização CSS:**
   - O CSS foi utilizado para dar estilo ao card e aos seus elementos filhos.
   - Foram aplicados estilos de layout (como `display: flex` para o alinhamento dos cartões), estilos de fundo, bordas, sombras e margens para dar forma ao card.
   - Também foram utilizados estilos para ajustar o tamanho, a cor e a fonte do texto, bem como para definir o tamanho e a cor dos ícones sociais.

**Exemplo de Card em HTML e CSS:**

HTML:
```html
<div class="card">
    <img src="img/user_example.jpg" alt="Nome do Usuário" class="user-image">
    <div class="user-info">
        <h2>Nome do Usuário</h2>
        <p>Ocupação do Usuário</p>
        <div class="social-links">
            <a href="#" class="social-icon facebook"><i class="fab fa-facebook-f"></i></a>
            <a href="#" class="social-icon instagram"><i class="fab fa-instagram"></i></a>
            <a href="#" class="social-icon linkedin"><i class="fab fa-linkedin-in"></i></a>
        </div>
    </div>
</div>
```

CSS:
```css
.card {
    display: flex;
    align-items: center;
    background-color: white;
    border: 1px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    padding: 10px 25px;
    min-width: 355px;
}

.user-image {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-right: 10px;
}

.user-info {
    padding: 10px;
}

.user-info h2,
.user-info p {
    margin: 15px 0;
}

.social-links {
    display: flex;
    gap: 10px;
}

.social-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    color: white;
    background-color: #007bff;
    text-decoration: none;
    font-size: 20px;
}

.social-icon:hover {
    background-color: #0056b3;
}

.facebook {
    background-color: #3b5998;
}

.instagram {
    background-color: #e1306c;
}

.linkedin {
    background-color: #0077b5;
}
```

Com este exemplo, você pode criar múltiplos cards de usuário simplesmente duplicando o código do card dentro do seu HTML. Depois, você pode personalizar os detalhes, como as imagens e as informações do usuário, para se adequar ao seu projeto. Isso proporciona uma ótima prática para consolidar seu entendimento de HTML e CSS.

![image](https://github.com/ViniciusBorgesdeAraujo/cards/assets/105869015/c11c8715-c7a7-410a-982d-8f2d41ab0d50)
