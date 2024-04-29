# Agenda de Contatos

## Descrição do Projeto
Este projeto consiste em uma aplicação web para gerenciar uma agenda de contatos. Usuários podem adicionar, editar e excluir contatos, além de visualizá-los em uma lista organizada. O projeto é desenvolvido utilizando Django para o backend, com interfaces de usuário criadas em HTML e estilizadas com CSS.

## Tecnologias Utilizadas
- **Django**: Framework backend para construir a aplicação.
- **HTML**: Usado para estruturar o conteúdo das páginas.
- **CSS**: Aplicado para estilizar e formatar a apresentação das páginas.

## Funcionalidades
- **Cadastro de Contatos**: Adicionar novos contatos à agenda.
- **Edição de Contatos**: Atualizar informações de contatos existentes.
- **Exclusão de Contatos**: Remover contatos da agenda.
- **Visualização de Contatos**: Listar todos os contatos cadastrados.

## Instalação e Configuração
Para configurar e executar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   cd agenda-contatos

2. Navegue até o diretório do projeto:
   ```bash
   git clone https://github.com/seu-usuario/agenda-contatos.git
   
3. Crie um ambiente virtual:
   ```bash
   python -m venv venv
   
4. Ative o ambiente virtual:
   ```bash
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`

5. Instale as dependências:
   ```bash
   pip install -r requirements.txt

6. Realize as migrações do banco de dados:
   ```bash
   python manage.py migrate

7. Inicie o servidor de desenvolvimento:
   ```bash
   python manage.py runserver



