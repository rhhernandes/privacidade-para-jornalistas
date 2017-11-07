---
title: 'Enviar emails criptografados com PGP'
metadata:
    author: 'Gabor Szathmari'
    description: 'A última parte da série de tutoriais te ensina a mandar e receber seu primeiro email criptografado'
    'og:title': 'Enviar emails criptografados com PGP | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'A última parte da série de tutoriais te ensina a mandar e receber seu primeiro email criptografado'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/06.enviar-emails-criptografados-com-PGP/retrieve-public-key.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@gszathmari'
    'twitter:title': 'Enviar emails criptografados com PGP | Privacidade para Jornalistas'
    'twitter:description': 'A última parte da série de tutoriais te ensina a mandar e receber seu primeiro email criptografado'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/06.enviar-emails-criptografados-com-PGP/retrieve-public-key.png'
taxonomy:
    category:
        - pgp
    tag:
        - windows
---

# Enviar emails criptografados com PGP

[TOC]

Com chaves PGP criadas e divulgadas e com o Thunderbird pronto para ser usado, o último passo é importar a chave pública de alguém para que seja possível enviar emails criptografados para essa pessoa. Ao fim desse guia você poderá enviar emails criptografados para alguém.

Este tutorial é a quarta parte de uma série com quatro guias o uso do PGP para criptografar emails. Veja informações sobre a série completa na tabela:

| Etapa | Nome | Descrição |
| ---- | --------------- | ----------- |
| 1 | [**Como gerar chaves PGP**](../criar-chaves-pgp-windows) | A primeira parte da série mostra a instalação e o processo de gerar uma chave PGP no Windows |
| 2 | [**Como configurar o Thunderbird e PGP**](../configurar-thunderbird-pgp) |  A segunda parte guia você na instalação e configuração do Mozilla Thunderbird como gerenciador de emails para enviar e receber mensagens encriptadas |
| 3 | [**Como publicar sua chave pública PGP na Internet**](../divulgar-chave-publica-PGP) | A terceira parte da série mostra como você pode divulgar a parte pública da sua chave na internet, inclusive na sua conta  no Twitter |
| 4 | [**Como enviar email criptografados usando PGP**](../enviar-emails-criptografados-com-PGP) | Na última parte da série, ajudaremos você a enviar e a receber seu primeiro email encriptado |

## Encontrar uma chave pública PGP

O primeiro passo é conseguir a chave pública PGP de alguém da internet. No meu caso, estou baixando a chave de **https://keybase.io/gszathmari/key.asc**

![Retrieve Public Key](retrieve-public-key.png?lightbox=1024&cropResize=600,600)

* Salve a chave pública num arquivo de texto

![Save Public Key](save-public-key-in-text-file.png?lightbox=1024&cropResize=600,600)

* Abra o **Kleopatra** e clique no botão _'Import Certificates'_

![Kleopatra Import Certificates](kleopatra-main-window.png?lightbox=1024&cropResize=600,600)

* Selecione o arquivo de texto que acabamos de salvar

![Kleopatra Select Public Key](kleopatra-import-public-key.png?lightbox=1024&cropResize=600,600)

![Kleopatra Select Public Key](kleopatra-import-successful.png?lightbox=1024&cropResize=600,600)

* Volte para a janela principal do **Kleopatra** e abra a aba _'Imported Certificates'_

![Kleopatra Imported Certificates](kleopatra-main-window-2.png?lightbox=1024&cropResize=600,600)

* Clique duas vezes num certificado para mudar as preferências. Selecione _'Trust Certifications Made by This Certificate ...'_

![Kleopatra Trusts](kleopatra-key-properties.png?lightbox=1024&cropResize=600,600)

* Mude o nível de confiança de _'I do not know'_ para _'I believe checks are casual'_

![Kleopatra Change Trust Level](kleopatra-set-trust-level.png?lightbox=1024&cropResize=600,600)

![Kleopatra Change Trust Level](kleopatra-set-trust-level-1.png?lightbox=1024&cropResize=600,600)

![Kleopatra Change Trust Level](kleopatra-set-trust-level-2.png?lightbox=1024&cropResize=600,600)

## Escreva um email criptografado

Como agora você tem a chave pública do seu destinatário, você pode enviar o primeiro email criptografado para essa pessoa.

* Escreva a mensagem como sempre e depois clique no ícone de cadiado no topo da tela para criptografar o email

![Kleopatra Change Trust Level](thunderbird-encrypt-email.png?lightbox=1024&cropResize=600,600)

* Você deverá digitar sua senha antes que o email seja criptografado e enviado

![Kleopatra Change Trust Level](thunderbird-encrypt-email-2.png?lightbox=1024&cropResize=600,600)

* O email deverá ser enviado num formato criprografado. O email bruto deverá se parecer com o seguinte:

![The Encrypted Email](encrypted-email.png?lightbox=1024&cropResize=600,600)

* O destinatário receberá  os indicadores a seguir se ele tiver a sua chave pública importada no sistema dele

![Email Recipient](recipient-side-2.png?lightbox=1024&cropResize=600,600)

* O email poderá ser aberto e lido mesmo se ele não tiver a sua chave

![Email Recipient](recipient-side-1.png?lightbox=1024&cropResize=600,600)

Feito! Você está pronto para enviar e receber emails criptografados.

! Tenha em mente que metadados ficam gravados nos provedores por um ano no Brasil. Isso significa que seráo gravados endereços de IP, o tamanho da mensagem e de anexos além do endereço de email do remetente e do destinatário. **Em outras palavras, apesar de não ser possível descobrir o conteúdo das conversas, será possível fazer uma conexão entre você e quem é sua fonte.** Se isso é uma questão para você, veja [guias sobre programas que não deixam metadados](../)