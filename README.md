# Projeto Calculadora

Uma calculadora funcional e estilizada desenvolvida com foco em manipulação de layouts complexos através de CSS Grid.

![Preview da Calculadora](./imagens/Captura de tela_13-4-2026_215033_127.0.0.1.jpeg)

# Sobre o Projeto
Este projeto foi criado para praticar a estruturação de interfaces de usuário que exigem alinhamentos precisos. A calculadora possui um visor digital e um teclado numérico completo, organizado de forma responsiva.

# Tecnologias Utilizadas
HTML5: Estruturação dos botões e do visor.
CSS3:CSS Grid (Areas):** Utilizado para organizar os botões, incluindo o botão "0" que ocupa duas colunas e o botão "+" que ocupa duas linhas.
    Flexbox: Para centralizar a calculadora na tela.
    Gradients: Uso de `linear-gradient` para o fundo da página e da calculadora.
    Box Shadow: Efeito de profundidade para dar um aspecto realista ao dispositivo.

# Detalhes do Layout
O teclado foi construído utilizando áreas nomeadas no CSS, o que permite um controle total da posição de cada tecla:
- O botão **0** usa `grid-column: span 2` para ocupar mais espaço.
- O botão **+** (Adicionar) foi posicionado para ocupar um espaço vertical maior, simulando calculadoras reais.
- Estilização com bordas `outset` e `inset` para criar o efeito de botões físicos.

# Como abrir o projeto
1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em seu navegador.

---

## Autor
Leandro Falcão - https://github.com/Fxlcao 
