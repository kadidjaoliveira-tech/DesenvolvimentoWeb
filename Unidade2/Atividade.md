# Atividade Prática — HTML Semântico e Acessibilidade 30/04

## Objetivo

Construir e corrigir uma página web aplicando:

- HTML semântico  
- Acessibilidade (WCAG / eMAG)  
- Estrutura correta para SEO  

# Parte 1 — Construção da Página

## 📝 Tarefa

Criar uma página HTML contendo:

- `<header>` com título e navegação  
- `<main>` com:
  - 1 `<article>`
  - 1 `<section>`
- `<aside>` com conteúdo complementar  
- `<footer>` com informações da aula  

## ⚠️ Requisitos obrigatórios

- Apenas **1 `<h1>` por página**
- Hierarquia correta de títulos (`h1 → h2 → h3`)
- Uso de `alt` em imagens
- Uso de `<label>` associado a inputs
- Navegação acessível por teclado (Tab)
- Contraste adequado de cores

# Parte 2 — Exercício de Correção (Debug)

## 💻 Código com erros

```html
<!DOCTYPE html>
<html>
<head>
    <title>Página</title>
</head>
<body>

<div>
    <h1>Título</h1>
    <h1>Outro título</h1>
</div>

<div>
    <div>
        <p>Conteúdo principal</p>
    </div>
</div>

<img src="imagem.jpg">

<form>
    Nome:
    <input type="text">
</form>

<a href="#">Clique aqui</a>

</body>
</html>
