# scss-trab

## Objetivo

<p>
    Este projeto foi desenvolvido com o objetivo de demonstrar a eficácia e praticidade do pré-processador SASS (Syntactically Awesome Stylesheets). A utilização do SASS proporciona uma experiência de desenvolvimento mais eficiente, permitindo a criação de estilos avançados e reutilizáveis de forma organizada e estruturada. Através da modularidade, variáveis e outras funcionalidades poderosas do SASS, este projeto visa destacar as vantagens dessa ferramenta no desenvolvimento de estilos para websites. 
</p>

<p>
    O website trata-se de uma loja de camisas online feita utilizando SASS, HTML e CSS. Ele tem por objetivo mostrar diversos produtos (camisas) à venda, como novas coleções, camisas mais populares, lançamentos e camisas em destaque.
</p>

## Instalação dos softwares necessários

<p>
    Este guia fornece instruções detalhadas para configurar o SASS (Syntactically Awesome Stylesheets) em seu ambiente de desenvolvimento. O SASS é uma poderosa extensão de CSS que permite uma escrita mais limpa, eficiente e fácil de manter dos estilos da sua aplicação web.
</p>

<h2>
    Pré-requisitos
</h2>

<p>
    Antes de começar, certifique-se de que você tem o Node.js e o npm (Node Package Manager) instalados em sua máquina. Se não, você pode baixá-los e instalá-los do site oficial do Node.js.
</p>

<h2>
    Passo a Passo para Instalação
</h2>

<h3>
    Passo 1: Instalação do Node.js e npm
</h3>

<ul>
    <li>Baixe e instale a versão mais recente do Node.js do site oficial.</li>
    <li>Abra o terminal e execute node -v e npm -v para verificar a instalação.</li>
</ul>

<h2>
    Passo 2: Instalação do SASS
</h2>

<ul>
    <li>No terminal, execute o comando npm install -g sass para instalar o SASS globalmente.</li>
</ul>

<h2>
    Passo 3: Verificação da Instalação
</h2>

<ul>
    <li>Confirme a instalação executando sass --version no terminal.</li>
</ul>

<h2>Passo 4: Configuração do Projeto</h2>

<ul>
    <li>Crie um diretório para seus arquivos de estilo e inicie um novo projeto Node.js com npm init -y.</li>
</ul>

<h2>Passo 5: Estrutura de Diretórios</h2>

<p>Estruture seu projeto de forma organizada. Exemplo: </p>
<p>/MeuProjeto
  /src
    /scss
      estilo.scss
  /dist
    estilo.css
  index.html
  package.json</p>

  <h2>Passo 6: Compilação do SASS</h2>

  <ul>
      <li>No package.json, adicione um script para compilar o SASS:</li>
      <p>"scripts": {
      "compile-sass": "sass src/scss/estilo.scss dist/estilo.css"}</p>
        <li>Execute npm run compile-sass para compilar.</li>
  </ul>

<h2>
    Passo 7: Automatização com Watch
</h2>

<ul>
    <li>Adicione um script de watch no package.json:</li>
    "scripts": {
  "watch-sass": "sass --watch src/scss:dist"
}
    <li>Execute npm run watch-sass para iniciar a compilação automática.</li>
</ul>

<h2>Começando a Usar</h2>

<p>Com o SASS instalado e configurado, você está pronto para começar a escrever seus estilos de forma mais eficiente e poderosa. Use as funcionalidades avançadas do SASS para melhorar seu fluxo de trabalho e a qualidade do seu código CSS.</p>
<p>Para mais informações sobre como usar o SASS, consulte a documentação oficial.</p>

<h3>Maneira Alternativa</h3> 

<p>Uma outra maneira de configurar o SASS é seguir o Passo a Passo do vídeo a seguir: (https://youtu.be/YIEOpKYA9yc?si=KKa45uG5Xk1d9od2). </p>

## Passo a passo para o desenvolvimento do projeto
<p>OBS: A maneira escolhida para o desenvolvimento do projeto foi a alternativa, visto que o mesmo era de baixa complexidade.</p>
<ol>
    <li>
        Primeiramente fizemos o wireframe do projeto usando o Figma definindo coisas como cores, tipografias, espaçamentos e disposição dos elementos na tela.
        </br>
         <img alt="print-figma" src="https://github.com/MateusBorgesGuimaraes/scss-trab/assets/104425878/19b05387-60a8-4f54-98be-bc8ab4c5c0cb">
    </li>
    </br>
    <li>
        Na parte do código fizemos todo o HTML e instalamos a extensão Live Sass Compiler para o pré processamento do SASS, linkamos devidamente o css e ativamos a extensão com o Watch Sass, nesse momento, o pré processador já estava rodando.
        </br>
        <img alt="live-sass" src="https://github.com/MateusBorgesGuimaraes/scss-trab/assets/104425878/0fce9b4c-47ea-42d3-a2ac-58a5e2f50208">
    </li>
    </br>
    <li>
        Em seguida fizemos a utilização das variáveis SASS para definir elementos que se repetiam muito, esses sendo as tipografias, cores, pesos das fontes, e tamanhos.
        </br>
         <img alt="variaveis1" src="https://github.com/MateusBorgesGuimaraes/scss-trab/assets/104425878/edfe8fd6-c0f7-4d9f-9197-494d7d372036">
    </li>
    </br>
    <li>
        Durante o desenvolvimento percebemos um padrão que se repetia muito ao definir o estilo das tipografias, vimos então uma oportunidade de fazer o uso dos mixins para facilitar o desenvolvimento.
        </br>
        <img alt="variaveis2" src="https://github.com/MateusBorgesGuimaraes/scss-trab/assets/104425878/024b60f4-91a5-4bd1-8797-eaeb88d38f4f">
    </li>
    </br>
    <li>
        O aninhamento foi uma propriedade que foi de grande utilidade durante o desenvolvimento do projeto, a maneira que os elementos ficam agrupados ajuda muito no entendimento do código.
        </br>
        <img alt="classe-navegacao-scss" src="https://github.com/MateusBorgesGuimaraes/scss-trab/assets/104425878/3fcd3843-2bcd-4a5a-bb26-5f65039c5a8d">
    </li>
</ol>

<p>Essa foi a forma que usamos o SASS para desenvolevr o projeto.</p>
