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

### ÂNCORA

São os famosos _hyperlinks_, e a tag usada para se criar um é a **_<a href=" ></a>_**, responsável por ligar várias páginas.

Há também o atributo de _download_, que é **_download=""_**, usado junto do _href=""_,por exemplo, se você colocar o link de uma imagem no _href=""_ com o atributo de download, a imagem será baixada ao invés de irmos até a página e se colocarmos um valor no atributo de download, ele irá dizer como você vai salvar o arquivo.

Por fim temos o atributo **_target=""_**, que irá dizer qual o alvo do nosso disparo, ou seja, se não tivermos o _target_, quando clicarmos no link, ele vai pegar o mesmo alvo, a mesma página e apenas vai trocar o conteúdo, mas se usarmos o atributo, por exemplo **_target="\_blank"_**, ele vai abrir uma página com o conteúdo.

### DIRETÓRIOS

- Para sair de um diretório colocamos **_../_** ,ele sairá do diretório, semelhante a sair de uma caixa que está dentro de outro.

```bash
<a href="hyperlinks.html">arquivo na pasta anterior</a>
<br>
<a href="./urls-caminhos.html">arquivo no diretório raiz</a>
<br>
<a href="urls-caminhos.html">arquivo na mesma pasta</a>
<br>
<a href="outros/conteudo-a-element.html">arquivo na pasta outros, que está na pasta anterior</a>
```

### TABELAS

- Prós
  - Visualização de dados via linhas e colunas.
  - Boa acessibilidade para leitura dos dados
- Contras
  - Pouco flexível
  - Precisa de estilização para melhor visualização
- Não usar
  - Para criar seu layout

Para fazer uma tabela básica, apenas precisaremos da **_tag `<table></table>`_**, dentro dela iremos usar a tag `<tr></tr>`(table row) para criar uma linha na tabela, e dentro dela usaremos a tag `<th></th>` para o cabeçalho.

Depois faremos o `tr` novamente, só que agora não sendo o cabeçalho, e sim o `td`.

Ficará da seguinte foram:

```bash
<table>
    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>
    <tr>
        <td>Mayk</td>
        <td>35</td>
    </tr>
    <tr>
        <td>Diego</td>
        <td>25</td>
    </tr>
</table>
```

Agora vamos dar uma melhor organizada na nossa tabela.

Colocaremos o nosso cabeçalho, na tag **_<thead></thead>_** e o nosso corpo no **_<tbody></tbody>_** e criaremos o rodapé usando **_<tfoot></tfoot>_** colocando os dados total.

Por fim poderemos colocar a tag **_<caption></caption>_** para descrever sobre o que a nossa tabela é, ficando mais ou menos assim:

```bash
<table>

    <caption>Pessoas por idade</caption>

    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Mayk</td>
            <td>35</td>
        </tr>
        <tr>
            <td>Diego</td>
            <td>25</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Total:</td>
            <td>2 Pessoas</td>
        </tr>
    </tfoot>

</table>
```

Estaremos usando o atributo **_scope,_** que serve permitir que essa acessibilidade saiba que o escopo do cabeçalho é relacionado com, o agrupamento, ou a coluna, ou a linha, o atributo é escrito `scope=""`.

```bash
<table>
    <caption>Produzidos x Vendidos por Loja</caption>

    <colgroup>
        <col>
        <col span="2" style="background-color: red">
        <col span="2" style="background-color: blue;">
    </colgroup>

    <thead>
        <tr>
            <th rowspan="2"></th>
            <th colspan="2" scope="colgroup">Afonso Pena</th>
            <th colspan="2" scope="colgroup">Antônia Pereira</th>
        </tr>
        <tr>
            <th scope="col">Produzidos</th>
            <th scope="col">Vendidos</th>
            <th scope="col">Produzidos</th>
            <th scope="col">Vendidos</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Vassouras</th>
            <td>50</td>
            <td>30</td>
            <td>20</td>
            <td>20</td>
        </tr>
        <tr>
            <th scope="row">Baldes</th>
            <td>10</td>
            <td>10</td>
            <td>30</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

### CABEÇALHO

- `<head></head>`
  É a parte não visível pelo navegador, onde se faz configurações, contém informações como o título, links para o CSS, para o favicon.

- `<meta>`
   Ela serve para definir metadados, como codificação de caracteres especiais e portabilidade para dispositivos mobiles.

      Meta normalmente virá com o atributo ***name*** para especificar a ***meta***, ***content*** para conteúdo, mas há também como o atributo ***charset***, para caracteres especiais.

      ```bash
      <head>
          <!-- codificação de caracteres especiais -->
          <meta charset="UTF-8">

          <!-- portabilidade para dispositivos mobiles -->
          <meta name="viewport" content="width=device-width, initial-scale=1.0">

      </head>
      ```

- FAVICON
  Favicon é uma abreviação para _"favorite icon"_, refere-se aos ícones dos favoritos a alguns anos atrás, mas nos dias de hoje acabou ficando este termo, antigamente ele era por 16 pixeis, porém com o avanço da tecnologia isso mudou.
  Para colocarmos o ícone usaremos a tag `<link>` com o atributo **_rel="icon"_**, que seria para representar relação, no caso a tag **_link_** vai conter um ícone, depois o **_href_** para mostrar onde está o ícone

  ```bash
  <!--
      <link> para ícones personalizados
  -->

  <!-- favicon básico -->
  <link rel="icon" href="/icons/icon-48x48.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <!-- iPhone não-Retina, iPod Touch e dispositivos Android 2.1+: -->
  <link rel="apple-touch-icon-precomposed" href="https://developer.cdn.mozilla.net/static/img/favicon57.a2490b9a2d76.png">

  <!-- iPad de primeira e segunda geração: -->
  <link rel="apple-touch-icon" sizes="48x48" href="/icons/icon-48x48.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <link rel="apple-touch-icon" sizes="72x72" href="/icons/icon-72x72.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <link rel="apple-touch-icon" sizes="96x96" href="/icons/icon-96x96.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <!-- iPhone com tela retina de alta resolução: -->
  <link rel="apple-touch-icon" sizes="144x144" href="/icons/icon-144x144.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <!-- iPad de terceira geração com tela retina de alta resolução: -->
  <link rel="apple-touch-icon" sizes="192x192" href="/icons/icon-192x192.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <link rel="apple-touch-icon" sizes="256x256" href="/icons/icon-256x256.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <link rel="apple-touch-icon" sizes="384x384" href="/icons/icon-384x384.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>

  <link rel="apple-touch-icon" sizes="512x512" href="/icons/icon-512x512.png?v=cfca599cb367ccaf7377d56ddc7542f5"/>
  ```

### SEO (Search Engine Optimization)

- Veremos agora das metas que são importantes para SEO(Search Engine Optimization ou motores de busca, como o google).

```bash
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- Esses já vimos anteriormente.

```bash
<meta name="author" content="Mayk Brito">
```

- Temos também o de autor, para definir o autor da página, para possuirmos propriedade sobre a página.

```bash
<meta name="description" content="Um website para iniciantes em programação">
```

- Este meta é usado para descrição de sites, caso você não tenha esse meta, o navegador irá procurar qualquer texto seu, mas muito melhor escolher o que você quer que apareça.

```bash
<meta name="robots" content="index, follow">
```

- Esse meta diz para o robô do google o que queremos que ele faça, ele é responsável por colocar os resultados da busca , por exemplo. É possível dizer ao robô seguir links na página, através do `follow`, ou o contrário com o `nofollow` , ou "indexar" a página, através do index, ou no index.

- Existem metadados personalizados por empresas de redes sociais, como Facebook, que criou o Open Graph, que é um tipo de metadado se quisermos colocar um tipo de conteúdo especial, caso queiramos compartilhar o link da nossa página no Facebook.

```bash
 <head>
    <!-- Open Graph: facebook -->
    <meta property="og:image" content="https://cdn-images-1.medium.com/max/92/1*TkXVfLTwsHdwpUEjGzdi9w@2x.jpeg">
    <meta property="og:description" content="Aqui vem um texto para ser mostrado ao compartilhar no facebook">
    <meta property="og:title" content="Um site da Rocketseat">

    <!-- twitter -->
    <meta name="twitter:title" content="Rocketseat">
</head>
```

São exemplos de metadados, que o Facebook procura na hora que compartilhamos a nossa página, como imagens, descrição, texto e outros.

O Twitter usa o atributo `name` diferente do Facebook que resolveu usar o `property` .
