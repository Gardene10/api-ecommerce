<div style="background-color:black; padding: 20px;">
  <h1 style="color:white; text-align:center;">🛍️ API E-Commerce</h1>
</div>

Bem-vindo à API E-Commerce! Este é um projeto que apresenta uma API para gerenciar operações de um sistema de comércio eletrônico, desenvolvido com Node.js e Express.js.

## Funcionalidades ✨

- Cadastro de produtos com detalhes, preços e categorias.
- Listagem de produtos disponíveis.
- Detalhes de cada produto, incluindo informações e avaliações.

## Tecnologias Utilizadas 🚀

- Node.js
- Express.js
- MongoDB (utilizando Mongoose)

## Instalação e Uso 🛠️

1. **Clone o repositório:**

   git clone https://github.com/Gardene10/api-ecommerce.git
   
Entre na pasta do projeto:

cd api-ecommerce

Instale as dependências:

npm install

Configure as variáveis de ambiente:

Crie um arquivo .env na raiz do projeto com as seguintes variáveis:

env

PORT=3000
MONGODB_URI=<sua_URL_do_MongoDB>

Inicie o servidor:

npm start

Acesse a API em: http://localhost:3000

Dockerização 🐳 (opcional)
Se você preferir, pode usar Docker para containerizar a aplicação:

Certifique-se de ter o Docker instalado.

No diretório do projeto, construa a imagem:

docker build -t api-ecommerce .

Execute o container:

docker run -p 3000:3000 -d api-ecommerce

Contribuição 💬

Contribuições são bem-vindas! Se você encontrar problemas ou tiver melhorias para sugerir, fique à vontade para abrir uma issue ou um pull request.

Desenvolvido por Gardene 👋
