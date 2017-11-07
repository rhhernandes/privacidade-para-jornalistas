---
title: 'Divulgar a chave pública PGP na internet'
metadata:
    author: 'Raphael Hernandes'
    description: 'A terceira parte da série de guias mostra como publicar a chave pública PGP na internet, inclusive no Twitter'
    'og:title': 'Publicar a chave pública PGP na Internet | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'A terceira parte da série de guias mostra como publicar a chave pública PGP na internet, inclusive no Twitter'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/05.divulgar-chave-publica-PGP/twatter-add-sks-url.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Publicar a chave pública PGP na Internet | Privacidade para Jornalistas'
    'twitter:description': 'A terceira parte da série de guias mostra como publicar a chave pública PGP na internet, inclusive no Twitter'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/05.divulgar-chave-publica-PGP/twatter-add-sks-url.png'
taxonomy:
    category:
        - pgp
    tag:
        - windows
body_classes: publishing-the-private-key
---

# Divulgar a chave pública PGP na internet

[TOC]

O próximo passo é fazer o upload de sua chave pública PGP na internet em um local a que todos tenham acesso, de modo que possam enviar mensagens criptografadas para você. Ela deverá ter também uma URL para download, assim poderá ser encontrada e verificada facilmente.

Ao fim deste guia você terá sua chave PGP pública disponível na internet. Além disso, seu perfil no Twitter e assinatura também terão a URL para a chave.

!!!! O PGP funciona com duas chaves. Uma pública e outra privada. Como se fosse um baú com duas chaves, uma delas para trancar as coisas lá dentro e outra para destrancar. Se alguém quer enviar algo para você, terá que usar a primeira, e deverá ter uma cópia dela para isso. Como o que tem dentro do baú só interessa a você, a chave que abre a tranca é privada.

Este tutorial é a terceira parte de uma série com quatro guias o uso do PGP para criptografar emails. Veja informações sobre a série completa na tabela:

| Etapa | Nome | Descrição |
| ---- | --------------- | ----------- |
| 1 | [**Como gerar chaves PGP**](../criar-chaves-pgp-windows) | A primeira parte da série mostra a instalação e o processo de gerar uma chave PGP no Windows |
| 2 | [**Como configurar o Thunderbird e PGP**](../configurar-thunderbird-pgp) |  A segunda parte guia você na instalação e configuração do Mozilla Thunderbird como gerenciador de emails para enviar e receber mensagens encriptadas |
| 3 | [**Como publicar sua chave pública PGP na Internet**](../divulgar-chave-publica-PGP) | A terceira parte da série mostra como você pode divulgar a parte pública da sua chave na internet, inclusive na sua conta  no Twitter |
| 4 | [**Como enviar email criptografados usando PGP**](../enviar-emails-criptografados-com-PGP) | Na última parte da série, ajudaremos você a enviar e a receber seu primeiro email encriptado |

## Exportar a PGP Fingerprint

O primeiro passo é exportar a fingerprint da sua chave PGP. Ela permite que qualquer um verifique que a chave divulgada é autêntica.

* Abra o **Kleopatra**

![Kleopatra Main Window](kleopatra-main-window.png?lightbox=1024&cropResize=600,600)

* Clique no seu par de chaves com o botão direito do mouse e selecione _'Certificate Details'_

![Kleopatra Getting Info](kleopatra-getting-info.png?lightbox=1024&cropResize=600,600)

* Copie sua fingerprint (é uma lista longa de letras e números)

![Copy Fingerprint to Pasteboard](kleopatra-copy-fingerprint.png?lightbox=1024&cropResize=600,600)

* Abra o **Bloco de notas** e cole a informação lá

![Fingerprint in Notepad](notepad-copy-paste-fingerprint-no-spaces.png?lightbox=1024&cropResize=600,600)

* Adicione um espaço a cada quatro caracteres para deixar a fingerprint mais legível

![Fingerprint in Notepad](notepad-copy-paste-fingerprint.png?lightbox=1024&cropResize=600,600)

## Exportar a chave PGP pública 

Embora já tenhamos exportado a chave pública em outro guia, podemos agora ver esse processo com mais detalhes. Sinta-se livre para pular direto para a próxima parte do guia se você já exportou a chave.

* Volte para o **Kleopatra** e clique novamente com o botão direito sobre a sua chave. Selecione _'Export Certificates'_ e salve sua chave pública na área de trabalho 

![Public Key in Notepad](kleopatra-export-public-key-1.png?lightbox=1024&cropResize=600,600)

![Public Key in Notepad](kleopatra-export-public-key-2.png?lightbox=1024&cropResize=600,600)

## Enviar a chave para um servidor público

Os passos a seguir mostram como você pode enviar sua chave pública PGP para um servidor. Suas fontes poderão baixar a chave desses locais.

* Abra a chave pública que exportamos antes com o **Bloco de Notas**

![Public Key in Notepad](kleopatra-export-public-key-3.png?lightbox=1024&cropResize=600,600)

* Acesse [https://sks-keyservers.net/i](https://sks-keyservers.net/i). E selecione a opção _'Submit a Key to the Server'_

![SKS Website](sks-upload-public-key-1.png?lightbox=1024&cropResize=600,600)

* Cole a chave pública na caixa, conforme mostrado na imagem. Clique no botão  _'Submit this key to the keyserver!'_ para enviar

![SKS Paste Public Key](sks-upload-public-key-2.png?lightbox=1024&cropResize=600,600)

* Se deu tudo certo, você deverá ver a mensagem a seguir

![SKS Upload Successful](sks-upload-public-key-3.png?lightbox=1024&cropResize=600,600)

## Verifique sua chave pública no servidor

Espere alguns minutos e siga os próximos passos. Vamos retirar a URL que as suas fontes podem usar para ter acesso a sua chave pública.

* Acesse [https://sks-keyservers.net/i](https://sks-keyservers.net/i) de novo e agora selecione a opção _'Extract a Key from the Server'_. Coloque seu email na caixa de busca

![SKS Search for PGP Public Key by Email](sks-verify-public-key-1.png?lightbox=1024&cropResize=600,600)

* Sua chave PGP deve aparecer nos resultados. Verifique se a fingerprint é a mesma que foi extraída anteriormente do **Kleopatra**

![SKS Search Results](sks-verify-public-key-2.png?lightbox=1024&cropResize=600,600)

* Clique no link da página de resultados, que deverá levar até a chave pública

![SKS Retrieve Public Key](sks-verify-public-key-3.png?lightbox=1024&cropResize=600,600)

* Copie a URL (**https://sks-keyservers.net/pks/lookup?op=get&search=0xA8BC95D95045977F** no meu caso). Ela que deverá ser compartilhada com os seus contatos e fontes

## Publicar a URL e fingerprint no Twitter

Acesse seu perfil no Twitter para publicar a URL e a fingerprint PGP na sua descrição.

* Adicione a URL à descrição conforme mostrado

![Twitter Add URL to Bio](twatter-add-sks-url.png?lightbox=1024&cropResize=600,600)

* Copie os últimos 16 dígitos da sua fingerprint e adicone eles à descrição também

![Twitter Add Fingerprint to Bio](twatter-add-fingerprint.png?lightbox=1024&cropResize=600,600)

* Salve os resultados, seu perfil deverá ter os detalhes necessários para recuperar e verificar sua chave PGP pública

![Twitter URL and Fingerprint in Bio](twatter-finished-result.png?lightbox=1024&cropResize=600,600)

![Twitter URL and Fingerprint in Bio](twatter-published-profile.png?lightbox=1024&cropResize=600,600)

## Publicar a URL e fingerprint na assinatura do email

Edite sua assinatura do email para ter tanto a URL para download da chave e a assinatura PGP.

![Thunderbird Email Signature](thunderbird-signature.png?lightbox=1024&cropResize=600,600)

Sinta-se livre para compartilhar essas duas informações em qualquer outro lugar para que outras pessoas possam entrar em contato com você de maneira segura.

No próximo guia, veja como [enviar emails criptografados com PGP](../enviar-emails-criptografados-com-PGP).