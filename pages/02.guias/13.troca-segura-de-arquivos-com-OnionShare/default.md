---
title: 'Troca segura de arquivos com OnionShare'
metadata:
    author: 'Raphael Hernandes'
    description: 'Este guia ensina a instalar o OnionShare, que compartilha arquivos de maneira segura, sem deixar metadados'
    'og:title': 'Troca segura de arquivos com OnionShare | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Este guia ensina a instalar o OnionShare, que compartilha arquivos de maneira segura, sem deixar metadados'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/02.troca-segura-de-arquivos-com-OnionShare/tor-download-file-1.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Troca segura de arquivos com OnionShare | Privacidade para Jornalistas'
    'twitter:description': 'Este guia ensina a instalar o OnionShare, que compartilha arquivos de maneira segura, sem deixar metadados'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/02.troca-segura-de-arquivos-com-OnionShare/tor-download-file-1.png'
taxonomy:
    category:
        - 'file exchange'
    tag:
        - windows
        - 'no metadata'
---

# Troca segura de arquivos com OnionShare

[TOC]

Toda vez que um arquivo é compartilhado na internet por meio de serviçõs como emails, Dropbox ou outras formas de transferências de mensageiros instantâneos, metadados são deixados e eles poder servir para ligar o jornalista à sua fonte.

[OnionShare](https://onionshare.org?target=_blank) foi desenvolvido para simplificar e proteger as trocas de arquivos, deixando o menor número possível de metadados. Ele opera na rede Tor e conecta as duas pessoas sem nenhum servidor central no meio. Isso significa que, uma vez que o arquivo é transferido e o programa é fechado, não fica nenhum registro nos provedores.

No fim desse guia, você poderá usar o OnionShare para compartilhar arquivos de forma segura. 

## Baixar o OnionShare

* Acesse [https://onionshare.org](https://onionshare.org?target=_blank) para baixar a versão mais recente do software

![OnionShare Home Page](download-onionshare.png?lightbox=1024&cropResize=600,600)

* Instale **OnionShare** como qualquer outro programa

![Installing OnionShare](install-onionshare-1.png?lightbox=1024&cropResize=600,600)

![Installing OnionShare](install-onionshare-2.png?lightbox=1024&cropResize=600,600)

![Installing OnionShare](install-onionshare-3.png?lightbox=1024&cropResize=600,600)

## Instalar o navegador Tor

OnionShare precisa do navegador **Tor** para funcionar. Siga as instruções abaixo e faça a instalação.

* Baixe o **Tor** no site [Tor Project](https://www.torproject.org/projects/torbrowser.html.en?target=_blank)

![Downloading Tor Browser](download-tor-browser-1.png?lightbox=1024&cropResize=600,600)

![Downloading Tor Browser](download-tor-browser-2.png?lightbox=1024&cropResize=600,600)

* Instale o **Tor** seguindo as imagens abaixo

![Installing Tor Browser](install-tor-browser-1.png?lightbox=1024&cropResize=600,600)

![Installing Tor Browser](install-tor-browser-2.png?lightbox=1024&cropResize=600,600)

![Installing Tor Browser](install-tor-browser-3.png?lightbox=1024&cropResize=600,600)

![Installing Tor Browser](install-tor-browser-4.png?lightbox=1024&cropResize=600,600)

## Rodar o navegador Tor

* Abra o **Tor** e deixe-o rodando em segundo plano

![Running Tor Browser](tor-connect-1.png?lightbox=1024&cropResize=600,600)

![Running Tor Browser](tor-connect-2.png?lightbox=1024&cropResize=600,600)

![Running Tor Browser](tor-connect-3.png?lightbox=1024&cropResize=600,600)

## Compartilhar um arquivo com OnionShare

Enquanto o **Tor** está aberto em segundo plano, abra o **Onionshare**. Vamos compartilhar um arquivo de exemplo chamado _Super Secret File.txt_ na rede Tor.

* Abra o **OnionShare**

![Sharing a File with OnionShare](onionshare-share-file-1.png?lightbox=1024&cropResize=600,600)

* Arraste o arquivo (ou arquivos) para a janela principal do **OnionShare**

![Sharing a File with OnionShare](onionshare-share-file-2.png?lightbox=1024&cropResize=600,600)

* Agora aperte o botão _'Start Sharing'_. Pode demorar um pouco até o arquivo estar disponível na rede Tor

![Sharing a File with OnionShare](onionshare-share-file-3.png?lightbox=1024&cropResize=600,600)

* Uma vez que ele estiver disponível, o indicador ficará verde e um link aparecerá

![Sharing a File with OnionShare](onionshare-share-file-4.png?lightbox=1024&cropResize=600,600)

O arquivo compartilhado agora está disponível numa URL secreta. Ela não vai funcionar em navegadores normals, portanto a outra pessoa deverá usar o navegador **Tor** para acessar o arquivo.

!!! Compartilhe o link com a outra pessoa usando [chat](https://privacidadeparajornalistas.org/guias#chat) ou [email encriptados](https://privacidadeparajornalistas.org/guias#seguranca-de-email)

## Baixar arquivos compartilhados com OnionShare

Esta seção mostra como a outra parte pode baixar o arquivo compartilhado pelo link secreto.

* Abra o navegador **Tor**

![Downloading a File with the Tor Browser](tor-download-file-1.png?lightbox=1024&cropResize=600,600)

* Cole o link secreto na barra de URL

![Downloading a File with the Tor Browser](tor-download-file-2.png?lightbox=1024&cropResize=600,600)

* Salve o arquivo no HD

![Downloading a File with the Tor Browser](tor-download-file-3.png?lightbox=1024&cropResize=600,600)

![Downloading a File with the Tor Browser](tor-download-file-4.png?lightbox=1024&cropResize=600,600)

![Downloading a File with the Tor Browser](tor-download-file-5.png?lightbox=1024&cropResize=600,600)

* Descompacte e abra o arquivo

![Opening the Downloaded File](tor-open-file-1.png?lightbox=1024&cropResize=600,600)

![Opening the Downloaded File](tor-open-file-2.png?lightbox=1024&cropResize=600,600)

![Opening the Downloaded File](tor-open-file-3.png?lightbox=1024&cropResize=600,600)

![Opening the Downloaded File](tor-open-file-4.png?lightbox=1024&cropResize=600,600)

![Opening the Downloaded File](tor-open-file-5.png?lightbox=1024&cropResize=600,600)

* A pessoa que fez o envio pelo **OnionShare** recebe uma notificação dizendo que o arquivo foi baixado

![Shared File is Downloaded](onionshare-share-file-finished.png?lightbox=1024&cropResize=600,600)
