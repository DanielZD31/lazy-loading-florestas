# 🌲 Lazy Loading: Florestas pelo Mundo

Este projeto é um exemplo simples de **Lazy Loading de imagens com JavaScript puro**. Ele carrega imagens de florestas em resolução reduzida e, à medida que o usuário navega pela página, as imagens são substituídas por versões em alta resolução.

## 📷 Pré-visualização

![preview](https://images.unsplash.com/photo-1470115636492-6d2b56f9146d?w=600)

---

## 🚀 Funcionalidades

- Lazy loading de imagens com Intersection Observer
- Substituição dinâmica da resolução das imagens ao entrarem na viewport
- Totalmente sem bibliotecas externas

---

## 🧠 Como funciona?

As imagens são carregadas inicialmente com uma URL contendo uma resolução reduzida (`w=10`). Quando o usuário rola e a imagem entra na área visível da tela (viewport), o JavaScript detecta isso e altera o `src` da imagem para uma versão de resolução maior (`w=1000`), criando o efeito de Lazy Load.


## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6)
- Intersection Observer API
