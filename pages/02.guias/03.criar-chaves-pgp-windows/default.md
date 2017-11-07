---
title: 'Criar chaves PGP no Windows'
metadata:
    author: 'Raphael Hernandes'
    description: 'A primeira parte da série mostra o processo de instalação e de geração de chaves PGP no Windows'
    'og:title': 'Criar chaves PGP no Windows | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'A primeira parte da série mostra o processo de instalação e de geração de chaves PGP no Windows'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/03.criar-chaves-pgp-windows/kleopatra-export-public-keys-1.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Criar chaves PGP no Windows | Privacidade para Jornalistas'
    'twitter:description': 'A primeira parte da série mostra o processo de instalação e de geração de chaves PGP no Windows'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/03.criar-chaves-pgp-windows/kleopatra-export-public-keys-1.png'
taxonomy:
    category:
        - pgp
    tag:
        - windows
---

# Gerar chaves PGP no Windows

[TOC]

O guia a seguir mostra instruções detalhadas de como gerar um par de chaves PGP (privacidade muito boa, da sigla em inglês) para enviar e receber emails encriptados.

Ao fim deste passo a passo, você terá uma chave PGP pública e uma privada no seu computador.

Este tutorial é a primeira parte de uma série com quatro guias o uso do PGP para criptografar emails. Veja informações sobre a série completa na tabela:

| Etapa | Nome | Descrição |
| ---- | --------------- | ----------- |
| 1 | [**Como gerar chaves PGP**](../criar-chaves-pgp-windows) | A primeira parte da série mostra a instalação e o processo de gerar uma chave PGP no Windows |
| 2 | [**Como configurar o Thunderbird e PGP**](../configurar-thunderbird-pgp) |  A segunda parte guia você na instalação e configuração do Mozilla Thunderbird como gerenciador de emails para enviar e receber mensagens encriptadas |
| 3 | [**Como publicar sua chave pública PGP na Internet**](../divulgar-chave-publica-PGP) | A terceira parte da série mostra como você pode divulgar a parte pública da sua chave na internet, inclusive na sua conta  no Twitter |
| 4 | [**Como enviar email criptografados usando PGP**](../enviar-emails-criptografados-com-PGP) | Na última parte da série, ajudaremos você a enviar e a receber seu primeiro email encriptado |

## Instalar Gpg4Win

* Baixe o **Gpg4Win** de [www.gpg4win.org](https://www.gpg4win.org)

![Gpg4Win home page](gpg-windows-gpg4win-2.png?lightbox=1024&cropResize=600,600)

![Gpg4Win home page](gpg-windows-gpg4win-1.png?lightbox=1024&cropResize=600,600)

* Clique no arquivo baixado para iniciar a instalação

![Installing Gpg4Win](gpg-windows-gpg4win-3.png?lightbox=1024&cropResize=600,600)

* No menu iniciar, abra o programa **Kleopatra**

![Launching Kleopatra](kleopatra-start-menu.png?lightbox=1024&cropResize=600,600)

* Kleopatra é um programa gerenciador de chaves PGP. A janela principal deverá se parecer com a seguinte:

![Kleopatra main window](kleopatra-main-window.png?lightbox=1024&cropResize=600,600)

## Gerar um par de chaves PGP

Uma vez que o **Gpg4Win** estiver instalado e o **Kleopatra** aberto, podemos gerar o primeiro par de chaves PGP

* Clique em **File => New Certificate**

![Generate new certificate](kleopatra-main-window-new-keychain.png?lightbox=1024&cropResize=600,600)

* Selecione a opção _'Create a personal OpenPGP key pair'_ 

![Generate new certificate](kleopatra-main-window-personal.png?lightbox=1024&cropResize=600,600)

* Insira seu nome e email no formulário

![Entering details](kleopatra-enter-details.png?lightbox=1024&cropResize=600,600)

* Revise as informações e clique em _'Create Key'_ 

![Reviewing settings](kleopatra-review-details.png?lightbox=1024&cropResize=600,600)

* Agora crie uma senha forte. Isso vai proteger a sua chave privada no seu computador com criptografia

!! **Aviso: Nunca use a mesma senha em mais de um lugar**  
!! Escolha uma senha que você nunca usou em qualquer outro lugar

![Entering a strong passphrase](kleopatra-passphrase.png?lightbox=1024&cropResize=600,600)

* Se der tudo certo, você deverá ver as seguintes opções

![Key generation is ready](kleopatra-key-generated.png?lightbox=1024&cropResize=600,600)

* Clique em _'Finish'_ para finalizar o processo

## Configurando uma data de validade para as chaves

Agora iremos configurar um prazo de validade para as chaves geradas. É uma boa prática porque, se a sua chave for comprometidad e alguma forma sem que você saiba, o estrago seria limitado.

* Abra o **Kleopatra** 

![Kleopatra main window](kleopatra-main-with-key.png?lightbox=1024&cropResize=600,600)

* Clique com o botão direito no seu par de chaves PGP e selecione _'Change Expiry Date...'_

![Changing expiry date](kleopatra-set-expiry-menu.png?lightbox=1024&cropResize=600,600)

* Selecione *2 Years* como o tempo desejado e clique em _'OK'_

![Setting expiry date](kleopatra-change-expiry-date.png?lightbox=1024&cropResize=600,600)

* Tudo pronto

![Expiry date is set](kleopatra-expiry-date-successful.png?lightbox=1024&cropResize=600,600)

## Fazer o backup do par de chaves PGP

É importante criar uma cópia das chaves. Isso garante que você pode restaurar o par de chaves PGP e acessar emails encriptados caso o seu computador tenha algum problema ou seja roubado.

* Clique com o botão direito no par de chaves e selecione _'Export Secret Keys...'_

![Exporting Secret Key](kleopatra-export-secret-keys.png?lightbox=1024&cropResize=600,600)

* Escolha um nome para o arquivo e onde será salvo o backup. Selecione a caixa _'ASCII armor'_

![Exporting Secret Key](kleopatra-export-secret-keys-2.png?lightbox=1024&cropResize=600,600)

![Exporting Secret Key](kleopatra-export-secret-keys-3.png?lightbox=1024&cropResize=600,600)

* A chave será salva num arquivo

Agora faça um backup da chave pública

* Clique com o botão direito nas chaves e selecione _'Export Certificates ...'_

![Exporting Public Key](kleopatra-export-public-keys-1.png?lightbox=1024&cropResize=600,600)

![Exporting Public Key](kleopatra-export-public-keys-2.png?lightbox=1024&cropResize=600,600)

Pegue ambos os arquivos (chaves pública e privada) e copie para outro lugar. Pode ser um pen drive, uma pasta no Dropbox ou até imprimir" 

!!! É seguro guardar a chave privada em lugares diferentes porque ela é criptografada com a senha que selecionamos no início. Em outras palavras, ela não pode ser recuperada sem colocar a senha antes.

Vá para o próximo passo e [configure o Thunderbird](../configurar-thunderbird-pgp) para enviar e receber emails criptografados com PGP.
