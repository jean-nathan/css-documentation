# Fundação do Front-end (Documentação de HTML, CSS e JavaScript)

Bem-vindo à documentação de HTML, CSS e JavaScript. Esta documentação oferece explicações detalhadas e exemplos para cada tecnologia, organizados por categoria e funcionalidade.

## Categorias

### HTML
- [Tags Semânticas](html/semantic-tags.md)
- [Formulários](html/forms.md)
- [Tabelas](html/tables.md)
- [Links e Navegação](html/links-navigation.md)

### CSS
- [Flexbox](css/flexbox.md)
- [Grid](css/grid.md)
- [Tipografia](css/typography.md)
- [Cores](css/colors.md)
- [Transições](css/transitions.md)

### JavaScript
- [Manipulação do DOM](js/dom-manipulation.md)
- [Eventos](js/events.md)
- [Funções](js/functions.md)
- [Objetos e Arrays](js/objects-arrays.md)
- [Promises e Async/Await](js/promises-async-await.md)

## Modelo de Documentação

Para garantir consistência e clareza em toda a documentação, siga o modelo abaixo ao adicionar novos itens, sejam propriedades, elementos ou funcionalidades:

### HTML

1. **Título do Elemento**
   - Descrição: Explique o propósito e o uso do elemento HTML.
   - Atributos: Liste e descreva os principais atributos.
   - Exemplo: Forneça um exemplo de código HTML utilizando o elemento.
   - Visualização: Inclua uma imagem ou descrição visual do comportamento esperado.

### CSS

1. **Título da Propriedade**
   - Descrição: Explique o propósito e a função da propriedade.
   - Valores: Liste e descreva os valores possíveis.
   - Exemplo: Forneça um exemplo de código CSS utilizando a propriedade.
   - Visualização: Inclua imagens ou GIFs para mostrar visualmente o efeito da propriedade.

### JavaScript

1. **Título da Função/Objeto**
   - Descrição: Explique o que a função ou objeto faz.
   - Parâmetros: Descreva os parâmetros e seus tipos.
   - Exemplo: Forneça um exemplo de código JavaScript utilizando a função/objeto.
   - Visualização: Inclua uma explicação do comportamento esperado no navegador ou em uma aplicação prática.

## Exemplo de Documentação

### HTML

#### `form.md`

```markdown
# `form`

A tag `<form>` é utilizada para criar formulários de entrada de dados. É comumente usada para enviar informações do usuário para o servidor.

## Atributos

- **`action`**: Define o destino para onde os dados do formulário serão enviados.
- **`method`**: Especifica o método HTTP utilizado (GET ou POST).
  
## Exemplo

### Código

```html
<form action="/submit" method="POST">
  <input type="text" name="nome" />
  <button type="submit">Enviar</button>
</form>
```
```

### CSS

#### `flex-direction.md`

```markdown
# `flex-direction`

A propriedade `flex-direction` define a direção dos itens dentro do contêiner flexível.

## Valores

- **`row`** (padrão): Itens são dispostos horizontalmente.
- **`column`**: Itens são dispostos verticalmente.
- **`row-reverse`**: Itens são dispostos horizontalmente, mas na direção oposta.
- **`column-reverse`**: Itens são dispostos verticalmente, mas na direção oposta.

## Exemplo

### Código

```css
.container {
  display: flex;
  flex-direction: column;
}
```
```

### JavaScript

#### `addEventListener.md`

```markdown
# `addEventListener`

O método `addEventListener` é utilizado para registrar uma função que será chamada sempre que o evento especificado ocorrer.

## Parâmetros

- **`evento`**: O tipo de evento a ser escutado, como `click`, `mouseover`, etc.
- **`função`**: A função que será executada quando o evento ocorrer.

## Exemplo

### Código

```javascript
document.getElementById('btn').addEventListener('click', function() {
  alert('Botão clicado!');
});
```
```
