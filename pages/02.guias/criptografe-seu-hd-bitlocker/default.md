---
title: 'Criptografe seu HD com BitLocker'
published: true
metadata:
    author: 'Raphael Hernandes'
    description: 'Proteja seus dados de roubos físicos. Ative o BitLocker no seu Windows para habilitar criptografia completa do seu HD'
    'og:title': 'Criptografe seu HD | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Proteja seus dados de roubos físicos. Ative o BitLocker no seu Windows para habilitar criptografia completa do seu HD'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/criptografe-seu-hd-bitlocker/social.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Criptografe seu HD | Privacidade para Jornalistas'
    'twitter:description': 'Proteja seus dados de roubos físicos. Ative o BitLocker no seu Windows para habilitar criptografia completa do seu HD'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/criptografe-seu-hd-bitlocker/social.png'
taxonomy:
    tag:
        - windows
        - disk
visible: true
---

# Criptografe seu HD com BitLocker

[TOC]

Criptografia de HD protege de duas coisas. Primeiro, ninguém pode adulterar seu computador (como instalar backdoors). Segundo, seus arquivos permanecem seguros para o caso de a máquina ser roubada.

Continue a leitura para configurar o BitLocker e fazer uma criptografia completa do seu disco no Windows 10.

## Checar versão do Windows

BitLocker é o software de criptografia de disco rígido que vem embutido no Windows. Infelizmente, nem todas as versões do sistema operacional têm essa ferramenta. Primeiro, verifique se você tem o Windows Pro ou Enterprise no seu computador.

![](check-os-release-1.png?lightbox=1024&cropResize=600,600)

![](check-os-release-3.png?lightbox=1024&cropResize=600,600)

Se você tem uma versão que não a Pro ou Enterprise, você precisará comprar um upgrade da Microsoft. A boa notícia é que você não precisará reinstalar tudo, já que a melhora é feita automaticamente em segundo plano quando você faz a compra. Siga [essas instruções](https://support.microsoft.com/pt-br/help/12384/windows-10-upgrading-home-to-pro) para fazer a melhoria no sistema.

## Configurar o BitLocker

* Quando você confirmar que seu sistema operacional suporta o BitLocker, abra-o no menu iniciar

![](run-bitlocker-1.png?lightbox=1024&cropResize=600,600)

* Clique para acionar o BitLocker

![](run-bitlocker-2.png?lightbox=1024&cropResize=600,600)

Se você receber uma mensagem de erro como a que está abaixo, siga as instruções na seção _Usar o BitLocker sem um chip TPM_. Do contrário, vá para a seção _Usar o BitLocker com um chip TPM_.

![](tpm-config-1.png?lightbox=1024&cropResize=600,600)

### _Usar o BitLocker sem um chip TPM

Esse erro significa que seu computador não tem um negócio chamado [chip TPM](http://www.howtogeek.com/237232/what-is-a-tpm-and-why-does-windows-need-one-for-disk-encryption/?target=_blank). Esse chip normalmente é usado para armazenar a chave para descriptografar os conteúdos de maneira segura. Caso o seu computador não tenha ele, você ainda poderá usar o BitLocker e fazer o desbloqueio usando uma senha.

* Abra o menu iniciar e abra o *Editar política de grupos* (basta digitar "grupo" na barra de buscas)

![](tpm-config-2.png?lightbox=1024&cropResize=600,600)

* Agora vá para **Local Computer Policy -> Computer Configuration -> Administrative Templates -> Windows Components -> BitLocker Drive Encryption -> Operating System Drives**. Clique duas vezes em **Require additional authentication at startup**

![](tpm-config-3.png?lightbox=1024&cropResize=600,600)

* Na próxima janela, selecione **Habilitado** no botão que lembra um rádio e certifique-se de que as configurações estão como as da imagem

![](tpm-config-5.png?lightbox=1024&cropResize=600,600)

* Clique em **OK**. O **Require additional authentication at startup** também deve estar **Habilitado**

![](tpm-config-6.png?lightbox=1024&cropResize=600,600)

* Abra o **BitLocker** de novo a partir do menu iniciar

![](run-bitlocker-1.png?lightbox=1024&cropResize=600,600)

* Se você não tem um chip TPM, você verá as seguintes opções. Selecione **Inserir uma senha**

![](run-bitlocker-4.png?lightbox=1024&cropResize=600,600)

* Agora coloque a senha. Você não deve reutilizar uma senha que já está sendo usada em outro lugar.

![](run-bitlocker-5.png?lightbox=1024&cropResize=600,600)

* Agora você precisa salvar a sua chave de recuperaçãod e backup. A senha e a chave são as únicas coisas que podem desbloquear o seu HD

!!! Cuidado! Se você esquecer a senha e perder a chave de recuperação, os conteúdos do seu HD serão perdidos para sempre

* Escolha a opção **Imprimir chave de recuperação** *(print the recovery key)* 

![](run-bitlocker-6.png?lightbox=1024&cropResize=600,600)

* Escolha a opção **Microsoft Print to PDF** 

![](run-bitlocker-8.png?lightbox=1024&cropResize=600,600)

* Salve o PDF com a sua chave de recuperação

![](run-bitlocker-9.png?lightbox=1024&cropResize=600,600)

* Abra o arquivo PDF. Sua chave é o longo bloco de dígitos perto do fim. Escreva-o em um pedaço de papel e guarde num lugar seguro, ou save a chave numa carteira de senhas.

!! Se você preferir anotar ou imprimir a senha, nunca guarde junto do seu computador

![](run-bitlocker-10.png?lightbox=1024&cropResize=600,600)

* Depois de guardar a chave (ou imprimir), delete o arquivo PDF e esvazie a lixeira do Windows se necessário

* Agora clique em **Próximo** *(next)* e selecione **Criptografar todo o disco** *(encrypt entire drive)*

![](run-bitlocker-12.png?lightbox=1024&cropResize=600,600)

* Selecione a opção **Nova forma de criptografia** *(new encryption mode)*

![](run-bitlocker-13.png?lightbox=1024&cropResize=600,600)

* Clique em **Próximo**

![](run-bitlocker-14.png?lightbox=1024&cropResize=600,600)

* Reinicie o computador para iniciar a criptografia do HD

![](run-bitlocker-15.png?lightbox=1024&cropResize=600,600)

![](run-bitlocker-16.png?lightbox=1024&cropResize=600,600)

* Uma vez que o computador for reiniciado, você verá uma janela. Insira a senha que você escolheu mais cedo para desbloquear o HD.

!!! Você precisará digitar essa senha toda vez que o computador for reiniciado

![](run-bitlocker-17.png?lightbox=1024&cropResize=600,600)

* Você pode continuar a usar o seu computador enquanto ele é criptografado. Você pode ver o progresso no ícone do BitLocker próximo ao relógio do Windows (canto inferior direito da tela)

![](run-bitlocker-18.png?lightbox=1024&cropResize=600,600)

![](run-bitlocker-19.png?lightbox=1024&cropResize=600,600)

![](run-bitlocker-20.png?lightbox=1024&cropResize=600,600)

* Quando o processo terminar, você deverá ver um cadeado perto do seu disco **C:** (em "Computador"), indicando que ele está criptografado

![](run-bitlocker-21.png?lightbox=1024&cropResize=600,600)

* Você pode verificar a criptografia clicando com o botão direito do mouse em **C:** e selecionando **Gerenciar BitLocker** *(manage BitLocker)*

![](run-bitlocker-22.png?lightbox=1024&cropResize=600,600)

![](run-bitlocker-23.png?lightbox=1024&cropResize=600,600)

O seu disco rígido principal já está criptografado. Não se esqueça que seus dispositivos USB também devem ser criptografados. Leia mais sobre isso nos nossos [guias](/guias).

### Usar o BitLocker com um chip TPM

Se o seu computador tem um chip TPM, a configuração deverá ser bem simples. Infelizmente, não tenho acesso a um computador com esse recurso para montar o tutorial. Até lá, use as instruções [neste site](https://countuponsecurity.com/2014/06/23/bitlocker-with-tpm-in-10-steps/?target=_blank).

!!!! Ajude-nos a expandir este guia. Entre em [contato](mailto:contato@privacidadeparajornalistas.org) consoco!

## Habilitar bloqueio de tela automático

Para completar o processo, você deve habilitar o bloqueio de tela automático para o caso de você ficar longe do seu computador por alguns minutos. Assim, seria necessário colocar a senha novamente (não a do BitLocker) para continuar o trabalho.

* Clique com o botão direito na área de trabalho e selecione **Personalizar** _(personalise)_

![](screen-lock-1.png?lightbox=1024&cropResize=600,600)

* Selecione **Bloqueio de tela** *(lock screen)* à esquerda e role a tela para baixo. Clique em **configurações de proteção de tela** _(screen saver settings)_

![](screen-lock-2.png?lightbox=1024&cropResize=600,600)

* Selecione o protetor de tela que preferir e uma quantidade razoavelmente baixa de minutos para ativar. Selecione a caixa **ao voltar, mostre a caixa de log-on** _(on resume, display log-on screen)_

![](screen-lock-3.png?lightbox=1024&cropResize=600,600)

* Agora, quando o protetor de tela for ativado, você precisará digitar a senha para voltar a usar seu computador

![](screensaver-1.png?lightbox=1024&cropResize=600,600)

![](screen-lock-4.png?lightbox=1024&cropResize=600,600)

![](screen-lock-5.png?lightbox=1024&cropResize=600,600)

## Leia mais

* [Criptografe dispositivos USB com BitLocker](../criptografe-dispositivos-usb-bitlocker) no Windows