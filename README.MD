# Skills de Revisão de Código

## `comment-and-explain-code`

* Lê um arquivo de código.
* Adiciona comentários curtos e úteis para explicar trechos mais difíceis.
* Cria um arquivo Markdown separado com a explicação do código.

## `review-code-on-save`

* Revisa um arquivo de código depois de salvar ou alterar.
* Procura erros de sintaxe, nomes errados, imports faltando e problemas óbvios de lógica.
* Mostra os achados com o máximo de clareza possível.

## Como testar

### 1. Baixar as Skills
* No codex rode `@skill-installer`com o caminho das pastas das skills

### 1. Testar `comment-and-explain-code`

* No codex Use a skill `@Comment and Explain Code` com o caminho do arquivo `rightfile.html`
* Confira se os comentários ficaram úteis e se o arquivo `.md` resume bem o conteúdo.

### 2. Testar `review-code`

* No codex Use a skill `@Review Code` com o arquivo `wrongfile.html`.
* Peça para a skill revisar o arquivo e apontar os problemas.
* Confira se ela encontra erros reais, como:

  * loop incorreto;
  * divisão por zero;
  * acesso a elemento inexistente;
  * acesso inválido ao array;
  * problemas de lógica simples.
