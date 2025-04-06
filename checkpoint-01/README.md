# Projeto HTML + CSS — Traveller Page

Este projeto tem como objetivo praticar a criação de uma estrutura de página web com HTML e CSS, utilizando containers, alinhamentos, estilização de texto, imagens e links. A proposta é simular a criação de uma landing page com foco em organização visual e responsividade básica.

---

## 🎯 Objetivo

Construir uma página com base nos seguintes requisitos:

### 🧱 Estrutura do Container Principal

- **Largura:** 800px  
- **Margem superior/inferior:** 20px  
- **Margem lateral (auto):** Centraliza o conteúdo horizontalmente  
- **Padding:** 20px em todos os lados  
- **Alinhamento do texto:** Centralizado  

---

### 🧍‍♂️ Container Interno (Perfil)

Dentro do container principal:

- Largura: 800px  
- Margens: 20px (superior/inferior), auto (lateral)  

Contém:

- **Título principal com nome e RM**  
  - Fonte: 40px  
  - Cor: `#544C94`  
  - Margens: 20px acima e abaixo  
- **Imagem `banner.jpg`**  
  - Largura: 100%  
  - Cantos arredondados: 7px  
- **Parágrafo abaixo da imagem**  
  - Frase: *"Para baixar imagens como essa acesse Pexels."*  
  - A palavra **Pexels** é um link para [pexels.com](http://www.pexels.com), que abre em uma nova aba.

---

### 🔖 Subtítulo

- Fonte: 35px  
- Cor: `#751E63`  
- Margens: 20px (superior/inferior)

---

### 🖼️ Containers com Imagens

Três containers abaixo do subtítulo:

- **Largura:** 500px  
- **Margens:** 20px (superior/inferior), auto (lateral)  
- **Borda:** 2px sólida, cor `#515640`  
- **Arredondamento:** 7px  
- **Padding:** 20px  

Cada container contém:

- **Imagem:**  
  - `traveller1.jpg`, `traveller2.jpg`, `traveller3.jpg`  
- **Subtítulo:**  
  - Mesma formatação do subtítulo principal  
- **Parágrafo:**  
  - Margem superior de 20px e inferior de 40px  
  - Tamanho da fonte: 15px  
  - Conteúdo: texto fictício `lorem15` (15 palavras geradas com *Lorem Ipsum*)

---

## 🧪 Tecnologias Utilizadas

- HTML5
- CSS3

---

## 📁 Estrutura de Pastas

/projeto │
 ├── css/ 
 │ 
 └── estilos.css 
 ├── imagens/ 
 │ 
 ├── banner.jpg 
 │ 
 ├── traveller1.jpg 
 │ 
 ├── traveller2.jpg 
 │ 
 └── traveller3.jpg 
 ├── index.html 
 └── README.md