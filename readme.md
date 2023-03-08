## 🧾 Descrição

Este é um exemplo de código HTML, CSS e JavaScript que pode ser usado para criar uma página de login semelhante o site da Riot Games.

<h1>

## ⚙️ Estrutura

### HTML

- O código index.html começa com o elemento <!DOCTYPE html>, que define o tipo de documento como HTML. Em seguida, há um elemento html que contém todo o conteúdo da página. 
- Dentro do index.html, há um elemento head que contém informações sobre a página, como o título e o conjunto de caracteres. 
- O elemento meta especifica o conjunto de caracteres como UTF-8 e o elemento link é usado para vincular o arquivo CSS. 
- Além disso, há um elemento script que carrega o arquivo JavaScript para a página.

- Dentro do elemento body, há um elemento main que contém duas seções, section class="login" e section class="wallpaper". 
- A seção de login contém um formulário de login com campos para nome de usuário e senha, bem como botões para fazer login com uma conta do Facebook, Google ou Apple.
- Há também um checkbox para manter a sessão iniciada e um botão de login desativado. 
- A seção de wallpaper contém uma imagem de fundo para a página.

### CSS

- O arquivo CSS style.css contém estilos para a página HTML. 
- O estilo padrão * define as margens e os preenchimentos para 0 e a altura para 100%. 
- O estilo para html e body define a largura e a altura para 100% e remove as margens e os preenchimentos. 
- O estilo para a classe wrapper define o tamanho da caixa, a margem e a borda. 
- O estilo para a classe login__label define a fonte e a cor do texto. 
- O estilo para a classe login__button define a cor do plano de fundo e a cor da fonte. 
- O estilo para a classe login__button:disabled define a cor do plano de fundo e da fonte quando o botão estiver desativado. 
- O estilo para a classe login__icons define o tamanho e o espaço entre os botões. 
- O estilo para a classe login__icons img define o tamanho da imagem e o estilo para a classe login__label--checkbox define o estilo para o checkbox de manter a sessão iniciada.

### JavaScript

O código script.js adiciona funcionalidades aos inputs do formulário presente no código HTML anteriormente apresentado.

- Na primeira linha, é criada uma variável inputs que recebe um array com todos os elementos HTML com a classe .input. No código HTML, os elementos com essa classe são os campos de texto para nome de usuário e senha.

- Em seguida, é criada a variável button que recebe o elemento HTML com a classe .login__button, que é o botão de login.

- As funções handleFocus, handleFocusOut e handleChange são criadas para lidar com os eventos de foco nos campos de texto, saída do foco dos campos de texto e mudança dos valores dos campos de texto, respectivamente.

- A função handleFocus é chamada quando o usuário coloca o foco em um campo de texto. Ela adiciona uma classe .span-active ao elemento span anterior ao campo de texto.

- A função handleFocusOut é chamada quando o usuário tira o foco de um campo de texto. Se o valor do campo for vazio, a função remove a classe .span-active do elemento span anterior ao campo de texto.

- A função handleChange é chamada sempre que o valor de um dos campos de texto é alterado. Ela verifica se o campo de usuário está preenchido e se a senha tem pelo menos 8 caracteres. Se ambos estiverem preenchidos corretamente, o botão de login é habilitado. Caso contrário, o botão é desabilitado.

- Finalmente, adiciona os event listeners às funções criadas aos elementos de inputs, ou seja, aos campos de texto. Dessa forma, as funcionalidades de adicionar e remover classes, assim como habilitar ou desabilitar o botão de login, serão executadas de acordo com as ações do usuário nos campos de texto.

<h1>

<br>

## ✅ Resultado
<br>

![Login](https://i.imgur.com/FktRXFc.png)

<br>

## 💻 Autor

- [@luanferreira](https://github.com/fluanbrito)

<h1>

## 🚀 Sobre mim
Sou um grande entusiasta e apaixonado por tecnologia, empreendedorismo e inovação. Hoje, estou a cursar o curso de Sistema de Informação pelo Instituto Federal, faço uso profissionalmente de ferramentas e me aprofundo em temas como Marketing, Machine Learning AWS, Metodologias ágeis, Gestão de Projetos, Programação Web, Administração de Sistemas, Redes de computadores, entre outros.
