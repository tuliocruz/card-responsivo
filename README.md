### Card HTMl5 + CSS3

# Card-responsivo.md

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

- Card Responsivo para dispositivos moveis e alta resolução;
- Codigo limpo e simples para carregamento rápido;


####CSS3　

```css
/* Define a codificação da folha de estilo para Unicode UTF-8 */
@charset "UTF-8";

/* Carregando font do Google fonts */
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;400;500;700&display=swap');

/* CSS Reset */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #3F3752;
    font-family: 'Ubuntu', sans-serif;
}

.container {
    position: relative;
    width: 80%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 5.5rem;
    margin-left: 10%;
    margin-right: 10%;
    gap: 20px;
    flex-wrap: wrap;    
}

.container .tiposServicos {
    position: relative;
    width: 350px;
    height: 280px;
    background: #51446E;
    border-radius: 20px;
    overflow: hidden;
}

.container .tiposServicos .icone {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: var(--i);
    transform: 1s;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 2;
    transition-delay: 0.25s;
}

.container .tiposServicos:hover .icone {
    top: 30px;
    left: calc(50% - 40px);
    width: 80px;
    height: 80px;
    border-radius: 50%;
    transition: 0.8s;
    transition-delay: 0s;
}

.container .tiposServicos .icone ion-icon {
    font-size: 5em;
    color: #FFF;
    transition:1s;
}

.container .tiposServicos:hover .icone ion-icon {
    font-size: 2em;
}

.container .tiposServicos .conteudo {
    position: relative;
    padding: 20px;
    color: #FFF;
    text-align: center;
    margin-top: 100px;
    z-index: 1;
    transform: scale(0);
    transition: 0.8s;
    transition-delay: 0s;
}

.container .tiposServicos .conteudo {
    transform: scale(1);
    transition-delay: 0.25s;
}

.container .tiposServicos .conteudo h2 {
    margin-top: 10px;
    margin-bottom: 5px;
}

.container .tiposServicos .conteudo p {
    font-weight: 300;
    line-height: 1.5em;
}
```

####HTML code

```html

<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Card Responsivo HTML5 CSS3 </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="tiposServicos">
            <div class="icone" style="--i:#4EB7FF">
                <ion-icon name="logo-designernews"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Desing Fluido</h2>
                <p>Icone com design fluido e hover do mouse</p>
            </div>
        </div>  
        
        <div class="tiposServicos">
            <div class="icone" style="--i:#FD6494">
                <ion-icon name="code-outline"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Codigo</h2>
                <p>Codigo com design fluido e hover do mouse</p>
            </div>
        </div> 

        <div class="tiposServicos">
            <div class="icone" style="--i:#43F390">
                <ion-icon name="search-outline"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Busca</h2>
                <p>Busca com design fluido e hover do mouse</p>
            </div>
        </div> 

        <div class="tiposServicos">
            <div class="icone" style="--i:#FFB508">
                <ion-icon name="analytics-outline"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Analise</h2>
                <p>Analise com design fluido e hover do mouse</p>
            </div>
        </div> 

        <div class="tiposServicos">
            <div class="icone" style="--i:#37BA82">
                <ion-icon name="bar-chart-outline"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Graficos</h2>
                <p>Graficos com design fluido e hover do mouse</p>
            </div>
        </div> 

        <div class="tiposServicos">
            <div class="icone" style="--i:#CD57FF">
                <ion-icon name="videocam-outline"></ion-icon>
            </div>
            <div class="conteudo">
                <h2>Chamada</h2>
                <p>Chamada com design fluido e hover do mouse</p>
            </div>
        </div> 
    </div>

    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
```

###Images

Image:

![](https://i.ibb.co/4M3ZDZ1/card-resposivo-01.jpg)

> Normal.

![](https://i.ibb.co/QjhKyLC/card-resposivo-02.jpg)
> Hover do mouse.
                
----

```

###Fim
