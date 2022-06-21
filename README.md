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

### CITAÇÕES

- **blockquote** — para uma citação que você queira deixar maior, tendo uma estilização mais diferente.

```bash
<blockquote cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
    O <strong>Elemento HTML <code>&lt;blockquote&gt;</code> </strong> (ou <em>HTML Block
    Quotation Element</em>) indica que um texto externo foi citado.
</blockquote>
```

- **cite** — atributo usado para citar a url.

```bash
<p>De acordo com <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
    <cite>página MDN blockquote</cite></a>:
</p>
```

- **q** — citação curtas com aspas (_<q></q>_)
  _<cite></cite>_ — tag usada para colocar o citar link direto no texto.
  ```bash
  <p>O elemento quote — <code>&lt;q&gt;</code> — é <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">usado para citações curtas que não precisam de parágrafos ou quebras de linha.</q> -- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
  <cite>MDN q page</cite></a>.</p>
  ```

### ABREVIAÇÕES

- **abbr**

```bash
**<p>Usamos <abbr title="Hypertext Markup Language">HTML</abbr>  para estruturar nossos documentos da web.</p>**
```

### DETALHES DE CONTATO

A tag usada para apenas colocar detalhes de contato é a tag _<address></address>_, não endereço em si, mas por exemplo o autor da página.

```bash
<address>
    <p>Mayk Brito <br>
    <strong>Campo Grande, MS</strong>
    </p>
</address
```

### LISTA DE DESCRIÇÃO

- **dl** — tag para lista de descrições (_<dl></dl>_);
- **dt** — tag para o termo da descrição (_<dt></dt>_);
- **dd** — tag para descrição (_<dd></dd>_).

```bash
<dl>
    <dt>Hypertext</dt>
    <dd>É um hiper texto com possibilidades...</dd>

    <dt>Markup</dt>
    <dd>Marcação do texto</dd>

    <dt>Languague</dt>
    <dd>Linguagem com sua semântica e sintaxe....</dd>
</dl>
```

### REPRESENTAÇÃO DE CÓDIGO

- **code** — muda a cor do conteúdo para representar código (_<code></code>_).
- **pre** — tag para criar um bloco de código, mantém os espaços em branco (_<pre></pre>_).

```bash
<pre>
    <code>
        &lt;
    </code>
</pre>
```

### ELEMENTOS GENÉRIOCOS

- **div** — tag usada para agrupar conteúdo (<div></div>).
- **span** — tag usada para agrupar texto, em uma ideia mais de linha (<span></span>).

```bash
<div class="cart">
    <span>Camiseta</span>
    <span>r$ 99,00</span>
</div>
```
