# Estados

## **Empty state**

* [https://dribbble.com/search?q=empty+state](https://dribbble.com/search?q=empty+state)

### Quando?

* Quando não tem nada pra exibir pro usuário.
* Geralmente no primeiro cadastro, ou quando o usuário apaga todos os dados as listagens são vazias.

### O que fazer?

* Mensagem com ilustração/animação (ou não)
* Geralmente para cada componente:
  * listagens, tabelas, gráficos, sidebars, etc...

### Exemplos

* [https://dribbble.com/shots?tag=empty%20state](https://dribbble.com/shots?tag=empty%20state)
* [https://www.sketchappsources.com/free-source/4028-empty-states-icons-sketch-freebie-resource.html](https://www.sketchappsources.com/free-source/4028-empty-states-icons-sketch-freebie-resource.html)
* [https://www.sketchappsources.com/free-source/2319-empty-state-placeholders-sketch-freebie-resource.html](https://www.sketchappsources.com/free-source/2319-empty-state-placeholders-sketch-freebie-resource.html)

## **Loading state**

### Quando?

* Sempre que tiver alguma ação do usuário;

### O que fazer?

* Pode-se exibir algum conteúdo "fake" (placeholder)
* Pode-se exibir **ícone** de "loading" ou **palavra** "Carregando..."
* **Bloquear** ações do usuário em botões e links que podem acarretar em múltiplas requisições.

### Exemplos:

* "Calma, ainda estamos processando sua requisição..."
* "Aguarde, a sua conexão está um pouco lenta..."
* [https://www.codepicky.com/content-placeholders/](https://www.codepicky.com/content-placeholders/)
* [https://dribbble.com/shots?tag=loading%20state](https://dribbble.com/shots?tag=loading%20state)
* [https://dribbble.com/shots?tag=loading](https://dribbble.com/shots?tag=loading)

## Error/Failed state

### Quando?

* Geralmente quando aconteceu algum erro com a requisição
* Algum dado da API voltou vazio
* Não foi possível enviar/processar a solicitação

### O que fazer?

* Mensagem clara e objetiva do que aconteceu com aquela ação.
* Ilustração com animação (opcional)

### Exemplos:

## **Success state**

### Quando?

* Geralmente depois do "**_loading state_**" precisamos exibir algum status para o usuário, ou de erro ou de sucesso.

### O que fazer?

* Mensagem com ícone de check (✔️)
* Mensagem precisa ser visível e bem clara, ir direto ao ponto sem rodeios.
* Em alguns casos ilustração com animação (opcional)

### Exemplos:

* [https://dribbble.com/shots?tag=success](https://dribbble.com/shots?tag=success)

## **Form states (buttons and inputs)**

### Quando?

* As interações visuais nos elementos de um formulário também são importantes para o usuário.
* Disabled
  * botão e inputs desativado para alguma ação do usuário, geralmente usam com opacidade de 0.6 (60%) e/ou cinza.
* Hover
  * estado quando o usuário passa o mouse sobre o botão ou input.
* Focus (tab)
  * destaca o botão/input que está em foco (usando tab ou mouse), importante deixar bem destacado por questão de acessibilidade.
  * geralmente para input usa-se outline/border/shadow para destacar a borda do input.
  * para geralmente botões usa-se a mesma cor do fundo mais escura (5% ou 10%).
* Selected
* Activated
* Pressed
  * Botões selecionados, ativados e pressionados geralmente tem o mesmo destaque do **Focus.**
  * Esses estados não são usados para inputs.
* Dragged
  * Geralmente é usado esse status para quando o usuário arrastar algo pra cima do botão/input ou quando arrasta o próprio botão/input.

### Exemplos:

* [https://semantic-ui.com/elements/input.html#focus](https://semantic-ui.com/elements/input.html#focus)
* [https://material.io/design/interaction/states.html](https://material.io/design/interaction/states.html)
* [https://cloudfour.com/thinks/designing-button-states/](https://cloudfour.com/thinks/designing-button-states/)
