# 💳 Glassmorphism Credit Card - Cartão Interativo 3D

Um cartão de crédito conceitual e elegante que utiliza a tendência de design Glassmorphism, combinada com uma interação de giro 3D realista.

## 🌟 Descrição

Este projeto apresenta um cartão de crédito simulado com duas faces (frente e verso). O design é construído sobre um fundo escuro com elementos orgânicos flutuantes, criando uma sensação de profundidade.

**Destaques do Componente:**
- **Estilo Glassmorphism:** O cartão possui um efeito de vidro fosco, alcançado através de `backdrop-filter: blur` e fundos semi-transparentes.
- **Interação 3D Flip:** Ao passar o mouse, o cartão gira 180 graus no eixo Y, revelando a parte traseira de forma fluida.
- **Detalhes Realistas:** Inclui elementos como o chip EMV, logo da bandeira (MasterCard), número do cartão com espaçamento, nome do titular, validade e a faixa magnética com campo de assinatura no verso.
- **Fundo Dinâmico:** Círculos em gradiente posicionados atrás do cartão reforçam o efeito de transparência do vidro.

## 🛠️ Funcionalidades Técnicas

- **Backdrop Filter:** Uso de `blur(25px)` para o efeito de transparência desfocada.
- **Transformações 3D:** Implementação de `preserve-3d`, `perspective` e `rotateY` para o giro.
- **Backface Visibility:** Gerenciamento da visibilidade das faces para garantir que apenas um lado seja visto por vez durante a rotação.
- **Layout Flexbox:** Organização precisa dos dados do cartão e alinhamento dos elementos internos.
- **Repetitive Gradients:** Uso de `repeating-linear-gradient` para criar a textura da área de assinatura.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica das faces do cartão.
- **CSS3:** Glassmorphism, animações 3D, seletores avançados e gradientes.
- **Google Fonts:** Tipografia Poppins para um visual moderno.

## 📂 Como Usar

1. Baixe os arquivos do projeto (incluindo `chip.png` e `logo.png`).
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Passe o mouse sobre o cartão para ver o efeito de giro.

## 👤 Autor

**Miguel Oliveira**
- [GitHub](https://github.com/migueLLIDO)
