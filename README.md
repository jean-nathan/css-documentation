# Documentação de Propriedades CSS

Bem-vindo à documentação das propriedades CSS. Aqui você encontrará explicações e exemplos para cada propriedade, organizados por categoria.

## Categorias

- [Flexbox](css-properties/flexbox.md)
- [Grid](css-properties/grid.md)
- [Tipografia](css-properties/typography.md)
- [Cores](css-properties/colors.md)
- [Transições](css-properties/transitions.md)

## Modelo de Documentação

Para garantir consistência e clareza, siga o modelo abaixo ao adicionar novas propriedades à documentação:

1. **Título da Propriedade**
   - Descrição: Explique o propósito e a função da propriedade.
   - Valores: Liste e descreva os valores possíveis.
   - Exemplo: Forneça um exemplo de código CSS utilizando a propriedade.
   - Visualização: Inclua imagens ou GIFs para mostrar visualmente o efeito da propriedade.

### Exemplo de Documentação

#### `flex-direction.md`

````markdown
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
````
