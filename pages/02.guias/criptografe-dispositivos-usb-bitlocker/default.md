---
title: 'Criptografe dispositivos USB com BitLocker'
published: true
metadata:
    author: 'Raphael Hernandes'
    description: 'Proteja seus dados de roubo físico. Use BitLocker no seu Windows para criptografar dispositivos USB'
    'og:title': 'Cripotrafe dispositivos USB | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Proteja seus dados de roubo físico. Use BitLocker no seu Windows para criptografar dispositivos USB'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/criptografe-dispositivos-usb-bitlocker/social.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Cripotrafe dispositivos USB | Privacidade para Jornalistas'
    'twitter:description': 'Proteja seus dados de roubo físico. Use BitLocker no seu Windows para criptografar dispositivos USB'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/criptografe-dispositivos-usb-bitlocker/social.png'
taxonomy:
    tag:
        - windows
        - disk
visible: true
---

# Criptografe dispositivos USB com BitLocker

[TOC]

A ideia de criptografar seus discos USB e pendrives é semelhante à [criptografia de HD](../criptografe-seu-hd-bitlocker). Ela garante que seus arquivos estarão seguros mesmo que seu dispositivo seja perdido ou roubado.

Ao fim deste arquivo, você irá saberá como criptografar seu dispositivo USB para protegê-lo.

## Checking Windows Release

BitLocker é o software de criptografia de disco rígido que vem embutido no Windows. Infelizmente, nem todas as versões do sistema operacional têm essa ferramenta. Primeiro, verifique se você tem o Windows Pro ou Enterprise no seu computador

![](check-os-release-1.png?lightbox=1024&cropResize=600,600)

![](check-os-release-3.png?lightbox=1024&cropResize=600,600)


Se você tem uma versão que não a Pro ou Enterprise, você precisará comprar um upgrade da Microsoft. A boa notícia é que você não precisará reinstalar tudo, já que a melhora é feita automaticamente em segundo plano quando você faz a compra. Siga [essas instruções](https://support.microsoft.com/pt-br/help/12384/windows-10-upgrading-home-to-pro).

## Configurar o BitLocker

* Quando você confirmar que seu sistema operacional suporta o BitLocker, vá para "Computador" e clique com o botão direito no dispositivo que você quer criptografar. Selecione **Ativar Bitlocker** _(turn BitLocker on)_ no menu

![](bitlocker-1.png?lightbox=1024&cropResize=600,600)

* Escolha a opção **Usar uma senha para desbloquear o disco** _(use a password to unlock the drive)_. Digite a senha duas vezes. Recomendamos escolher uma que você não usa em nenhum outro lugar

![](bitlocker-2.png?lightbox=1024&cropResize=600,600)

* Você deve salvar a chave de recuperação em algum lugar

![](bitlocker-3.png?lightbox=1024&cropResize=600,600)

![](bitlocker-4.png?lightbox=1024&cropResize=600,600)

* Abra o arquivo que você acabou de salvar e, ou grave a chave de recuperação em uma carteira de senhas, ou a escreva num papel

!! Se preferir anotar a senha, nunca deixe o papel junto do dispositivo que foi criptografado

* Agora delete o arquivo que foi salvo mais cedo e esvazie a lixeira do Windows

!!! Cuidado. Se você esquecer a senha e perder a chave de recuperação, as informações do disco serão perdidas para sempre

* Clique em **Próximo** _(next)_ para continuar o processo de configuração

![](bitlocker-6.png?lightbox=1024&cropResize=600,600)

* Escolha a opção de criptografar o dispositivo todo, não só o espaço usado

![](bitlocker-8.png?lightbox=1024&cropResize=600,600)

* Selecione o **Modo de compatibilidade** _(compatible mode)_ se você deseja usar o dispositivo USB em máquinas com Windows 7 e 8. Do contrário, escolha **Novo modo de criptografia** _(new encryption mode)_

![](bitlocker-9.png?lightbox=1024&cropResize=600,600)

* Clique em **Próximo** *(next)*

![](bitlocker-10.png?lightbox=1024&cropResize=600,600)

* O processo de criptografia deverá começar

![](bitlocker-11.png?lightbox=1024&cropResize=600,600)

* Assim que o processo acabar, clique em **Fechar** _(close)_. O seu dispositivo USB está criptografado

![](bitlocker-12.png?lightbox=1024&cropResize=600,600)

## Ejetar o dispositivo USB criptografado

De agora em diante, o drive pode ser ejetado como qualquer outro. Simplesmente clique com o botão direito no ícone do dispositivo e selecione **Ejetar** _(eject)_

![](unmount-drive-1.png?lightbox=1024&cropResize=600,600)

## Conectar o drive USB criptografado

Quando você inserir o dispositivo no USB do seu computador, o Windows irá pedir a senha para desbloqueio.

* Clique na notificação no canto inferior direito da tela para colocar a senha

![](mount-drive-1.png?lightbox=1024&cropResize=600,600)

* Digite a senha

![](mount-drive-2.png?lightbox=1024&cropResize=600,600)

![](mount-drive-3.png?lightbox=1024&cropResize=600,600)

* Se você usa um HD criptografado, é seguro selecionar a opção de salvar a senha no seu computador. Dessa forma, da próxima vez você não precisará digitar a senha nesta máquina novamente

![](mount-drive-4.png?lightbox=1024&cropResize=600,600)

* Agora você pode usar o dispositivo USB normalmente como qualquer outro

![](mount-drive-5.png?lightbox=1024&cropResize=600,600)

## Leia mais

* [Criptografe seu HD com BitLocker](../criptografe-seu-hd-bitlocker) no Windows