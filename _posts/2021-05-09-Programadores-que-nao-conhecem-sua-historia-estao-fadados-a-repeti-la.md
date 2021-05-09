---
layout: post
title: Programadores que não conhecem sua história estão fadados a repeti-la
gh-repo: FabriDamazio/fabridamazio.github.io
cover-img: /assets/img/hydre.jpg
gh-badge: [star, follow]
tags: [agile], [agilidade], [artesanato]
comments: true
---

## Introdução

O tema "repetir o passado" é recorrente na história da humanidade. Frases sobre este tema são frequentemente atribuídas a filósofos, políticos e generais. Talvez a mais famosa delas seja a frase "Aqueles que não conhecem a história estão fadados a repeti-la." que é atribuída erroneamente ao filósofo irlandês Edmund Burk. Isso não quer dizer que Edmund Burk não tenha recorrido ao tema. No livro "Reflections on the Revolution in France" (1790) ele escreveu "As pessoas não serão capazes de olhar para a posteridade, se não olharem para trás para seus ancestrais" (tradução livre). Já em "The Life of Reason" (1905), o filósofo espanhol George Santayana escreveu "Aqueles que não conseguem se lembrar do passado estão condenados a repeti-lo" e que foi parafraseado por Winston Churchill que em um discurso em 1948 disse "Aqueles que falham em aprender com a história estão condenados a repeti-la.". Mas o que isso tem a ver com programação?


## Uma breve resumo da história

Não pretendo escrever a história dos programadores ou da programação aqui. Por questões práticas, prefiro indicar um vídeo porque não resumiria esta história melhor do que Uncle Bob fez em uma apresentação chamada "The Future of Agile"[1]. É uma viagem por mais de 70 anos comprimida em cerca de uma hora, vale cada minuto. Em determinada parte desta apresentação é citado o artigo "Managing the Development of Large Scale Software Systems"[2] escrito por Winston Royce. Este artigo, baseado nas lições que ele aprendeu gerenciando grandes projetos de software, continua sendo até agora a fonte mais citada do modelo em cascata (Waterfall) para desenvolvimento de softwares. Este modelo de desenvolvimento foi, por mais de 30 anos, o padrão adotado pela indústria de software. Existe farto material disponível na internet sobre todos os problemas que este modelo pode trazer, sugiro pesquisarem sobre o tema. Posso resumir que foi doloroso e horrível para todos envolvidos, especialmente para os programadores.

## O movimento Ágil: ascensão e queda

Algo estava acontecendo na indústria na segunda metade da década de 90. Diversas outras metodologias estavam surgindo e sugerindo que poderia existir um jeito melhor de desenvolver software. Em 1995 durante a OOPSLA ’95, Ken Schwaber e Jeff Sutherland apresentavam o, até então desconhecido, SCRUM (o artigo "SCRUM Development Process" foi publicado em 1997 no livro "Business Object Design and Implementation"[3]). Já 1998, Alistair Cockburn começava a dar vida a metodologia Crystal e um ano depois foi a vez de Kent Beck publicar seu livro "Extreme Programming Explained". O que todas essas novas metodologias tinham em comum? O objetivo de reagir aos "pesados" métodos utilizados. Queriam algo mais leve, mais flexível e que fosse melhor para as empresas, projetos e desenvolvedores. Em 2001, dezessete programadores se reuniram para discutir as similaridades e objetivos em comum de cada uma desses métodos e assim nasceu o tão famoso e aclamado "Manifesto para Desenvolvimento Ágil de Software"[4]. Indico um podcast onde Uncle Bob conta em detalhes toda história de como esse encontro aconteceu.[5]

Nascia então o Movimento Ágil, que trazia esperanças de um futuro melhor para o desenvolvimento de software. Após um começo entusiasmado e promissor algo parecia estar errado. Conforme o termo "Ágil" rompia barreiras uma disfunção ficou evidente. Os programadores estavam ficando de lado, para não falar de fora. Os eventos, as conferências, as certificações foram dominadas pelos então até então intitulados "Gerente de projetos" que viam no Movimento Ágil uma espécie de variação da maneira de gerenciar projetos. O movimento foi transformado em um negócio lucrativo cujo objetivo é vender treinamentos, certificações e a próxima "grande revolução" da gestão de projetos. O movimento se afastou dos programadores, do código e das práticas técnicas que tornam um time ágil. Ágil se tornou uma varição estranha de PMI, repaginado e com cara de modernidade.

“A história repete-se sempre, pelo menos duas vezes”, disse o filósofo alemão, Friedrich Hegel. Em grande parte das empresas hoje, trabalhamos utilizando uma metodologia Ágil desprovida das disciplinas e valores fundamentais para seu funcionamento (caro leitor, você se identifica?), a qual é chamada pelos criadores do movimento como Faux Agile, Scrum flácido ou Dark Scrum (pessoalmente adoro o termo brasileiríssimo "Cascágil"). Assim, a história se repete com projetos perdendo prazos, estourando orçamentos, códigos sem o mínimo de manutenabilidade e não atendendo de maneira satisfatória empresas e clientes. Fico com a frase de Ron Jeffries que resume a queda do movimento ágil: "Parte meu coração ver as ideias sobre as quais escrevemos no Manifesto Ágil usadas para tornar a vida dos desenvolvedores pior, em vez de melhor. Também me entristece que a empresa não esteja conseguindo o que poderia com o negócio, mas minha principal preocupação é com as pessoas que fazem o trabalho."[6]. Triste fim.

## O movimento do Artesanato de Software

No final do ano de 2008 um grupo de programadores voltou a se encontrar com o objetivo de, nas palavras de Uncle Bob, "continuar e expandir a mensagem do Ágil". Nasceu assim o "Manifesto for Software Craftsmanship" e seu movimento para reestabelecer as disciplinas e os valores que foram abandonados pelo movimento Ágil em prol dos lucrativos negócios de vendas de treinamento e certificações. O novo movimento não obteve uma fração da tração que obteve movimento original, mas sobrevive mesmo sobre constantes questionamentos. Muitos desses questionamentos vem pela falta de entendimento do que o movimento realmente representa, porém, isso é assunto para outra hora. Posso afirmar que se termos como TDD, Refactoring e Pair Programming fazem parte do nosso dia a dia é em grande parte a este grupo de profissionais que continuam dando relevância a valores e disciplinas que são fundamentos para o desenvolvimento ágil de software.


## Conclusão

Se a grande batalha do Ágil foi perdida, um fio de esperança de dias melhores sobrevive por meio do Software Craftsmanship. Devemos conhecer nossa história para aprender com os erros do passado e não repeti-los. O importante é entregar valor e software funcionando e isso vai de justamente de encontro com os valores originais do movimento Ágil que hoje é representado pelo Artesanato de Software. O mundo depende cada vez mais dos softwares, eles estão em todos os lugares, e cabe a nós assumirmos a responsabilidade por criar um futuro melhor para todos. 

Se você gosta do tema ou quer conversar sobre qualquer tema relacionado a programação, entre em contato comigo pelo LinkedIn ou e-mail fabridamazio@gmail.com.


## Fontes

[1] The Future of Agile - Robert C. Martin [link](https://www.youtube.com/watch?v=FedQ2NlgxMI&t=935s)  
[2] Managing the Development of Large Scale Software Systems - Wiston Royce [link](https://blog.jbrains.ca/assets/articles/royce1970.pdf)  
[3] Business Object Design and Implementation - [link](https://www.springer.com/br/book/9783540760962?utm_campaign=bookpage_about_buyonpublisherssite&utm_medium=referral&utm_source=springerlink#otherversion=9781447109471)  
[4] A Brief History of the Agile Manifesto - Retro Time Podcast com Uncle Bob - [link](https://www.retrotimepodcast.com/23-a-brief-history-of-the-agile-manifesto-with-uncle-bob-martin/)  
[5] Manifesto para Desenvolvimento Ágil de Software [link](http://agilemanifesto.org/iso/ptbr/manifesto.html)   
[6] Developers Should Abandon Agile - Ron Jeffries [link](https://ronjeffries.com/articles/018-01ff/abandon-1/) 