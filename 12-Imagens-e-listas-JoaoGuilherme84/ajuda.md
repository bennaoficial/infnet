# Imagens e listas

## Imagens

### Externas
```html
<img src="https://www.infnet.edu.br/infnet/wp-content/uploads/sites/6/2021/10/infnet_mod.svg" alt="Logo da Infnet">
```

### Internas
```html
<img src="./assets/img/logo.png" alt="Logo da Infnet">

<!--Para imagens internas, a imagem precisa estar na pasta referente ao caminho que estamos apontando, onde o `.` representa o diretório onde o arquivo html está. Na aula o arquivo index.html tinha ao seu lado a pasta assets e dentro da assets a pasta img com a logo.png dentro.-->
```

Use height ou width para definir o tamanho da imagem, basta adicionar com atributo da tab assim: 
```html
<img src="./assets/img/logo.pn" alt="Logo da Infnet" width="100"> 
<!--Para alterar a largura-->

<img src="./assets/img/logo.pn" alt="Logo da Infnet" height="50"> 
<!-- Para alterar a altura-->

<!-- Você também pode passar os dois juntos. Mas cuidado, pois pode distorcer a imagem.-->
```

## Listas

**Não ordenadas**
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
  <li>Item 5</li>
</ul>
```

**Ordenadas**
```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
  <li>Item 5</li>
</ol>
```

### Listas aninhadas

```html
<ol>
  <li>
    Item 1
    <ol>
      <li>Subitem 1.2</li>
      <li>Subitem 1.2</li>
      <li>Subitem 1.3</li>
    </ol>
  </li>
  <li>
    Item 2
    <ol>
      <li>Subitem 2.1</li>
      <li>Subitem 2.2</li>
      <li>Subitem 2.3</li>
    </ol>
  </li>
</ol>
```