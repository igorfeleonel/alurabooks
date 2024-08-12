![Mockup do Alura Books (1)](https://github.com/user-attachments/assets/743bf64b-e22b-4eae-a51b-ea34378143f5)

# Alura Books
Alura Books é um projeto desenvolvido no Alura esse projeto tem um objetivo de aprimorar as minhas habilidades de HTML e CSS que tem uma construção de layouts responsivo

## 🔥 Introdução
O objetivo desse projeto, funcionalidade de como interpretar um protótipo de site criado pelo o Figma, que tem se desenvolvendo de mobile-first no desenvolvimento de site, que tem como se transformar o site de layouts responsivo

### ⚙️ Pré-requisitos
A instalação do projeto que precisa instalar o projeto tem como fazer o Download ZIP no botão do lado direito perto do repositório tem um botão verde quando ao clicar no Code vai aparecer o Download ZIP
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura Books</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<!--ALURA BOOKS - Feito por Igor Felipe-->
<body>
    <header class="cabeçalho">
        <div class="container">
            <input type="checkbox" id="menu" class="container__botao">
            <label for="menu">
                <span class="cabeçalho__menu-hamburguer container__imagem"></span>
            </label>
            <ul class="lista-menu">
                <li class="lista_menu__titulo">Categorias</li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Programação</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Front-end</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Infraestrutura</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Business</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Design & UX</a>
                </li>
            </ul>
            <img src="image/Logo (1).png" alt="Logo do Alura books" class="container__imagem">
            <li class="container__titulo"><b class="container__titulo--negrito">Alura</b>Books</li>
        </div>
```
```
@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrosel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");
@import url("styles/rodapé.css");

:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
    --laranja: #EB9B00;
    --azul-degrade: linear-gradient(97.54deg, #002F52 35.49%, #326589 165.37%);
    --fonte-principal: "Poppins";
    --azul: #002F52;
    --fonte-secundario: "Josefin Sans";
    --preto: #000000;
    
}

body {
    background-color: var(--cor-de-fundo);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}
```
### 🔨 Guia de instalação
Como que pode executar o projeto pasta a clicar no Code no botão verde vai aparecer o Dowloand ZIP assim quando clicar vai carregar o código do Dowloand ZIP quando instalar é obrigatóriamente extrair o arquivo na pasta a onde que foi criado quando realizar esse processso de instalamento tem que abrir o editor de texto Vs Code ou de sua preferência qual editor que você está utilizando

Etapas para instalar:

Codigo, exemplos

```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura Books</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
```
Passo 2:

```
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```
Codigo, exemplos
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura Books</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<!--ALURA BOOKS - Feito por Igor Felipe-->
<body>
    <header class="cabeçalho">
        <div class="container">
            <input type="checkbox" id="menu" class="container__botao">
            <label for="menu">
                <span class="cabeçalho__menu-hamburguer container__imagem"></span>
            </label>
            <ul class="lista-menu">
                <li class="lista_menu__titulo">Categorias</li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Programação</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Front-end</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Infraestrutura</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Business</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Design & UX</a>
                </li>
            </ul>
            <img src="image/Logo (1).png" alt="Logo do Alura books" class="container__imagem">
            <li class="container__titulo"><b class="container__titulo--negrito">Alura</b>Books</li>
        </div>

        <ul class="opções">
            <li class="opções__item">Categorias</li>
            <li class="opções__item"><a href="#" class="opções__link">Favoritos</a></li>
            <li class="opções__item"><a href="#" class="opções__link">Minha estante</a></li>
        </ul>

        <div class="container">
            <a href="#"><img src="image/Favoritos (1).png" alt="Meus favoritos" class="container__imagem" container__imagem-transparente></a>
            <a href="#"><img src="image/Sacola.png" alt="Carrinhos de compras" class="container__imagem"></a>
            <a href="#"><img src="image/Usuario.png" alt="Meu perfil" class="container__imagem"></a>
        </div>
    </header>
    <section class="banner">
        <h2 class="banner__titulo">Já sabe por onde começar?</h2>
        <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
        <input type="search" class="banner__pesquisa" placeholder="Qual será sua próxima leitura?">
    </section>
    <section class="carrosel">
        <h2 class="carrosel__titulo">Novos lançamentos</h2>
        <!-- Slider main container -->
        <div class="swiper">
            <!-- Additional required wrapper -->
            <!-- If we need pagination -->
            <div class="swiper-pagination"></div>

            <div class="swiper-wrapper">
                <!-- Slides -->
                <div class="swiper-slide"><img src="image/Guia Front-end.png"
                        alt="Livro sobre Guia Front-end do Alura books"></div>
                <div class="swiper-slide"><img src="image/Liderança.png"
                        alt="Livro sobre Liderança design do Alura books"></div>
                <div class="swiper-slide"><img src="image/Javascript.png" alt="Livro sobre Javascript Alura books">
                </div>
                <div class="swiper-slide"><img src="image/Nodejs.png" alt="Livro sobre Nodejs"></div>
                <div class="swiper-slide"><img src="image/ReactNative.png" alt="Livro sobre ReactNative"></div>
                <div class="swiper-slide"><img src="image/Acessibilidade.png" alt="Livro sobre Acessibilidade"></div>
            </div>

            <!-- If we need navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>

        <div class="card">
            <!-- 1 linha -->

            <div class="card__descrição">
                <!-- 1 coluna -->
                <div class="descrição">
                    <h3 class="descrição__titulo">Talvez você também se interesse por...</h3>
                    <h2 class="descrição__titulo-livro">Angular 11 e Firebase</h2>
                    <p class="descrição__texto">Construindo uma aplicação integrada com a plataforma do Google.</p>
                </div>
                <!-- 2 coluna -->
                <img src="image/Angula (1).png" class="descrição__imagem">
            </div>

            <!-- 2 linha -->
            <div class="card__botões">
                <!--1 coluna-->

                <ul class="botões">
                    <li class="botões__item"><img src="image/Favoritos (1).png" alt="Favoritar livros"></li>
                    <li class="botões__item"><img src="image/Sacola.png" alt="Adicionar nos carrinhos de compras"></li>
                </ul>
                <!-- 2 coluna -->
                <a href="#" class="botões__ancura">Saiba mais</a>
            </div>
        </div>

        <!-- 1 linha card autora -->

        <div class="card__autora">

            <!-- 2 linha card autora -->
            <div class="autora__descrição">
                <div class="autora">
                    <img src="image/Estrelinhas.png" alt="cinco estrelas">
                    <h3 class="descrição__titulo">Autora do Mês</h3>
                    <h2 class="titulo-autora">Juliana Agarikov</h2>
                    <p class="descrição__texto">Analista de sistemas e escritora, Juliana é especialista em Front-End.
                    </p>
                </div>

                <img src="image/Perfil-escritora 1.png" class="image__escritora" alt="descrição autora">
            </div>

            <!-- 3 linha card autora -->

            <div class="autora__imagem">

                <ul class="favoritos__compras">
                    <li class="autora__item"><img src="image/Favoritos (1).png" alt="Favoritos autora"></li>
                    <li class="autira__item"><img src="image/Sacola.png" alt="Adicionar no carrinhos de compras"></li>
                </ul>
                <!-- 4 linha autora saiba mais -->
                <a href="#" class="autora__saiba-mais">Saiba Mais</a>
            </div>
        </div>
    </section>
    <!--ALURA BOOKS - Feito por Igor Felipe-->
    <section class="tópicos">
        <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
        <ul class="tópicos__lista">
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Android</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Marketing Digital</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Agile</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Startups</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">HTML & CSS</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Python</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">OO</a>
            </li>
            <li class="tópicos__item">
                <a href="#" class="tópicos__link">Java</a>
            </li>
            </li>
            </li>
        </ul>
    </section>
    <!--ALURA BOOKS - Feito por Igor Felipe-->
    <section class="contato">
        <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
        <p class="contato__texto">Atualizações de e-books, novos livros, promoções e outros.</p>
        <input type="email" placeholder="Cadastre seu e-mail" class="contato__email">
    </section>

    <hr />
    
    <footer class="rodapé">
        <h2 class="rodapé__titulo">Grupo Alura</h2>
    </footer>

    <!-- 3 linha card autora -->

    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    <script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
                el: '.swiper-pagination',
                type: 'bullets',
            }
        });
    </script>
</body>

</html>
```
## 📦 Tecnologias usadas:
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />

## 💡 Expressões de gratidão

* Para suporte, mande um email para igorzinyt999@gmail.com.
* Link do meu linkedin [Meu linkedin](www.linkedin.com/in/igorfeleonel)
