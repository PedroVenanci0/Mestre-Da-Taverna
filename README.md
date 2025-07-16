# 🧙‍♂️ O Mestre da Taverna (Chat com IA para RPG)

> **Sugestão:** Tire um print da sua aplicação em funcionamento e substitua o placeholder acima.

---

## 👋 Bem-vindo, aventureiro!

Este projeto é uma **interface de chat imersiva** que simula uma conversa com um **Mestre de Jogo** de RPG, alimentado pela poderosa **API do Google Gemini**.  
A aplicação foi desenhada para auxiliar **jogadores e mestres de RPG de mesa**, oferecendo uma ferramenta criativa para:

- Gerar ideias  
- Descrever cenários  
- Interpretar regras  
- Rolar dados 🎲

---

## 📜 Conceito

A ideia central é criar um ambiente com **temática de fantasia**, onde o usuário pode interagir com uma IA configurada para atuar como um **Mestre de RPG sábio e criativo**.  
A interface, que remete a uma **taverna antiga**, busca proporcionar uma **experiência imersiva** para os fãs do gênero.

---

## ✨ Funcionalidades Principais

O **Mestre da Taverna** vem equipado com várias ferramentas para enriquecer sua campanha:

### 🎭 Chat com IA Personalizada  
Converse com o "Mestre" (Google Gemini), que possui uma **persona pré-definida** para responder de forma criativa e temática, como um verdadeiro mestre de RPG.

### 🎲 Rolador de Dados Visual  
Envie comandos no chat no formato padrão de RPG (ex: `1d20`, `2d6+3`, `1d100`) para ativar uma **bandeja de rolagem animada**, que mostra o resultado de cada dado individualmente.

### 🖼️ Interpretação de Imagens  
Envie uma imagem (como mapa, ficha de personagem ou ilustração) e peça ao Mestre para descrevê-la, criar uma história a partir dela ou extrair informações.

### 🧵 Interface Temática e Responsiva  
A interface utiliza **TailwindCSS** e **CSS customizado** para criar um visual que remete a uma **taverna de fantasia**, adaptando-se a diferentes tamanhos de tela.

### 🎨 Estilo Imersivo  
Fontes, cores e elementos visuais, como a **barra de rolagem** e as **bolhas de mensagem**, foram cuidadosamente escolhidos para manter a imersão.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura semântica da página  
- **CSS3** – Estilização, animações com `@keyframes` e design responsivo  
- **TailwindCSS** – Framework CSS para estilização rápida e moderna  
- **JavaScript (Vanilla)** – Manipulação do DOM, lógica da aplicação e interações  
- **Google Gemini API** – O cérebro por trás do "Mestre", responsável por gerar as respostas criativas e analisar imagens

---

## 🚀 Como Executar o Projeto

Para ter o **Mestre da Taverna** funcionando em sua máquina local, siga estes simples passos:

### 1. Clone o Repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```
Substitua seu-usuario/nome-do-repositorio pelo URL do seu projeto.

## 2. Abra o script.js

Localize o arquivo script.js na pasta do projeto.

## 3. Insira sua Chave da API

Dentro do script.js, encontre a seguinte constante e substitua o valor existente pela sua própria chave de API do Google Gemini:
```
const API_KEY = "SUA_CHAVE_DA_API_VEM_AQUI"; // COLOQUE AQUI SUA CHAVE DE API
```

⚠️ Atenção: É crucial obter sua própria chave na plataforma do Google AI Studio para que a aplicação funcione corretamente.

## 4. Abra o index.html

Abra o arquivo index.html em seu navegador de preferência.
A maneira mais fácil é usar uma extensão como o Live Server no Visual Studio Code, para evitar problemas com CORS ao fazer requisições para a API.

---

### ✒️ Autor
Criado por Pedro.
Que seus dados rolem alto! 🎲✨
