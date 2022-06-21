HTML (Hypertext Markup Language)
É uma linguagem no seu jeito de escrever, tem semântica, tem sintaxe

### COMENTÁRIOS

Usado para comentar no meio do código sem interferir no código.

```bash
<!- - comentário - ->
```

### TAGS

- Abertura e fechamento
  < > </ >

###

### ATRIBUTOS GLOBAIS

- **Class**: Utilizada para classifica, aplicar estilos (styles) no CSS e também usada para acessar no JavaScript. E também pode ser usada repetidamente no código;
  ```bash
  <div class=”nome-da-classe ”> </div>
  ```
- **Hidden**: Esconde a tag;
- **id**: pode ser usado um único por página/tag;
- **Style**: posso estilizar minha página dentro do html sem precisar criar um outro arquivo chamado CSS;
- **Tabindex**: Usado para enumerar as tags para quando o usuário não conseguir/tiver uma mouse, ele vai poder navegar através da teclas tab do teclado;
- **Title**: Usado para definir um título para a tag;

### ANATÔMIA DO DOCUMENTO

```bash
<!DOCTYPE *html*>

<html *lang*="pt">

	<head>

		<!-- configurações para o documento (Cabeça)-->

		<meta *charset*="UTF-8" />

		<meta *http-equiv*="X-UA-Compatible" *content*="IE=edge" />

		<meta *name*="viewport" *content*="width=device-width, initial-scale=1.0" />

		<title>Document</title>

	</head>

	<body>

		<!--É o que o usuário da página ira ver/receber (Corpo)-->

	</body>

</html>
```

### LISTAS

- Ordenada
  Segue uma ordem numérica: 1,2,3,4,5,6,7,8,9…
  ```bash
  <ol>
  	<li>3 folhas de couve</li>
  	<li>1 laranja</li>
  	<li>1 pedacinho de gengibre</li>
  	<li>300ml de água</li>
  	<li>Adoçante a gosto</li>
  	<li>Gelo a gosto</li>
  </ol>
  ```
- Não Ordenada
  Não segue uma ordem numérica, segue como lista.
  ```bash
  <ul>
  	<li>3 folhas de couve</li>
  	<li>1 laranja</li>
  	<li>1 pedacinho de gengibre</li>
  	<li>300ml de água</li>
  	<li>Adoçante a gosto</li>
  	<li>Gelo a gosto</li>
  </ul>
  ```
