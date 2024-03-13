# aulas-front-end

## Html


- estruturação
- semantica
- Padrões Web

## Css

Linguagem de estilização que "casa" com elementos HTML.

Em geral, CSS serve para:

1. Estilos (sombra, borda etc)
2. alinhamento
3. Desing responsivo
4. Animações e efeitos especiais de interação

### Formas de implementação

#### Inline

O css é aplicado diretamente em cada tag Html

#### Interna/Onpage

O CSS é criado usando regras (com seletores, propriedades, valores) dentro da própria página que queremos formatar.

As regras vão valer para todos os elementos/tags desta página.

#### Externa (mais usada!)

É criado um arquivo de extensão CSs dedicando às regras de formataçãp. Este arquivo é então "conectado" às paginas HTML.

```css
seletor { propriedade: valor;}

seleltor {
    propriedade1: valor;
    propriedade2: valor;
    PropriedadeN: valor;
}
```

---

### Tipos de seletor


- Tag: seletor mais abrangente/generalista, casa com elementos HTML de acordo com a tag especificada.

- Descendente: seletor mais específico, casa com elementos que são filhos (descendentes) de outro elemento. Usa-se espaço para separar o filho/Pai .

- Agrupado: grupo de seletores que compartilham uma mesma formatação. Usa-se , para separar os seletores.

- Pseudo-Classe: classes "prontas/nativas" da linguagem que podem ser aplicadas em diversas situações. Exemplos: passar mouse, reconhecer foco, selecionar determinados elementos etc. TODAS pseudo-classes começam com dois-pontos  :

- Classe: seletor versátio que permite a aplicação de estilos em diversos elementos, possibilitando também a combinação de diferentes classes. No Css usa-se .nome-da-classe para criar a classe, e no HTML usa-se o atributo class="nome-da-classe" para aplicar a classe.

- Identificado: seletor bastante restrito (o msm id só pode ser usado em um elemento por página), permitindo criar uma estilização altamente especifical. No CSS usa-se #nome-do-id para criar, e no HTML usa-se o atributo id="nome-do-id" para aplicar.