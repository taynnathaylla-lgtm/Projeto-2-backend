
# Sistema de Biblioteca — Projeto 2

Projeto da disciplina Construção de Backend (IESB).

O sistema gerencia autores, livros, membros e empréstimos, aplicando regras de negócio desenvolvidas em Django.

## Funcionalidades

- Cadastro de Autores, Livros e Membros pelo Django Admin
- Empréstimo de livros com prazo de 14 dias
- Controle de cópias disponíveis
- Devolução de livros com reposição de cópias
- Indicação de empréstimos atrasados
- Relatório de livros mais emprestados

## Como rodar

1. Criar o ambiente virtual:

```bash
python -m venv venv
````

2. Ativar o ambiente virtual.

No Windows:

```powershell
venv\Scripts\activate
```

3. Instalar as dependências:

```bash
pip install -r requirements.txt
```

4. Executar as migrações:

```bash
python manage.py migrate
```

5. Criar um superusuário:

```bash
python manage.py createsuperuser
```

6. Iniciar o servidor:

```bash
python manage.py runserver
```

Depois, acesse:

http://127.0.0.1:8000/


## Prints

Inclua nesta seção prints das principais telas do sistema:

- Django Admin
- Listagem de livros
- Tela de empréstimos
- Tela de devolução
- Relatório de livros mais emprestados

## Testes

Para executar os testes automatizados do projeto:


python manage.py test

## Autor
Taynna Thaylla Souza Vitorio — IESB 2026
