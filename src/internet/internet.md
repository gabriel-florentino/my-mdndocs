# 📘 Fundamentos da Web
> Nos fundamentos, aboradaremos a parte mais básica da web, uma compreenção simplória de como tudo funciona. Aprenderemos tambem o básico sobre utilização de comandos em linha, que ajudão muito no dia a dia.

## Módulos do projeto
- [Voltar ao menu](../../README.md)
- [HTML- Em desenvolvimento]()
- [CSS- Em breve]()
- [Javascript - Em breve]()
- [GIT Github - Em breve]()
- [NPM - Em breve]()
- [Testes - Em breve]()

## 🤔 O que é isso?
### 🌐 Página na internet
> É um documento HTML acessado via navegador. Pode conter estilos (CSS), scripts (JavaScript) e mídia (imagens, vídeos, etc).

### 🏠 Site
> Um conjunto de páginas relacionadas e interligadas. Exemplo: um blog, uma loja online ou uma rede social.

### 💾 Servidor Web
> Um computador configurado para armazenar e entregar sites para os usuários. É onde o seu site "mora".

### 🔍 Motor de busca
> Ferramentas como Google ou Bing. Elas indexam o conteúdo da web e ajudam a encontrar o que você procura.

### 🔗 URL (Uniform Resource Locator)
> O "endereço" de uma página na web. Exemplo: https://meusite.com/sobre.

### 📡 HTTP (Hypertext Transfer Protocol)
> Um conjunto de regras usado para comunicação entre navegadores (clientes) e servidores. É a base da web.

## ⚙️ Como funciona tudo isso?
Quando você digita uma URL no navegador:

1. O navegador envia uma requisição HTTP para o servidor web daquele endereço.

2. O servidor responde com o conteúdo solicitado (HTML, CSS, JS, imagens, etc).

3. O navegador renderiza esse conteúdo na sua tela.

4. Se a URL estiver errada ou o servidor não responder, você recebe um erro (ex: 404 ou 500).

## 💻 Linha de Comando Básica
A linha de comando é uma interface de texto usada para interagir diretamente com o sistema operacional. É muito útil no desenvolvimento, automação e manipulação de arquivos.

### 🖥️ O que é o terminal?
Um terminal (ou shell) executa comandos do usuário. Exemplos:

- CMD (Prompt de Comando – Windows)
- PowerShell (Windows)
- Terminal (macOS/Linux)
- WSL (Subsistema Linux para Windows – recomendado)

#### ✅ Recomendação
Se você usa Windows, instale o WSL (Windows Subsystem for Linux). Ele permite usar comandos Unix no Windows, evitando problemas de compatibilidade.

### 🧪 Comandos básicos
#### 📁 Navegação e manipulação
<table>
  <thead>
    <tr>
      <th>Comando</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>cd</code></td>
      <td>Navega entre diretórios</td>
    </tr>
    <tr>
      <td><code>mkdir</code></td>
      <td>Cria pastas</td>
    </tr>
    <tr>
      <td><code>touch</code></td>
      <td>Cria arquivos ou atualiza data de modificação</td>
    </tr>
    <tr>
      <td><code>cp</code></td>
      <td>Copia arquivos ou diretórios</td>
    </tr>
    <tr>
      <td><code>mv</code></td>
      <td>Move ou renomeia arquivos</td>
    </tr>
    <tr>
      <td><code>rm</code></td>
      <td>Exclui arquivos ou diretórios</td>
    </tr>
    <tr>
      <td><code>ls</code></td>
      <td>Lista arquivos e pastas</td>
    </tr>
    <tr>
      <td><code>wc</code></td>
      <td>Conta linhas, palavras ou caracteres</td>
    </tr>
  </tbody>
</table>

#### 🌐 Baixar arquivos
`curl` – Faz requisições HTTP e baixa arquivos via URL

#### 🔍 Pesquisar texto
`grep` – Busca padrões de texto dentro de arquivos

#### 📖 Ver conteúdo
`cat` – Exibe conteúdo completo

`less` – Exibe conteúdo página por página

#### 🛠️ Manipular textos
`awk`, `tr`, `sed` – Editam, substituem ou formatam texto de forma automatizada

#### 🔗 Operadores úteis   
<table>
  <thead>
    <tr>
      <th>Comando</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>..</code></td>
      <td>Sobe um nível no diretório</td>
    </tr>
    <tr>
      <td><code>-l</code></td>
      <td>Exibe listagem detalhada</td>
    </tr>
    <tr>
      <td><code>-r</code></td>
      <td>Excluir tudo dentro de uma pasta</td>
    </tr>
  </tbody>
</table>

### 📎 Links para aprofundamento

- [🎥 Diolinux – Comandos básicos no terminal (YouTube)](https://www.youtube.com/watch?v=JEhVB4VHsTI)
- [📖 MDN Docs – Introdução à linha de comandoo](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Environment_setup/Command_line)

### ⛳ Desafios e exercicios
[Exercicios.md](./exercicios.md)