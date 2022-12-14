# Repository para o módulo de HTML 5 do curso FullStack Javascript da T.EXperts

## 2.3.1 – Estrutura de Diretórios

### Criação da estrutura de pastas que será utilizada durante o curso.

        root
            readme.md
            index.html
            \pages
            \images
            \src
                \css
            \samples
                \test


## 2.3.2 – Estrutura de um documento HTML

### A Estrutura de um documento HTML

    - A tag <!DOCTYPE html> tem como intuito informar que este documento se trata de um documento HTML 5.
    - As tags head e body são fundamentais para a estrutura da página, sendo a body responsável por todo o corpo da página, e o head utilizado para consulta de sistemas externos.
    - Um comentário em HTML é definido pela seguinte estrutura <!–Comentário–>.

## 2.3.3 – Semântica HTML

As tags semânticas representam alguma parte da página, como a header, footer e section.
A semântica das tags é capaz de comunicar para agentes externos o que cada parte do html significa, por exemplo, a tag article é capaz de comunicar que naquela área está contido um artigo.

### Elementos Semânticos

![Elementos Semanticos](/src/images/tableElementosSemanticos.png "Estrutura Semântica da Página")

## 2.3.4 – Formatando o texto em HTML

A tag strong é capaz de realizar a marcação negrito visualmente, e deixa claro para a máquina de que aquele trecho se trata de um texto com alta relevância. Diferente da tag b, que apenas gera o negrito visualmente, não deixando significado semântico.
Para o efeito de itálico, utiliza-se a tag em com efeito semântico, ou a tag i, sem efeito semântico.
É possível utilizar a tag pre, para que se use uma pré-formatação.

## 2.3.5 – Criando listas
É possível criar uma lista ordenada utilizando a tag ol, de forma que através da propriedade type, pode-se alterar o tipo de ordenação da lista, sendo numérica, alfabética ou com algarismos romanos.
Com a tag ul, é possível criar uma lista não ordenada. Pode-se ainda trocar os bullets por outros símbolos de representação dos itens, por meio da propriedade type.
Existe ainda a lista de definição, criada a partir da tag dl, que possui um esquema de tabulamento com seu título e itens.
