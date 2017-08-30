# Website Performance Optimization portfolio project

Para executar o projeto, clique [aqui](https://jeancwill.github.io/frontend-nanodegree-mobile-portfolio/index.html) para ve-lo hospedado no GitHub Pages, ou realize o download do diretório e abra o arquivo index.html.

### Otimização da pontuação no PageSpeed Insights
  - Movido os arquivos externos de CSS para o cabeçalho da página index.html
  - Alterados para assíncronos os links para javascript no cabeçalho
  - Otimizado as imagens utilizando o grunt
  - Configurado o carregamento da fonte para evitar o bloqueio de renderização
 
PageSpeed Insights Score Mobile: **93/100**
PageSpeed Insights Score Desktop: **92/100**

### Otimização de quadros por segundo na página pizza.html
  - Movida a variável pizzasDiv para fora do loop
  - Novas variáveis randPizzas e numPizzas para simplificar o loop
  - Excluídas as variáveis: ```oldwidth```, ```windowwidth```, ```oldsize```, ```newsize```, e ```dx```
  - Atualizado os valores de largura na função de troca de porcentagem
  - Movido o código ```(documento.body.scrollTop / 1250)``` para uma variável fora do loop
  - Alterado de 200 para 30 pizzas carregadas
