# project-albuns
This project is about evaluating your favorite albums and having an average and knowing what your favorite is, which can be used for music platforms so people know their musical taste!

# Minha Coleção — Álbuns (Django + React)

Sistema web fullstack desenvolvido para o projeto avaliativo M2 (Parte 1) da disciplina de Lógica e Programação

## Integrantes do Grupo
> **ARTHUR CAMPOS BATISTA** — RGM: 11261104789 {github - https://github.com/nakazaca}
> **MIGUEL HENRIQUE DA SILVA DAMIÃO** — RGM: 11261102921 {github - https://github.com/Damiz7}
> **RAFAEL ENZO XAVIER DE AGUIAR** — RGM: 11261105220 {github - https://github.com/rafonfis}

## Variante do Projeto
> **Tema:** Álbuns
> **App Django:** 'albuns'
> **Model:** "Album" ('titulo', 'artista', 'ano', 'avaliacao')

## Como rodar o Backend (Django)
1. Acesse a pasta raiz do projeto ('colecao'):
   ```bash
   >cd colecao
   ```
2. Ative o ambiente virtual (se estiver usando) e instale as dependências:
   ```bash
   >pip install django
   >pip install django-cors-headers
   ```
3. Execute as migrações e inicie o servidor:
   ```bash
   >python manage.py migrate
   >python manage.py runserver
   ```
   O backend estará disponível em 'http://127.0.0.1:8000/api/albuns/'.

## Como rodar o Frontend (React + Vite)
1. Em outro terminal, acesse a pasta `frontend`:
   ```bash
   >cd colecao/frontend
   ```
2. Instale os pacotes e inicie a aplicação:
   ```bash
   >npm install
   >npm run dev
   ```
   O frontend estará disponível em 'http://localhost:5173'.
