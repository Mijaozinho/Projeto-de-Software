# Projeto-de-Software

## SIAD - Sistema de Inscrição e Acompanhamento Desportivo da UEPG

Projeto de Software - Sistema de Inscrições e Acompanhamento Desportivo (SIAD)

Este é um projeto Django produzido para a matéria de Projeto de Software do curso de Engenharia de Computação, para gerenciar eventos esportivos, incluindo modalidades, divisões, grupos e atletas. O projeto também permite a administração de notícias e editais relacionados aos eventos.

## Funcionalidades

- **Gestão de Eventos**: Criação e administração de eventos esportivos.
- **Gestão de Grupos e Modalidades**: Adição e exclusão de grupos e modalidades para cada evento.
- **Gestão de Divisões**: Adição e exclusão de divisões para cada modalidade.
- **Notícias**: Adicione e visualize notícias relacionadas aos eventos.
- **Editais**: Upload e visualização de editais para cada evento.
- **Sistema de Login**: Autenticação e autorização para diferentes tipos de usuários (administradores e representantes esportivos).

## Tecnologias

- **Django**: Framework web para o desenvolvimento do projeto.
- **SQLite**: Banco de dados padrão para desenvolvimento.

## Instalação

### Requisitos

- Python 3.x
- pip (gerenciador de pacotes do Python)

### Passos para Instalação

1. Clone o Repositório

   ```bash
   git clone https://github.com/saskuati-dev/projeto.git
   cd SIAD
   
2. Instale as Dependências

   ```bash
   pip install -r requirements.txt
   
3. Crie as configurações do Banco de Dados
   ```bash
   python manage.py makemigrations
   
4. Atualize o Banco de Dados

   ```bash
   python manage.py migrate
   
5. Configure o Banco de Dados

   ```bash
   python manage.py migrate
   
6. Inicie o Servidor

   ```bash
   python manage.py runserver

