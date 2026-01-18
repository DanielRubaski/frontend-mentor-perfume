# 🌸 Projeto Perfume - Página de Produto

Um site elegante para exibir e vender um perfume de luxo. O projeto foi desenvolvido com **HTML**, **CSS** responsivo e segue as melhores práticas de design moderno.

---

## 📱 O que é o projeto?

Este é um **produto digital** que simula uma página de e-commerce para um perfume. Ele apresenta:

- **Imagem do produto** que se adapta a diferentes tamanhos de tela
- **Informações do perfume** (nome, descrição, marca)
- **Preço com desconto** (mostra valor antigo e novo)
- **Botão de compra** com ícone de carrinho

---

## 🎯 Características principais

### ✨ Design Responsivo
- **Celular (até 767px)**: Layout em coluna (imagem em cima, informações embaixo)
- **Desktop (768px+)**: Layout em linha (imagem à esquerda, informações à direita)

### 🎨 Estilo Visual
- Cores profissionais e elegantes
- Fontes modernas: *Montserrat* (texto comum) e *Fraunces* (títulos)
- Efeito de hover no botão (muda de cor ao passar o mouse)
- Design limpo e minimalista

### 📐 Estrutura do Layout
```
┌─────────────────────┐
│    IMAGEM           │
│   DO PRODUTO        │  (Mobile)
├─────────────────────┤
│ Nome do Perfume     │
│ Descrição           │
│ Preço: R$ 150       │
│ [Botão de Compra]   │
└─────────────────────┘
```

---

## 📁 Estrutura de Arquivos

```
frontend-mentor-perfume/
│
├── index.html              # Página principal (HTML)
├── README.md              # Este arquivo
│
└── src/                   # Pasta com recursos
    ├── css/
    │   ├── reset.css      # CSS reset (remove estilos padrão)
    │   └── style.css      # Estilos personalizados
    │
    └── image/
        ├── desktop.jpg    # Imagem para telas grandes
        ├── mobile.jpg     # Imagem para celular
        ├── icon-cart.svg  # Ícone do carrinho
        └── favicon-32x32.png  # Ícone da aba
```

---

## 🏗️ Como funciona o código?

### **index.html** - O esqueleto da página
- Define a estrutura HTML
- Importa os arquivos CSS
- Cria um artigo com:
  - `<picture>`: Imagem que muda conforme o tamanho da tela
  - `<article class="produto">`: Container principal
  - `<div class="informativo">`: Seção com informações e botão

### **reset.css** - Limpeza do CSS
Remove estilos padrão do navegador para começar "do zero":
- Remove margens e paddings
- Remove estilos de listas, links e botões
- Garante que imagens sejam responsivas

### **style.css** - Beleza e layout
Adiciona o design final:
- **Variáveis de cor** (`:root`): Fácil manutenção de cores
- **Flexbox**: Para alinhar elementos perfeitamente
- **Media Query**: Transforma o layout para telas maiores
- **Transições**: Efeitos suaves no botão

---

## 🎬 Cores Utilizadas

| Cor | Uso |
|-----|-----|
| 🟫 `#F3EAE3` | Fundo da página |
| ⚪ `#FFFFFF` | Fundo do card |
| 🟩 `#3C8067` | Botão (cor principal) |
| 🟩 `#1C3A2E` | Botão ao passar mouse |
| ⬛ `#1C232B` | Texto |

---

---

## 🚀 Tecnologias Usadas

- **HTML5**: Estrutura semântica
- **CSS3**: Layout com Flexbox e Media Queries
- **Fontes Google Fonts**: Tipografia moderna
- **SVG**: Ícone vetorial (não pixela)

---

## 📱 Responsividade

O site funciona perfeitamente em:
- ✅ Celulares (320px - 767px)
- ✅ Tablets (768px - 1024px)
- ✅ Desktops (1025px+)

---

## 🎓 Aprenda com este projeto

Este é um ótimo exemplo para aprender:

✔️ **HTML semântico** com `<picture>` para imagens responsivas  
✔️ **Variáveis CSS** (`:root`) para fácil manutenção  
✔️ **Flexbox** para alinhamento perfeito  
✔️ **Media Queries** para design responsivo  
✔️ **Transições CSS** para interatividade  
✔️ **Favicon e favicon.ico** para identidade visual  

---

## 📝 Detalhes do Produto

- **Nome**: Gabrielle Essence Eau De Parfum
- **Marca**: CHANEL
- **Tipo**: Eau de Parfum (concentração de fragrância)
- **Preço Original**: $169.99
- **Preço em Promoção**: $149.99
- **Descrição**: Uma fragrância floral, solar e voluptuosa criada por Olivier Polge

---

## 🔗 Créditos

- Design baseado no desafio **Frontend Mentor**
- Imagens e ícones inclusos no projeto
- Fontes do Google Fonts: Montserrat e Fraunces