## Gerenciamento de Tarefas 🚀

Este projeto consiste em uma aplicação Full Stack completa com o objetivo de auxiliar na gestão de atividades e tarefas.

### Tecnologias Utilizadas 📊

#### Backend
- **NodeJS**
- **Express**

#### Frontend
- **HTML**
- **CSS**
- **JavaScript**

#### Banco de Dados
- **MySQL**

### Como Usar 🛠️

#### 1. Clonar ou Baixar o Repositório
Para clonar o repositório, utilize o seguinte comando no terminal:

```bash
$ git clone https://github.com/GabyXavierr/My-Tasks.git
```

#### 2. Criar o Banco de Dados
Acesse o terminal do MySQL e execute o comando abaixo para criar o banco de dados:

```sql
CREATE DATABASE tasks;
```

#### 3. Criar a Tabela "tasks"
Após criar o banco de dados, crie a tabela "tasks" com os seguintes campos:

```sql
CREATE TABLE tasks (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(45) NOT NULL,
    status VARCHAR(45) NOT NULL,
    created_at VARCHAR(45) NOT NULL
);
```

#### 4. Configurar Variáveis de Ambiente
Na raiz do projeto, localize o arquivo `.env.example`. Renomeie este arquivo para `.env` e preencha os campos com as informações correspondentes ao seu banco de dados:

```env
PORT= [Porta onde o servidor irá rodar]
MYSQL_HOST= [Host da máquina, por padrão 'localhost']
MYSQL_USER= [Seu usuário, por padrão 'root']
MYSQL_PASSWORD= [A senha configurada ao instalar o MySQL]
MYSQL_DB= [Nome do banco de dados criado anteriormente]
```

#### 5. Instalar Dependências
Abra um terminal dentro da pasta "backend" e execute o seguinte comando para instalar as dependências:

```bash
$ npm install
```

#### 6. Iniciar o Servidor
Ainda dentro da pasta "backend", execute o seguinte comando para iniciar o servidor:

```bash
$ npm start
```

#### 7. Abrir o Frontend
Abra manualmente o arquivo `index.html` no seu navegador.

### Observações Importantes ⚠️

- Certifique-se de que o MySQL está instalado e configurado corretamente em sua máquina.
- Verifique se as configurações no arquivo `.env` estão corretas.
- Para testar funcionalidades adicionais, você pode ajustar o frontend e backend conforme as suas necessidades.

### Melhorias Futuras 💡

- Implementar autenticação de usuários.
- Melhorar a interface do usuário.
- Adicionar a funcionalidade de filtros e buscas nas tarefas.
- Integração com APIs externas.

