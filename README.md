# Back-end GoBarber

Projeto do Bootcamp GoStack. O back-end do GoBarber é responsável pela regra de negócio da aplicação e será consumida pelos clientes web e mobile, API agnóstica de tecnologia. 🧔

## Ferramentas

**TypeORM**: Tecnologia utilizada para comunicar-se com o banco de dados, além disso, a capacidade de criar migrations é essencial para a criação das tabelas do banco dando transparência as ações e evitando problemas futuros ou até mesmo voltar no tempo.

**Postgres**: Banco de dados escolhidos para utilizar na aplicação. Sendo assim, algumas informações da migrations do ORM são específicas para o Postgres.

**Token**: Foi utilizado o `jsonwebtoken` para gerir a capacidade de autenticação de usuários na aplicação e criar rotas autenticadas. Além disso, a criptografia de senha também com o `bcriptjs`

**Multer**: Utilizado para auxiliar no upload de arquivos. Onde há a importação das imagens dos perfis de usuários.

## Passo-a-passo para executar

1. `git clone <link do repositório>` | Para clonar o repositório
2. `yarn` | Para instalar as dependências do projeto
3. Com o banco de dados instalado, basta configurá-lo conforme o arquivo ormconfigexample.json
4. `yarn dev:server` | Para rodar o projeto
