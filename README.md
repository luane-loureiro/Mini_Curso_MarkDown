# Mini Curso MarkDown
Repositorio para guardar tutoriais e Dicas de MarkDown.
<br><br>
## O que é Markdown?
Markdown é uma linguagem de marcação leve que você pode usar para adicionar elementos de formatação a documentos de texto simples.
Em um aplicativo como o Microsoft Word, você clica em botões para formatar palavras e frases, e as alterações ficam visíveis imediatamente. Markdown não é assim. Quando você cria um arquivo formatado em Markdown (.md), você adiciona sintaxe Markdown ao texto para indicar quais palavras e frases devem ter aparência diferente.
Markdown nâo é uma linguagem de programção, e sim uma linguagem de marcaçâo, assim como em um HTML, só que bem mais simples.
<br><br>
## Para que serve o Markdown?
Markdown é uma maneira rápida e fácil de fazer anotações, criar conteúdo para um site e produzir documentos prontos para impressão.
Não demora muito para aprender a sintaxe do Markdown, e uma vez que você saiba como usá-la, você pode escrever usando Markdown em praticamente qualquer lugar. 
A maioria das pessoas usa Markdown para criar conteúdo para a web, mas Markdown é bom para formatar tudo, de mensagens de e-mail a listas de compras.
<br><br>
## Como ele funciona?
Quando você escreve em Markdown, o texto é armazenado em um arquivo de texto simples que tem uma extensão .md ou .markdown.
Depois você precisa de um aplicativo Markdown capaz de processar o arquivo Markdown. Apesar de suas diferenças visuais, todos os aplicativos fazem a mesma coisa, todos eles convertem texto formatado em Markdown para HTML para que ele possa ser exibido em navegadores da web.
<br><br><br>
![image](https://github.com/user-attachments/assets/23a6f8a9-d77a-47b2-b42f-2ae623ffca84)
<br><br><br>
## Por que usar Markdown?
- Markdown pode ser usado para tudo. As pessoas o usam para criar sites , documentos , notas , livros , apresentações , mensagens de e-mail e documentação técnica .
- O Markdown é portátil. Arquivos contendo texto formatado em Markdown podem ser abertos usando praticamente qualquer aplicativo.
- Markdown é independente de plataforma. Você pode criar texto formatado em Markdown em qualquer dispositivo executando qualquer sistema operacional.
- Markdown é à prova do futuro. Mesmo que o aplicativo que você está usando pare de funcionar em algum momento no futuro, você ainda poderá ler seu texto formatado em Markdown usando um aplicativo de edição de texto. Esta é uma consideração importante quando se trata de livros, teses universitárias e outros documentos importantes que precisam ser preservados indefinidamente.
- Markdown está em todo lugar. Sites como Reddit e GitHub dão suporte a Markdown, e muitos aplicativos de desktop e baseados na web dão suporte a ele.
<br><br>
## Como Aprender Markdown?
A melhor maneira de começar a usar o Markdown é usá-lo.
Você nem precisa baixar nada. Existem vários editores Markdown online que você pode usar para tentar escrever em Markdown. Ou você pode usar o próprio GitHub, para criar readme de seus projetos ou a sua página de sobre mim.

## Sintaxe básica

### Criando Títulos 

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

### Destacando com itálico
Para tornar uma frase ou palávra itálica no Markdown, você pode cercar as palavras com um asterisco (*)

```
Writing in _Markdown_ is not that hard!
```
Writing in _Markdown_ is not that hard!

### Destacando com Negrito
Para tornar uma frase itálica no Markdown, você pode cercar as palavras com dois asteriscos (**)
```
Writing in **Markdown** is not that hard!
```
Writing in **Markdown** is not that hard!

### Negrito e itálico
Para tornar uma frase ou palávra em negrito e itálica no Markdown, você pode cercar as palavras com um três asteriscos (***)
```
Writing in ***Markdown*** is not that hard!
```
Writing in ***Markdown*** is not that hard!

### Citações de um paragráfo
Para criar um blockquote, adicione um sinal de maior (>) antes de um parágrafo.

```
> Writing in Markdown is not that hard!
```
> Writing in Markdown is not that hard!

### Citações de vários paragráfos
Blockquotes podem conter vários parágrafos. Adicione um sinal de maior (>) nas linhas em branco entre os parágrafos.

```
> Writing in Markdown is not that hard!
>
> You can do it.
```
> Writing in Markdown is not that hard!
>
> You can do it.

### Listas ordenadas
Para criar uma lista ordenada, adicione itens de linha com números seguidos por ponto.

```
1. primeiro item
2. segundo item
3. terceiro item
```

1. primeiro item
2. segundo item
3. terceiro item

### Listas não ordenadas
Para criar uma lista não ordenada, adicione traços ( -), asteriscos ( *) ou sinais de mais ( +) na frente dos itens de lista (particularmente costumo isar o traço (-)). 

```
- primeiro item
- segundo item
- terceiro item
```

- primeiro item
- segundo item
- terceiro item

### listas não ordenadas aninhadas
Recue um ou mais itens para criar uma lista aninhada.

```
- primeiro nivel
  - segundo nivel
      - terceiro nivel
```
- primeiro nivel
  - segundo nivel
      - terceiro nivel

### listas ordenadas e não ordenadas aninhadas
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

### Linhas Horizontais
Para criar uma régua horizontal, use três ou mais asteriscos ( ***), traços ( ---) ou sublinhados ( ___) em uma linha isoladamente.

```
Conteudo 1

---

Conteudo 2
```

Conteudo 1

---

Conteudo 2


### Criando Tabelas
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


### Blocos de Códigos 
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

### Links
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


### Imagens
Para adicionar uma imagem, adicione um ponto de exclamação (!), seguido por texto alt entre colchetes e o caminho ou URL para o recurso de imagem entre parênteses. Opcionalmente, você pode adicionar um título entre aspas após o caminho ou URL.

```
![Google](https://cdn.iconscout.com/icon/free/png-256/free-google-2690379-2232882.png "Google")
```

![Google](https://cdn.iconscout.com/icon/free/png-256/free-google-2690379-2232882.png "Google")

## Usando o HTML
Muitos aplicativos Markdown permitem que você use tags HTML em texto formatado em Markdown. Isso é útil se você preferir certas tags HTML à sintaxe Markdown. Por exemplo, algumas pessoas acham mais fácil usar tags HTML para imagens. Usar HTML também é útil quando você precisa alterar os atributos de um elemento, como especificar a cor do texto ou alterar a largura de uma imagem.

Para usar HTML, coloque as tags no texto do seu arquivo formatado em Markdown.

```
Esta **palavra** está em negrito. Esta <em>palavra<em> está em itálico.

```

A saída renderizada se parece com isso:

Esta **palavra** está em negrito. Esta <em>palavra<em> está em itálico.
