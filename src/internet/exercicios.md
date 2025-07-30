# 📘 Quiz – Fundamentos da Web
## 1. Oque é HTTP e URL? Qual a sua diferença?
## 2. Oque é um terminal?
## 3. Oque são motores de busca?
## 4. Oque faz o comando `mkdir`?
## 5. Como funciona a internet? Detalhe isso da melhor forma possivel!

# 🧩 Desafio 1 — Criando Estrutura com WSL
Abra seu `wsl`
1. Crie uma pasta dentro da sua area de trabalho chamada `teste`.
2. Crie um arquivo chamado `index.html` dentro da pasta `teste`.
3. Crie uma pasta `style` dentro da pasta `teste`.
4. Crie um arquivo `index.css` dentro da pasta `style`

# 💻 Desafio 2 — Editando com VSCode
Abra a seu `wsl`
1. Com comandos `cd` navegue até oa pasta `teste` 
2. Digite esse comando `code .` esse comando vai abrir o VScode
3. Selecione o arquivo `index.html` e cole isso.

```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Você conmpletou o desafio</title>
        <link rel="stylesheet" href="./style/index.css">
    </head>
    <body>
        <div>
            <H1>Você completou o desafio!</H1>
        </div>
    </body>
    </html>
```

4. Agora navegue até o arquivo `index.css`
5. Cole esse codigo aqui.

```css
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #89f7fe, #66a6ff);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
div {
    background-color: white;
    padding: 40px 60px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    text-align: center;
}
h1 {
    font-size: 2.5rem;
    color: #333;
    animation: pulse 1.5s infinite ease-in-out;
}
@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}
```
6. Agora vá até o arquivo ``index.html`` pelo explorador de arquivo e abra ele com seu navegador.

# 🧨 Desafio 3 — Explorando Comandos do Terminal
Abra o ``wsl`` para começar os comandos.
1. Navegue até a pasta teste.
2. Conte quantos arquivos ela possui com os comandos ``wc -l``
3. Remova o arquivo ``index.css`` especificamente sem comprometer outros arquivos.
4. Exclua toda a pasta teste.

# 💡 Resolução
Acessem [meu linkedin](https://www.linkedin.com/in/gabriel-florentino/) e mande uma mensagem com suas respostas e prints que vou mandar eles corrigidos.