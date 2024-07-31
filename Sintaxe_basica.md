# Sintaxe básica

## Criando Títulos 

# Writing in Markdown is not that hard!
```
# Writing in Markdown is not that hard!
```
## Writing in Markdown is not that hard!
```
## Writing in Markdown is not that hard!
```

### Writing in Markdown is not that hard!
```
### Writing in Markdown is not that hard!
```

#### Writing in Markdown is not that hard!
```
#### Writing in Markdown is not that hard!
```
<br><br>
## Destacando com itálico
Para tornar uma frase ou palávra itálica no Markdown, você pode cercar as palavras com um asterisco (*)

```
Writing in _Markdown_ is not that hard!
```
Writing in _Markdown_ is not that hard!
<br><br>
## Destacando com Negrito
Para tornar uma frase itálica no Markdown, você pode cercar as palavras com dois asteriscos (**)
```
Writing in **Markdown** is not that hard!
```
Writing in **Markdown** is not that hard!
<br><br>
## Negrito e itálico
Para tornar uma frase ou palávra em negrito e itálica no Markdown, você pode cercar as palavras com três asteriscos (***)
```
Writing in ***Markdown*** is not that hard!
```
Writing in ***Markdown*** is not that hard!
<br><br>
## Texto Tarchado (riscado)
Para tornar uma frase ou palávra tarchada no Markdown, você pode cercar as palavras com dois til (~~)
```
Writing in ~~Markdown~~ is not that hard!
```
Writing in ~~Markdown~~ is not that hard!
<br><br>
## Citações de um paragráfo
Para criar um blockquote, adicione um sinal de maior (>) antes de um parágrafo.

```
> Writing in Markdown is not that hard!
```
> Writing in Markdown is not that hard!
<br><br>
## Citações de vários paragráfos
Blockquotes podem conter vários parágrafos. Adicione um sinal de maior (>) nas linhas em branco entre os parágrafos.

```
> Writing in Markdown is not that hard!
>
> You can do it.
```
> Writing in Markdown is not that hard!
>
> You can do it.
<br><br>
## Alertas
Alertas são uma extensão Markdown baseada na sintaxe blockquote que você pode usar para enfatizar informações críticas. Em GitHub, eles são exibidos com cores e ícones distintos para indicar a importância do conteúdo.

```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
<br><br>
Use alertas apenas quando eles forem cruciais para o sucesso do usuário e limite-os a um ou dois por artigo para evitar sobrecarregar o leitor.
## Listas ordenadas
Para criar uma lista ordenada, adicione itens de linha com números seguidos por ponto.

```
1. primeiro item
2. segundo item
3. terceiro item
```

1. primeiro item
2. segundo item
3. terceiro item
<br><br>
## Listas não ordenadas
Para criar uma lista não ordenada, adicione traços ( -), asteriscos ( *) ou sinais de mais ( +) na frente dos itens de lista (particularmente costumo isar o traço (-)). 

```
- primeiro item
- segundo item
- terceiro item
```

- primeiro item
- segundo item
- terceiro item
<br><br>
## listas não ordenadas aninhadas
Recue um ou mais itens para criar uma lista aninhada.

```
- primeiro nivel
  - segundo nivel
      - terceiro nivel
```
- primeiro nivel
  - segundo nivel
      - terceiro nivel
<br><br>
## listas ordenadas e não ordenadas aninhadas
Você pode aninhar uma lista não ordenada em uma lista ordenada, ou vice-versa.

```
1. primeiro nivel
    - segundo nivel
    - segundo nivel
      - terceiro nivel
      - terceiro nivel
2. primeiro nivel
```

1. primeiro nivel
    - segundo nivel
    - segundo nivel
      - terceiro nivel
      - terceiro nivel
2. primeiro nivel
<br><br>
## Listas de tarefas
Para criar uma lista de tarefas, coloque um hífen e um espaço seguidos de [ ] antes dos itens de lista. Para marcar uma tarefa como concluída, use [x].

```
- [x] Estudar
- [ ] fazer exercícios
- [ ] ter uma aliemntação saldável
```

- [x] Estudar
- [ ] fazer exercícios
- [ ] ter uma aliementação saldável

  <br><br>
## Linhas Horizontais
Para criar uma régua horizontal, use três ou mais asteriscos ( ***), traços ( ---) ou sublinhados ( ___) em uma linha isoladamente.

```
Conteudo 1

---

Conteudo 2
```

Conteudo 1

---

Conteudo 2

<br><br>
## Criando Tabelas
Você pode criar tabelas com pipes | e hífens -. Hifens são usados para criar o cabeçalho de cada coluna, enquanto as barras verticais separam cada coluna. Você deve incluir uma linha em branco antes da tabela para ela ser construída corretamente.
As barras verticais em cada extremo da tabela são opcionais.
As células podem ter largura variada e não precisam estar alinhadas perfeitamente com as colunas. Deve ter no mínimo três hifens em cada coluna da linha do cabeçalho.

```

| titulo 1  | titulo 2 |
| --------- | ---------|
| conteudo  | conteudo |
| conteudo  | conteudo |
| conteudo  | conteudo |
| conteudo  | conteudo |

```

| titulo 1  | titulo 2 |
| --------- | ---------|
| conteudo  | conteudo |
| conteudo  | conteudo |
| conteudo  | conteudo |
| conteudo  | conteudo |

<br><br>
## Blocos de Códigos 
Você pode criar blocos de código isolados colocando acentos graves triplos ( ``` ) antes e depois do bloco de código. É recomendável colocar uma linha em branco antes e depois dos blocos de código para facilitar a leitura da formação bruta.

````

```
const sayHello = "Olá Mundo!";
console.log (sayHello);
```

````

```
const sayHello = "Olá Mundo!";
console.log (sayHello);
```

Você pode adicionar um identificador de linguagem opcional para habilitar o realce de sintaxe no bloco de código isolado.
O realce da sintaxe altera a cor e o estilo do código-fonte para facilitar a leitura.
Por exemplo, para código javaScript do realce de sintaxe:


````

```javascript
const sayHello = "Olá Mundo!";
console.log (sayHello);
```

````

```javascript
const sayHello = "Olá Mundo!";
console.log (sayHello);
```
<br><br>
## Links
Para criar um link, coloque o texto do link entre colchetes (por exemplo, [Google]) e, em seguida, coloque imediatamente o URL entre parênteses (por exemplo, (https://google.com)).

```
[Google](https://google.com)
```

[Google](https://google.com)


Opcionalmente, você pode adicionar um título para um link. Isso aparecerá como uma dica de ferramenta quando o usuário passar o mouse sobre o link. Para adicionar um título, coloque-o entre aspas após o URL.

```
[Google](https://google.com"O mais famoso sistema de buscas")
```

[Google](https://google.com "O mais famoso sistema de buscas")
<br><br>
## Imagens
Para adicionar uma imagem, adicione um ponto de exclamação (!), seguido por texto alt entre colchetes e o caminho ou URL para o recurso de imagem entre parênteses. Opcionalmente, você pode adicionar um título entre aspas após o caminho ou URL.

```
![Google](https://cdn.iconscout.com/icon/free/png-256/free-google-2690379-2232882.png "Google")
```

![Google](https://cdn.iconscout.com/icon/free/png-256/free-google-2690379-2232882.png "Google")
<br><br>
## Usar emojis
É possível adicionar um emoji à escrita digitando :EMOJICODE:, dois pontos e, em seguida, o nome do emoji.
Se você digitar :, uma lista de emojis sugeridos será exibida. A lista será filtrada à medida que você digitar algo. Portanto, assim que encontrar o emoji que estava procurando, pressione Tab ou ENTER para completar o resultado realçado.

```
:+1:
```
:+1:

Eu prefiro(caso esteja usando windows)  apertar a tecla do logotipo do win + tecla ponto (.) para abrir o painel de emojis e escolher algum na lista.
<br><br>
## Usando o HTML
Muitos aplicativos Markdown permitem que você use tags HTML em texto formatado em Markdown. Isso é útil se você preferir certas tags HTML à sintaxe Markdown. Por exemplo, algumas pessoas acham mais fácil usar tags HTML para imagens. Usar HTML também é útil quando você precisa alterar os atributos de um elemento, como especificar a cor do texto ou alterar a largura de uma imagem.

Para usar HTML, coloque as tags no texto do seu arquivo formatado em Markdown.

```
Esta **palavra** está em negrito. Esta <em>palavra<em> está em itálico.

```

A saída renderizada se parece com isso:

Esta **palavra** está em negrito. Esta <em>palavra<em> está em itálico.
