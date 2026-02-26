# Plant Based - Animated Button

Este repositório contém um componente de UI moderno: um botão estilizado com o tema "Plant Based", que utiliza **HTML5**, **CSS3** e **SVG** para criar uma animação complexa e interativa ao passar o mouse (hover).

---

## 🌟 Funcionalidades

O projeto destaca o uso avançado de animações CSS e manipulação de elementos vetoriais:

- **SVG Inline**: Uso de vetores diretamente no HTML para garantir performance e nitidez.
- **Keyframes Animation**: Cada folha (ícone) possui sua própria animação de "balanço" (`swing`) ao aparecer.
- **Efeito Hover Profundo**: Ao passar o mouse, o botão altera sua forma e faz brotar cinco tipos diferentes de folhas em posições e tamanhos variados.
- **Design Moderno**: Uso de `box-shadow` interno e externo para criar profundidade (Neumorfismo leve).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação dos elementos e containers dos ícones.
* **CSS3**: 
    * Posicionamento absoluto para controle dos ícones.
    * `transition` para suavidade nos movimentos.
    * `@keyframes` para as animações de entrada das folhas.
    * `z-index` para controlar a sobreposição atrás do botão.

---

## 📂 Estrutura de Arquivos

O projeto é composto por dois arquivos principais (conforme o código):

- **index.html**: Contém o botão e os 5 caminhos (paths) de SVG que formam a ilustração.
- **style.css**: Contém toda a lógica visual, cores das folhas (`#7B9B3A`, `#556729`, `#3C4819`) e os efeitos de animação.

---

## 🚀 Como Visualizar

1. Salve o código HTML em um arquivo chamado `index.html`.
2. Salve o código CSS em um arquivo chamado `style.css` na mesma pasta.
3. Abra o arquivo `index.html` em qualquer navegador moderno.

---

## 📊 Comportamento da Animação

| Ícone | Posição Final (Hover) | Tamanho | Delay de Animação |
| :--- | :--- | :--- | :--- |
| Folha 1 | Centro Superior | 50px | 0.45s |
| Folha 2 | Direita Superior | 75px | 0.45s |
| Folha 3 | Esquerda Inferior | 60px | 0.45s |
| Folha 4 | Extrema Esquerda | 85px | 0.45s |
| Folha 5 | Extrema Direita | 85px | 0.45s |

---
Projeto desenvolvido para estudos de animação e interatividade em interfaces web.
