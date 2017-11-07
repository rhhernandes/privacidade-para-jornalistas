---
title: 'Configurar Thunderbird e PGP'
metadata:
    author: 'Raphael Hernandes'
    description: 'A segunda parte da série de guias mostra como ensinar e configurar o Mozilla Thunderbird para enviar e receber emails criptografados'
    'og:title': 'Configurar o Thunderbird e PGP | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'A segunda parte da série de guias mostra como ensinar e configurar o Mozilla Thunderbird para enviar e receber emails criptografados'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/04.configurar-thunderbird-pgp/thunderbird-signed-2.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Configurar o Thunderbird e PGP | Privacidade para Jornalistas'
    'twitter:description': 'A segunda parte da série de guias mostra como ensinar e configurar o Mozilla Thunderbird para enviar e receber emails criptografados'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/04.configurar-thunderbird-pgp/thunderbird-signed-2.png'
taxonomy:
    category:
        - pgp
    tag:
        - windows
        - email
        - criptografia
---

# Configurar Thunderbird e PGP

[TOC]

Assim que você terminar de [criar chaves PGP](../criar-chaves-pgp-windows), será necessário configurar um programa de emails para usá-la. 

Ao fim deste guia, você poderia enviar e receber emails criptografados.

Este tutorial é a segunda parte de uma série com quatro guias o uso do PGP para criptografar emails. Veja informações sobre a série completa na tabela:

| Etapa | Nome | Descrição |
| ---- | --------------- | ----------- |
| 1 | [**Como gerar chaves PGP**](../criar-chaves-pgp-windows) | A primeira parte da série mostra a instalação e o processo de gerar uma chave PGP no Windows |
| 2 | [**Como configurar o Thunderbird e PGP**](../configurar-thunderbird-pgp) |  A segunda parte guia você na instalação e configuração do Mozilla Thunderbird como gerenciador de emails para enviar e receber mensagens encriptadas |
| 3 | [**Como publicar sua chave pública PGP na Internet**](../divulgar-chave-publica-PGP) | A terceira parte da série mostra como você pode divulgar a parte pública da sua chave na internet, inclusive na sua conta  no Twitter |
| 4 | [**Como enviar email criptografados usando PGP**](../enviar-emails-criptografados-com-PGP) | Na última parte da série, ajudaremos você a enviar e a receber seu primeiro email encriptado |

## Instalar o Mozilla Thunderbird

* Acesse [https://www.mozilla.org/en-GB/thunderbird/](https://www.mozilla.org/en-GB/thunderbird/) para baixar o Mozilla Thunderbird _(é grátis)_

![Mozilla Thunderbird home page](thunderbird-home.png?lightbox=1024&cropResize=600,600)

* Abra o arquivo baixado e instale o programa

![Installing Mozilla Thunderbird](thunderbird-install-1.png?lightbox=1024&cropResize=600,600)

![Installing Mozilla Thunderbird](thunderbird-install-2.png?lightbox=1024&cropResize=600,600)

![Installing Mozilla Thunderbird](thunderbird-install-2.png?lightbox=1024&cropResize=600,600)

![Installing Mozilla Thunderbird](thunderbird-install-2.png?lightbox=1024&cropResize=600,600)

## Configurar o Mozilla Thunderbird

Depois que o Thunderbird for instalado, abra-o. Você deverá fornecer alguns detalhes a respeito do seu provedor de email (Gmail, por exemplo). Talvez você precise descobrir as informações de **POP** e de **IMAP** do provedor --normalmente ficam na parte de configurações e parecem com a URL de um site. 

* O Thunderbird deverá abrir já com a janela de configuração. Selecione _'Skip this and use my existing email_.

![Mozilla Thunderbird Configuration Wizard](thunderbird-configure-1.png?lightbox=1024&cropResize=600,600)

* Uma janela deverá abrir para você inserir seu endereço de email e senha. O Thunderbird irá tentar adivinhar as configurações necessárias.

![Mozilla Thunderbird Configuration Wizard](thunderbird-configure-a.png?lightbox=1024&cropResize=600,600)

* Se ele não conseguir, você precisará colocar as configurações de **POP** e de **IMAP** manualmente.

![Mozilla Thunderbird Configuration Wizard](thunderbird-configure-2.png?lightbox=1024&cropResize=600,600)

* Se deu tudo certo, o Thunderbird já deverá ser capaz de se conectar ao seu email para enviar e receber mensagens.

![Mozilla Thunderbird Configuration Wizard](thunderbird-configure-3.png?lightbox=1024&cropResize=600,600)

## Configurar o Enigmail

Enigmail é uma extensão que conecta o Thunderbird ao Gpg4Win.

* Clique no ícone de hambúrguer no topo direito da tela e selecione _'Add-ons'_

![Opening Thunderbird Add-ons](enigmail-configure-1.png?lightbox=1024&cropResize=600,600)

* Digite _'Enigmail'_ na caixa de busca e aperte enter. O primeiro resultado deverá ser o plugin Enigmail. Clique em _'Install'_.

![Opening Thunderbird Add-ons](enigmail-configure-2.png?lightbox=1024&cropResize=600,600)

![Installing Enigmail](enigmail-configure-3.png?lightbox=1024&cropResize=600,600)

* Quando o Enigmail for instalado, clique _'Restart Now'_ para ativar o plugin.

![Installing Enigmail](enigmail-configure-4.png?lightbox=1024&cropResize=600,600)

* Quando o Thunderbird abrir de novo, o Enigmail deverá mandar uma mensagem com informações ara configuração. Clique em _'Next'_ na primeira tela.

![Enigmail Wizard](enigmail-wizard-1.png?lightbox=1024&cropResize=600,600)

* Não mude as configurações básicas e clique em _'Next'_.

![Enigmail Wizard](enigmail-wizard-2.png?lightbox=1024&cropResize=600,600)

* A página seguinte deverá mostrar o [par de chaves PGP que criamos](../criar-chaves-pgp-windows) mais cedo. Certifique-se de que a chave correta está selecionada e clique em _'Next'_

![Enigmail Wizard](enigmail-wizard-3.png?lightbox=1024&cropResize=600,600)

![Enigmail Wizard](enigmail-wizard-4.png?lightbox=1024&cropResize=600,600)

## Testar o PGP

Para testasr se tudo está funcionando, normalmente o procedimento é enviar um email assinado digitalmente (não criptografado).

!!!! Além de criptografar emails, o PGP serve para certificar (assinar digitalmente) que a pessoa que envia realmente é quem diz ser

* Escreva um email como de costume. Aperte no ícone de lápis na barra do Enigmail para assinar a sua mensagem e clique em _'Send'_

![New Signed Email](thunderbird-signed-1.png?lightbox=1024&cropResize=600,600)

* Digite sua senha para assinar a mensagem

![New Signed Email](thunderbird-signed-2.png?lightbox=1024&cropResize=600,600)

* O destinatário poderá ver que a mensagem foi assinada digitalmente

![Signed Email at Recipient](thunderbird-signed-3.png?lightbox=1024&cropResize=600,600)

!!! O destinatário precisa importar sua chave pública no computador dele para poder verificar a autenticidade da sua assinatura digital

Na próxima seção veremos como [divulgar a sua chave pública](../divulgar-chave-publica-PGP) na internet para que outras pessoas possam verificar sua assinatura digital e trocar emails criptografados com você.