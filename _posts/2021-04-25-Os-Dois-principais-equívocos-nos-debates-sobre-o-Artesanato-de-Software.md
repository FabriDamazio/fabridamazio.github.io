---
layout: post
title: Os dois principais equívocos no debate sobre o Artesanato de Software
gh-repo: FabriDamazio/fabridamazio.github.io
gh-badge: [star, follow]
tags: [artesanato]
comments: true
---

## Uma longa e desnecessária introdução

Mário de Andrade foi um poeta, romancista, musicólogo, historiador de arte, crítico e fotógrafo brasileiro e um dos fundadores do modernismo no país. Assumiu a cadeira de Filosofia e História da Arte no Instituto de Artes da Universidade do Distrito Federal em 1938. "O artista e o artesão" foi  a aula inaugural dos cursos de Filosofia e História da Arte daquele ano [[1]](###Fontes). Nesta aula, em dado momento, ele apresenta o que seriam as três regiões que constituem a técnica: o artesanato, a virtuosidade e a solução pessoal. O artesanato seria "a parte da técnica que se pode ensinar", a virtuosidade seria "o conhecimento da técnica tradicional" e a solução pessoal não se estaria nos domínios do aprendizado, sendo parte de um "talento de cada um". 

O Artesanato de Software(Software Craftsmanship) tem origem no movimento de desenvolvimento ágil de software, o qual tinha o objetivo de reformular a maneira como gerenciamos e executamos projetos de software[[2]](###Fontes). Este novo movimento invoca o sentimento de orgulho pela mão de obra, qualidade, elegância e atenção aos detalhes que os programadores aspiram. Sugere ainda que que os desenvolvedores de software não precisam se ver como parte da tradição da engenharia e que uma metáfora diferente seria mais adequada. Este seria a do programador como artesão de software, remetendo aos artesões medievais que eram profissionais especializados em fabricar ou prestar um determinado serviço e dedicavam a vida a se tornar um mestre em seu ofício.

Pensando no desenvolvedor de software como um artesão, podemos explorar melhor, no contexto de desenvolvimento de software, uma das três regiões da técnica requeridas de um artista citadas por Mario de Andrade, o artesanato. Ele afirma que "Existe, certo, dentro da arte, um elemento, o material, que é necessário por em ação, mover, pra que a obra de arte se faça...Mas nos processos de movimentar o material, a arte se confunde quase inteiramente com o artesanato. Pelo menos naquilo que se aprende.". Que fique claro, não considero código ou software uma obra de arte, mas no artesanato de software o elemento citado, o material, pode ser entendido como o código em si, que precisa ser escrito, movido, alterado para que o produto seja criado e esta parte da técnica pode ser ensinada, aprendida e aprimorada. O artesanato de software é sobre este elemento, sobre como devemos entende-lo e domina-lo e sobre como aprender e ensinar como isso deve ser feito, da maneira que entregue mais qualidade, agregue mais valor tanto para o produto em si quanto para quem o desenvolve. O livro Apprenticeship Patterns, de Dave H. Hoover e Adewale Oshineye, trás uma ótima explicação, a qual tentarei resumir, do que estamos falando quando falamos de "artesanato de software". Falamos de uma comunidade de prática unificada e definida por valores em comum, incluindo: uma "mentalidade de crescimento", que envolve a crença de que você pode ser melhor e tudo pode ser melhorado se você estiver preparado para trabalhar nisso, a necessidade de estar sempre se adaptando e mudando com base no feedback que você recebe do mundo a sua volta, o desejo de ser pragmático em vez de dogmático, a crença de que é melhor compartilhar o que sabemos, uma vontade de experimentar e provar que está errado, ter controle e responsabilidade por nossos destinos e não esperar que outra pessoa dê-nos as respostas, foco em indivíduos ao invés de grupos (não é um movimento com líderes e seguidores), um compromisso com a inclusão, centrados em habilidades e não em processos e uma forte preferência pela"aprendizagem situada", ou seja, que a melhor maneira de aprender é estar na mesma sala com pessoas que estão tentando atingir algum objetivo usando as habilidades que deseja aprender[[3]](###Fontes).

## Os dois principais equívocos

Alguns anos atrás, comecei a ter contato com o tema e me interessei em saber um pouco mais. A metáfora do artesão, para mim, parecia realmente adequada mas, para minha surpresa, ao pesquisar pelo assunto me deparei com polêmicos artigos com fortes contrapontos (o mais famoso deles talvez seja o artigo do Dan North chamado "Programming is not a craft"[[4]](###Fontes)). Um bom tempo passou-se desde então e, motivado pelo fato de que, de forma recorrente, seja em artigos, blogs, lives ou podcasts, sempre me deparo com comentários sobre o tema, resolvi colocar no "papel" dois breves equívocos que tornam o debate sobre o artesanato de software na comunidade brasileira pouco produtivo. O primeiro equívoco é não diferenciar o artista do artesão e o segundo é não diferenciar arte de obra de arte.

### Artista versus artesão

A grande maioria dos debates partem da premissa de que seus programadores artesões se consideram artistas. Isso acontece pela confusão sobre o que é o artista e o que é o artesão. O artesão não é necessariamente um artista e vice-versa. O artesão é um profissional que fabrica produtos que necessitam algum tipo de habilidade específica através de um processo manual ou com auxílio de ferramentas. Dyson Freeman, em seu ensaio "Ciência como Indústria Artesanal" (Science as a Craft Industry), diz que "Uma das ferramentas mais importantes da ciência moderna é o computador...Mas o computador deu origem a uma indústria artesanal maior que ainda está florescendo, a indústria de software."[[5]](###Fontes). É da premissa de programadores como artesãos, e não como artistas, que deve partir o debate sobre o movimento do Artesanato de Software e, correndo o risco de soar tirânico, afirmo que qualquer debate que não respeitar essa premissa deve ser completamente ignorado. O processo de desenvolvimento de software é um processo manual desenvolvido com o auxílio de inúmeras ferramentas, como editores de código e frameworks, onde cada uma das linhas é escrita especificamente para resolver uma necessidade em específico. Não consigo pensar nisso como um processo não artesanal. Há de se fazer uma ressalva importante aqui, talvez o fato de muitos desenvolvedores que se dizem artesãos não terem ido além do manifesto, os faça se verem realmente como artistas e isso provavelmente contribui para que isso seja tomado como premissa.

### Arte versus obra de arte

O segundo equívoco comum é pensar no artesanato de software apenas com foco no código ou software produzido, como se o artesão buscaria no código algum tipo de produção de obra arte. Se no primeiro problema citado acima tem a raiz na confusão sobre o que é o artista e o artesão, este é sobre o que é arte e obra de arte. Arte pode ser definida como um conjunto de meios e procedimentos através dos quais é possível a obtenção de finalidades práticas ou a produção de objetos; técnica. Obra de arte é uma obra criada ou avaliada por sua função artística ao invés de prática. O livro Apprenticeship Patterns compartilha soluções para os dilemas pessoais relativos a moral e motivação que muitas vezes são enfrentados por desenvolvedores de software. Para o dilema "Artesanato acima da Arte" o problema é descrito da seguinte maneira: "Embora haja uma solução comprovada disponível, o problema do seu cliente representa um oportunidade de fazer algo verdadeiramente fantástico, proporcionando a você a oportunidade de criar algo lindo que vai impressionar seus colegas.". Já a solução descrita para este dilema: "O artesanato se baseia em relacionamentos sólidos. Concentre-se em entregar valor ao seu cliente acima de defender seus próprios interesses. Como artesão, você está construindo principalmente algo que atende às necessidades dos outros, não entregando-se à expressão artística. Afinal, não existe artesão faminto." e por fim citam seu amigo Laurent Bossavit que afirmou: “Para um artesão morrer de fome é um fracasso; ele deveria ganhar a vida em seu ofício.”. Ora, parece claro que o debate do artesanato de software sob a ótica de produção de obras de arte é inócuo e também deve ser superado.

### Porque isso importa?

São dois equívocos que embora simples acabam por atrapalhar a real importância deste debate. Então em qual âmbito deve-se debater o artesanato de software e o porque esta discussão tem relevância? Acredito que devemos debater os possíveis benefícios ou malefícios desse tipo de abordagem de desenvolvimento de software pode trazer para os desenvolvedores, clientes e a industria como um todo. Em um mercado em que, em sua maioria, ainda trata muitas vezes o desenvolvedor de software como um mero "recurso" e a demanda por eles cresce de forma exponencialmente maior do que sua oferta, necessitamos de um debate mais sério e profundo sobre diferentes abordagens que visam melhorar a qualidade, tanto do trabalho produzido quanto do trabalho como forma de realização e satisfação pessoal do desenvolvedor. Essa escassez de mão-de-obra exerce uma enorme pressão para que sejam formados profissionais em um espaço cada vez mais curto de tempo, afetando de forma catastrófica o desenvolvimento de suas habilidades profissionais. O artesanato de software se propõe em ajudar a resolver, pelo menos em parte, alguns desses problemas pois ele ajuda a trazer ao centro do debate muitas das práticas artesanais que já exercemos hoje mesmo que você não simpatize com o termo artesanato.

Para encerrar gostaria de indicar alguns livros sobre o assunto para quem deseja ir além:

The Software Craftsman: Professionalism, Pragmatism, Pride - Sandro Mancuso  
Apprenticeship Patterns: Guidance for the Aspiring Software Craftsman - Dave Hoover  
Software Craftsmanship: The New Imperative - Mike Hendrickson  
The Craftsman - Richard Sennett  

---

>## **Manifesto for Software Craftsmanship - Ampliando fronteiras:**
>
>Como aspirantes a verdadeiros Artesãos de Software, estamos ampliando as fronteiras da qualidade no desenvolvimento profissional de programas de computadores através da prática e ensinando outros a aprender nossa arte. Graças a esse trabalho, valorizamos:
>
>### Não apenas software em funcionamento, **mas software de excelente qualidade**
>
>### Não apenas responder a mudanças, **mas agregar valor de forma constante e crescente**
>
>### Não apenas indivíduos e suas interações, **mas uma comunidade de profissionais**
>
>### Não apenas a colaboração do cliente, **mas parcerias produtivas**
>
>Sendo assim descobrimos, que para atingir os objetivos à esquerda, os que estão à direita são indispensáveis.
>
>*© 2009, os assinantes.Este [manifesto](http://manifesto.softwarecraftsmanship.org/#/pt-br) pode ser livremente copiado em qualquer formato, mas apenas integralmente, incluindo essa observação.*
> 

---
### Fontes:
[1] O artista e o artesão, Mario de Andrade - [link](http://www.usp.br/cje/depaula/wp-content/uploads/2017/03/O-Artista-e-o-Artes%C3%A3o_M%C3%A1rio-de-Andrade-ilovepdf-compressed.pdf)  
[2] Software Craftsmanship, Wikipedia - [link](https://en.wikipedia.org/wiki/Software_craftsmanship)  
[3] Apprenticeship Patterns, Dave H. Hoover e Adewale Oshineye - [link](https://www.amazon.com.br/Apprenticeship-Patterns-Dave-Hoover/dp/0596518382)  
[4] Programming is not a craft, Dan North - [link](https://dannorth.net/2011/01/11/programming-is-not-a-craft/)  
[5] Science as a Craft Industry, Dyson Freeman - [link](https://science.sciencemag.org/content/280/5366/1014.full?view=full)  

