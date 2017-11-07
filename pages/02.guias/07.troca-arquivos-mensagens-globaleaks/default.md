---
title: 'Trocas de arquivos e de mensagens com o GlobaLeaks'
metadata:
    author: 'Raphael Hernandes'
    description: 'Este guia fala sobre o uso do GlobaLeaks por jornalistas para compartilhar informações de maneira segura com fontes'
    'og:title': 'Trocas de arquivos e mensagens com o GlobaLeaks | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Este guia fala sobre o uso do GlobaLeaks por jornalistas para compartilhar informações de maneira segura com fontes'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/07.troca-arquivos-mensagens-globaleaks/reporter-4.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Trocas de arquivos e mensagens com o GlobaLeaks | Privacidade para Jornalistas'
    'twitter:description': 'Este guia fala sobre o uso do GlobalLeaks por jornalistas para compartilhar informações de maneira segura com fontes'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/07.troca-arquivos-mensagens-globaleaks/reporter-4.png'
---

# Trocas de arquivos e de mensagens com o GlobaLeaks

[TOC]

Toda vez que um arquivo é compartilhado na internet por serviços como emails, Dropbox ou mensageiros instantâneos, metadados ficam espalhados e podem ser usados para ligar o jornalista às pessoas com quem ele interagiu --e, com isso, descobrir suas fontes.

Falamos sobre o [OnionShare](../troca-segura-de-arquivos-com-onionshare), uma solução simples para trocas seguras de arquivos. Como o OnionShare não tem um serviço de chat, você precisa usar o [Ricochet](../conversas-seguras-com-ricochet) paralelamente. No entanto, às vezes é necessário ter os dois serviços num lugar só.

[GlobaLeaks](https://www.globaleaks.org/?target=_blank) é uma plataforma segura que simplifica o processo. Ele é rodado em um serviço Tor, que conecta o jornalista à suas fontes. Os arquivos e mensagens só ficam disponíveis para você. Além disso, tudo é criptografado com [PGP](/guias#seguranca-de-email), então ninguém além de você consegue abrir o conteúdo.

O GlobaLeaks, junto com outra plataforma popular, chamada de [SecureDrop](https://securedrop.org/?target=_blank), é usado por [várias empresas de mídia](https://en.wikipedia.org/wiki/GlobaLeaks#Implementations?target=_blank) no mundo todo.

O guia a seguir mostra como uma fonte pode enviar arquivos e mensagens por meio desse serviço e como o jornalista pode ter acesso ao conteúdo.

!!! Precisa de ajuda com o GlobaLeaks? [Entre em contato conosco](mailto:contato@privacidadeparajornalistas.org)

## Enviar arquivos como uma fonte

* A fonte acessa a URL **.onion** do GlobalLeaks usando o navegador Tor. A URL deve ser compartilhada com a fonte previamente, no site da empresa, por exemplo

![Visiting the .onion URL as a source](submission-1.png?lightbox=1024&cropResize=700,700)

* A fonte aperta o botão no meio e a página a seguir aparecerá. Nela, arquivos e mensagens podem ser adicionados

![Adding files and messages](submission-2.png?lightbox=1024&cropResize=700,700)

![Adding files and messages](submission-3.png?lightbox=1024&cropResize=700,700)

* A fonte aperta o botão _'Submit'_ para enviar arquivos ao jornalista

## Acessar os arquivos como jornalista

Uma vez que os arquivos e mensagens são enviados, o jornalista recebe email _(opcional)_ criptografado com PGP com as informações.

![Email notification](reporter-1.png?lightbox=1024&cropResize=700,700)

* O jornalista deve então acessar o lugar em que os envios são listados

![Submissions](reporter-2.png?lightbox=1024&cropResize=700,700)

* O repórter então pode recuperar os arquivos e enviar mensagens para a fonte. Tudo é criptografado com PGP, então precisam ser descriptografados após serem salvos no computador

![Submission](reporter-3.png?lightbox=1024&cropResize=700,700)

![Writing a message](reporter-4.png?lightbox=1024&cropResize=700,700)

## Adicionar mais mensagens

A fonte pode entrar no sistema novamente a qualquer momento para adicionar mais arquivos e para ler ou escrever mensagens. 

* A fonte acessa o sistema com a senha para ler e escrever mensagens

![Logging in](logging-in.png?lightbox=1024&cropResize=700,700)

* A fonte responde o jornalista

![Replying to a message](submission-5.png?lightbox=1024&cropResize=700,700)

* O repórter recebe um email _(opcional)_, criptografado com PGP sobre a nova movimentação

![Email notification](reporter-5.png?lightbox=1024&cropResize=700,700)