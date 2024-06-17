# 🥟 PastelSoft

**PastelSoft** é um sistema desenvolvido para auxiliar o serviço de pastelarias, oferecendo uma solução completa para o gerenciamento de pedidos, controle de estoque, gestão de funcionários, controle de receitas e muito mais. O objetivo é otimizar a operação da pastelaria, proporcionando eficiência e organização.

## 🛠️ Tecnologias Utilizadas

### Backend
- **Linguagem**: Java
- **Framework**: Spring (Spring Boot)
- **API**: RESTful
- **Banco de Dados**: MySQL

### Frontend
- **Linguagem**: JavaScript
- **Framework/Biblioteca**: React

## ✨ Funcionalidades

### 📋 Gerenciamento de Pedidos
- **Adicionar Pedidos**: Facilidade para inserir novos pedidos, incluindo detalhes como itens, quantidade e especificações do cliente.
- **Atualizar Pedidos**: Capacidade de editar pedidos existentes para refletir alterações solicitadas pelos clientes.
- **Cancelar Pedidos**: Opção para cancelar pedidos, com atualização automática do estoque.
- **Histórico de Pedidos**: Acesso ao histórico completo de pedidos para análise e referência futura.

### 📦 Controle de Estoque
- **Adicionar Produtos**: Inserção de novos produtos no sistema, com detalhes como nome, preço e quantidade inicial.
- **Atualizar Estoque**: Atualização automática do estoque com base nos pedidos realizados.
- **Notificações de Estoque Baixo**: Alertas automáticos quando os níveis de estoque atingem um limite mínimo definido.

### 👥 Gestão de Funcionários
- **Cadastro de Funcionários**: Registro detalhado dos funcionários, incluindo informações de contato e funções desempenhadas.
- **Controle de Acesso**: Gerenciamento de permissões e níveis de acesso para diferentes tipos de usuários (administradores, atendentes, cozinheiros, etc.).
- **Relatórios de Desempenho**: Relatórios detalhados sobre o desempenho e atividades dos funcionários.

### 💰 Controle de Receitas
- **Registro de Vendas**: Registro automático de todas as vendas realizadas, com geração de relatórios financeiros.
- **Relatórios de Vendas**: Relatórios diários, semanais e mensais das vendas, incluindo produtos mais vendidos e horários de pico.
- **Análise de Desempenho**: Ferramentas analíticas para avaliar o desempenho financeiro da pastelaria.

## 🗂️ Estrutura do Projeto

### Backend
- **Controller**: Responsável por receber as requisições HTTP e encaminhá-las para os serviços apropriados.
- **Service**: Contém a lógica de negócios e interage com o repositório para acessar o banco de dados.
- **Repository**: Interface com o banco de dados MySQL, utilizando Spring Data JPA.

### Frontend
- **Componentes**: Componentes reutilizáveis do React para construir a interface do usuário.
- **Pages**: Páginas específicas para diferentes partes do sistema (ex.: página de pedidos, página de estoque).
- **Services**: Comunicação com a API RESTful para enviar e receber dados.

## 🚀 Como Executar o Projeto

### Pré-requisitos
- **Java 17+**
- **Maven**
- **Node.js**
- **MySQL**

### Backend
1. Clone o repositório:
    ```bash
    git clone https://github.com/caiohrmm/pastelsoft.git
    cd pastelsoft/backend
    ```
2. Configure o banco de dados MySQL no arquivo `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/pastelsoft
    spring.datasource.username=seu-usuario
    spring.datasource.password=sua-senha
    ```
3. Execute o projeto:
    ```bash
    mvn spring-boot:run
    ```

### Frontend
1. Navegue até o diretório do frontend:
    ```bash
    cd pastelsoft/frontend
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Execute o projeto:
    ```bash
    npm start
    ```

## 🤝 Contribuição

1. Faça um fork do projeto.
2. Crie uma branch para a sua feature (`git checkout -b feature/MinhaFeature`).
3. Commit suas mudanças (`git commit -am 'Adicionei MinhaFeature'`).
4. Faça o push para a branch (`git push origin feature/MinhaFeature`).
5. Abra um Pull Request.

## 📄 Licença

Este projeto está licenciado sob a licença MIT.

