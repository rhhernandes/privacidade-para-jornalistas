---
title: 'Armazenar arquivos de maneira privada na nuvem'
metadata:
    author: 'Raphael Hernandes'
    description: 'Nem todo serviço de armazenamento em nuvem funciona da mesma forma. Aprenda a usar o Sync.com para manter seus arquivos seguros e privados'
    'og:title': 'Armazenar arquivos de forma privada na nuvem | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Nem todo serviço de armazenamento em nuvem funciona da mesma forma. Aprenda a usar o Sync.com para manter seus arquivos seguros e privados'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/09.armazene-arquivos-forma-privada-nuvem/sync_main_page.PNG'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Armazenar arquivos de forma privada na nuvem | Privacidade para Jornalistas'
    'twitter:description': 'Nem todo serviço de armazenamento em nuvem funciona da mesma forma. Aprenda a usar o Sync.com para manter seus arquivos seguros e privados'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/09.armazene-arquivos-forma-privada-nuvem/sync_main_page.PNG'
taxonomy:
    tag:
        - windows
        - criptografia
        - armazenamento
        - nuvem
---

# Armazenar arquivos de maneira privada na nuvem

[TOC]

Nem todo serviço de armazenamento de arquivos na nuvem funcionam de forma igual. Embora quase todos usem criptografia para transferir e armazenar os arquivos, há detalhes importantes a serem considerados.

Serviços populares --como Dropbox e o Microsoft OneDrive-- tem acesso às chaves para descriptografar os arquivos. Em outras palavras, as empresas podem acessar seus arquivos para fazer coisas como [detectar mídia pirata](http://www.wired.co.uk/article/dropbox-dmca-position?target=_blank) nas suas pastas, ou fornecer informações quando [intimados por um mandado](#servicos-sem-conhecimento-zero), por exemplo.

Felizmente, serviços com criptografia de ponta a ponta e protocolos de conhecimento-zero (que não analisam o conteúdo dos arquivos) resolvem este problema. Seus arquivos são criptografados no seu computador usando uma chave antes de serem enviados para a nuvem. Como a chave nunca deixa o seu computador, ninguém mais consegue acessar os arquivos, nem o prestador do serviço.

## Instruções

As sessões a seguir vão te ensinar a se registrar e a configurar o [sync.com](https://www.sync.com/?target=_blank). É um sistema de armazenamento em nuvem simples de usar, e usa protocolos de conhecimento-zero que deixam seus arquivos seguros e privados.

### Criar uma conta

* Acesse [sync.com](https://www.sync.com/?target=_blank) e clique no botão **Free signup**, no canto superior direito

![](sync_main_page.PNG?lightbox&cropResize=800,800)

* Insira seu email e uma senha forte

![](registering_an_account.PNG?lightbox&cropResize=800,800)

* Você deverá receber um email de confirmação. Clique no link enviado na mensagem. A conta, então, estará pronta para ser usada

![](registration_complete.PNG?lightbox&cropResize=800,800)

### Configurar o programa no computador

Você pode sincronizar pastas no seu computado com o sync.com se instalar o software.

* Acesse a página de [download](https://www.sync.com/install/?target=_blank)

![](downloading_client_1.PNG?lightbox&cropResize=800,800)

* Abra o arquivo para instalar o programa. Escolha a segunda opção e clique em **Next**

![](logging_into_the_client_1.PNG?lightbox&cropResize=800,800)

* Insira seu nome de usuário e senha

![](logging_into_the_client_2.PNG?lightbox&cropResize=800,800)

* Mude o lugar da pasta que será sincronizada se desejar. Por padrão, o programa cria uma pasta em **Documentos** chamada **Sync**.

![](configuring_client_1.PNG?lightbox&cropResize=800,800)

* Desmarque a opção **Send error and debug messages to Sync** e clique em **Finish** para finalizar a instalação

![](configuring_client_2.PNG?lightbox&cropResize=800,800)

* Um pequeno ícone deverá aparecer próximo ao relógio do computador (canto inferior direito, por padrão). Isso mostra que o programa está rodando

![](syncing_a_file_1.PNG?lightbox&cropResize=800,800)

### Sincronizar seu primeiro arquivo

Abra a pasta **Sync** em **Documents** e arraste um arquivo para lá (copiar e colar também funciona)

![](syncing_a_file_2.PNG?lightbox&cropResize=800,800)

### Acessar seus arquivos pelo navegador

* Acesse sync.com novamente e clique em **Log in**, no topo da página

![](sync_main_page.PNG?lightbox&cropResize=800,800)

* Insira seu login e senha

![](web_ui_1.PNG?lightbox&cropResize=800,800)

* O arquivo que você sincronizou deve aparecer na interface online

![](web_ui_2.PNG?lightbox&cropResize=800,800)

### Ativar a autenticação de dois fatores _(opcional, mas altamente recomendado)_

É sempre bom proteger suas contas importantes com autenticação de duas etapas, par ao caso de sua senha ser roubada por uma [backdoor no seu computador](../protect-your-pc-from-backdoors-windows), por exemplo.

Para isso, você precisará do aplicativo **Google Authenticator** ([Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2?target=_blank), [iPhone](https://itunes.apple.com/us/app/google-authenticator/id388497605?target=_blank)) no seu smartphone.

* No painel do Sync no seu navegador, clique no seu endereço de email no canto superior direito da tela. Selecione **Account Settings** do menu.

![](configure_2fa_1.PNG?lightbox&cropResize=800,800)

* Na aba **Security**, selecione **Enable 2-FA via Google Authenticator**

![](configure_2fa_2.PNG?lightbox&cropResize=800,800)

* Escaneie o código QR que irá aparecer usando o Google Authenticator no seu telefone. Digite a senha de seis dígitos que irá aparecer e selecione **Save**.

![](configure_2fa_3.PNG?lightbox&cropResize=800,800)

![](logging_in_with_2fa_1.PNG?lightbox&cropResize=800,800)

* Quando a autenticaçãod e dois fatores estiver ativa, você precisará do código de seis dígitos do seu telefone todas as vezes que for acessar o painel no navegador.

![](web_ui_1.PNG?lightbox&cropResize=800,800)

![](logging_in_with_2fa_2.PNG?lightbox&cropResize=800,800)

## Outros serviços de conhecimento-zero

* [SpiderOak One](https://spideroak.com/solutions/spideroak-one?target=_blank)
* [Tresorit](https://tresorit.com/?target=_blank)
* [Boxcryptor](https://www.boxcryptor.com/en?target=_blank) - Serviço de criptografia de conhecimento-zero para Dropbox, OneDrive, Google Drive e Box
* [Resilio](https://www.getsync.com/?target=_blank) - Sincronize seus dispositivos sem um intermediário na nuvem

### Serviçõs sem conhecimento-zero

Os seguintes serviços de armazenamento em nuvem **não** usam protocolos de conhecimento-zero. Alguns enviam informações para governos, o que é confirmado por relatórios de transparência.

* **Dropbox** - [Relatório de transparência](https://www.dropbox.com/transparency?target=_blank)
* **Microsoft OneDrive** - [Relatóriod e pedidos para o cumprimento da lei](https://www.microsoft.com/about/csr/transparencyhub/lerr/?target=_blank)
* **Google Drive** - [Relatório de transparência](https://www.google.com/transparencyreport/userdatarequests/AU/?target=_blank)
* **Box**
* **iCloud** - [Pedidos de informação feitos pelo governo](https://www.apple.com/au/privacy/government-information-requests/?target=_blank)

## Leia mais _(em inglês)_

* [Sync.com Privacy White Paper](https://www.sync.com/pdf/sync-privacy.pdf) 
* [Comparison of online backup services](https://en.wikipedia.org/wiki/Comparison_of_online_backup_services?target=_blank)
* [What is Zero-Knowledge Encryption?](https://tresorit.com/blog/zero-knowledge-encryption/)
* [Fabian M. Suchanek's review of sync.com](https://suchanek.name/texts/reviews/tresorit.html#sync)