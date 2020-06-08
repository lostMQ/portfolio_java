---
title: "Exemplos de Formatação"
date: "1986-09-17"
author: "Elliot"
cover: "img/hello.jpg"
draft: true
description: "\"Hello, friend?\" That's lame. Maybe I should give you a name?"
---

# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6

Este texto é um paragrafo  
Esta linha não tem espaçamento da anterior pq acabamos a linha anterior com 2 espaços

Em Markdown (.md) os paragrafo tem de ser separados por uma linha em branco

> Isto é uma citação

- Uma
- Lista
    - Desordenada
        - Identada

[Isto é um link](http://www.google.pt)


Imagem sem shortcode
![texto exemplo](/img/hello.jpg)

Imagem usando o shortcode image
{{< image src="/img/hello.jpg" alt="Hello Friend" position="center" style="border-radius: 8px;" >}}

Imagem usando o shortcode figure
{{< figure src="/img/hello.jpg" alt="Hello Friend" position="center" style="border-radius: 8px;" caption="Hello Friend!" captionPosition="center" captionStyle="color: red;" >}}

caixa de código
```java
public class hello{
    public function main(){
        system.out.println("Hello World!");
    }
}
```

Isto é uma linha horizontal

---

Uma tabela

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Para ver todos os exemplos [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)