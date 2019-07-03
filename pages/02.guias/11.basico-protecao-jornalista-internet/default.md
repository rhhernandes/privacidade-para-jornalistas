---
title: 'Guia básico para a proteção do jornalista na Internet'
published: false
metadata:
    author: 'Raphael Hernandes'
    description: 'Guia para que jornalistas entendam conceitos básicos e tenham uma noção de ameaças que eles e suas fontes enfrentam em ambientes digitais'
    'og:title': 'Guia básico para a proteção do jornalista na Internet | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Guia para que jornalistas entendam conceitos básicos e tenham uma noção de ameaças que eles e suas fontes enfrentam em ambientes digitais'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/01.conversas-seguras-com-ricochet/sending-im-1.png'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@hernandesraph'
    'twitter:title': 'Guia básico para a proteção do jornalista na Internet | Privacidade para Jornalistas'
    'twitter:description': 'Guia para que jornalistas entendam conceitos básicos e tenham uma noção de ameaças que eles e suas fontes enfrentam em ambientes digitais'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/02.guias/01.conversas-seguras-com-ricochet/sending-im-1.png'
taxonomy:
    category:
        - 'Privacidade para Jornalistas'
    tag:
        - 'end-to-end encryption'
        - segurança
        - comunicação
---

# Guia básico para a proteção do jornalista na Internet

[TOC]

Por **Raphael Hernandes** | [@hernandesraph](https://twitter.com/hernandesraph)

A gente sabe que jornalista procura fugir das exatas e do que é muito complexo tecnicamente. Não dá tempo. Mas a gente também sabe que é fundamental ao repórter saber proteger a si e a suas fontes online. 

Por isso, a ideia deste guia é ensinar ao leigo como montar defesas eficientes em meios digitais. Sem paranoia. Para tanto, é importante conhecer alguns conceitos e entender como pensar nesse mundo: o processo é mais importante que as ferramentas (mas, claro, citamos algumas depois).

!!!! Dica: saiba se seus dados pessoais já estiveram envolvidos em algum vazamento em [haveibeenpwned.com](https://haveibeenpwned.com/). Basta inserir seu email e/ou nome de usuário e procurar. No menu do topo, ative a opção "Notify me" para receber alertas caso suas informações estejam em algum _leak_. O site não reúne todos os vazamentos possíveis e imagináveis, mas é um bom começo.

Comecemos por entender um pouco mais sobre a atuação do nosso protagonista nessa história: o hacker.

## O hacker

A pessoa responsável por ataques, no dia a dia, não necessariamente é uma pessoa com conhecimento técnico muito avançado. 

Hoje, é possível comprar ferramentas prontas que podem ser usadas para realizar diferentes tipos de ataques. E nem é necessário procurar muito. Algumas delas são compradas legalmente e estão a uma busca no Google e um cartão de crédito de distância.

Essa popularização faz com que sejam mais comuns ataques menos sofisticados, que poderiam ser facilmente evitados com medidas básicas de segurança. 

Hackers extremamente qualificados existem, inclusive no Brasil. Estes, no entanto, normalmente estão preocupados com coisas maiores --tipo ganhar dinheiro desenvolvendo essas ferramentas que serão exploradas por atacantes com menor conhecimento técnico.

!!!! No Brasil, os atacantes são muitas vezes criativos e ousados (agem às claras e sem muito medo de serem pegos). Exemplo disso nesta [reportagem da Folha](https://www1.folha.uol.com.br/mercado/2018/03/fraude-em-cartao-oferece-suporte-tecnico.shtml).

## Os ataques

Ataques contra jornalistas não são novidades. Os objetivos e os adversários variam. Casos clássicos focam em quebra de sigilo de fonte, ataques à reputação do repórter/veículo e para espalhar desinformação.

Quebra de sigilo telefônico é um velho conhecido, mas casos recentes incluem condução coercitiva de jornalista que teve seus eletrônicos apreendidos, repórteres com WhatsApp hackeado, casos de espionagem em fronteira e roubo de redes sociais por grupos ciberterroristas.

(imagens roubo)

As consequências de um ataque podem incluir a publicação de informações falsas, envio de emails falsos para atacar colegas, acesso a informações sensíveis (fontes, por ex.) e perda de reputação.

Uma boa proteção começa ao entender que o que normalmente é entendido por _hacking_, ou a invasão de um sistema, é apenas um dos possíveis problemas.

O atacante tem um objetivo a cumprir, e isso não quer dizer que ele precise tomar controle completo de sua vida digital para atingí-lo. Via de regra, o mais simples é melhor. 

!!! Ex.: ao ativar uma conta de WhatsApp, o aplicativo manda uma mensagem de SMS com um código para o usuário. Um criminoso precisa dessa informação para roubar uma conta no mensageiro. Em vez de tentar interceptar as mensagens de texto enviadas para o número da vítima, ele pode simplesmente dar um jeito de convencê-la (ludibriar) a passar esse número para ele.

Eis alguns exemplos das principais ameaças:

* Hacking
	* Malwares (vírus e afins)
	* Backdoors (brechas deixadas propositalmente em sistemas para que informações mesmo criptografadas sejam acessíveis sem a senha, mediante ordem judicial, por ex.
* Engenharia social
	* Phishing (envio de emails falsos para roubar informações)
	* Papagaio de pirata (ficar de olho na tela da vítima, fisicamente)
* Ataques legais
	* Quebra de sigilo
* Furtos

Em um ataque, essas ameaças podem se associar.

Por mais simples ou óbvio que possam parecer alguns desses, é importante levar tudo isso em consideração ao montar uma defesa. Novamente: o que é mais simples é também mais provável de acontecer.

!! O Marco Civil da Internet obriga operadoras de telefonia a armazenar informações de navegação de seus usuários por um ano e esses dados podem ser usados pelo governo em investigações. Com eles, é possível descobrir quem se comunicou com quem, e que horas.

## Como se defender

### O custo

Que fique bem claro: **defesa custa**. Não é grátis.

O custo não é necessariamente financeiro. Pode ser a conveniência de digitar uma senha a mais, ou até de deixar de usar um serviço popular por não ser a opção mais segura naquele momento. Isso é igual ao mundo físico: é mais trabalhoso trancar três fechaduras na porta, colocar alarme no carro custa dinheiro e por aí vai.

### Data at rest vs data in motion

É importante se lembrar que nem todo dado está em trânsito. Tão importante quanto proteger a mensagem que é enviada do ponto A para o ponto B, é importante proteger o local onde ela fica armazenada depois --às vezes esquecemos do segundo. 

### Abordagem do castelo

Um bom sistema de defesa funciona como um castelo medieval. O rei poderia ficar dentro de uma sala fechada, com guardas na porta, cercado por uma parede e um rio cheio de crocodilos. A lógica é: se uma defesa falha, tem a outra. Redundância é chave no mundo digital também (o conceito se chama _defense in depth_). Ou seja, a resposta pra "mas eu já uso antivírus, tenho que ter senha forte também?" é "sim".

### Análise de ameaças

Para não cair na paranoia, é bom fazer uma análise de ameaças caso a caso, a cada reportagem. Também é bom conhecer as ferramentas que estão sendo usadas para não cometer deslizes ao achar que está mais seguro do que realmente está.

Pergunte-se:

* O que você não quer que os outros saibam?
* Por que alguém iria querer saber isso? Quem?
* Como alguém pode conseguir essa informação?
* O que acontece se o atacante vencer?

Leve sempre em consideração a pessoa ou entidade que pode ser seu adversário. Quem pode querer te atacar? O mais óbvio é o assunto da matéria. Aí é importante pensar no histórico desse atacante para saber o que ele pode fazer: um ataque jurídico? Ficar na porta da sua casa esperando você sair pra roubar seu telefone?

### Boas práticas

* Mantenha tudo atualizado. Alguns dos principais problemas recentes seriam evitados com atualizações de softwares e sistemas.

(imagem wannacry)

* Cuide bem das suas **senhas**. **Não repita** a mesma senha em lugares diferentes e as troque com frequência. Uma boa senha é uma combinação de caracteres aleatórios.
	* Para gerir as senhas (e criar boas senhas novas) é recomendável o uso de um gerenciador de senhas. Algumas opções:
		* [Lastpass](https://www.lastpass.com/pt)
		* [1Password](https://1password.com/pt/) 
		* [Keepass](https://keepass.info/)

* Vá além da senha e ative a autenticação de dois fatores (2FA) --aquele negócio que nem os bancos têm, no qual além de digitar a senha, você tem que inserir um código presente no celular. Sempre que possível, evite usar SMS como método de validação. [Este site](http://turnon2fa.com) ensina a ativar a verificação de duas etapas em todos os serviços mais populares. 

* Tenha bom senso e trate sua segurança virtual como trata a do mundo físico. Não entre em links estranhos assim como não entraria num beco desconhecido. Cuidado com dispositivos USBs estranhos (não use um pen drive cuja procedência desconhece).

* Seus dados pessoais podem ser uma arma nas mãos de atacantes (e golpistas). Lembra daquela conta antiga do MySpace? Pode ser a hora de apagar.

* Celulares são um desastre. Coletam muitas informações o tempo todo, e esses dados vão parar em muitos lugares diferentes --afinal, são muitos aplicativos capturando dados simultaneamente. Se vai discretamente encontrar uma fonte que não pode ser identificada, talvez seja melhor deixar o telefone em casa.

* Use antivírus, inclusive no celular. Prefira marcas conhecidas. Muitas têm promoções se comprar para computador e celular ao mesmo tempo (sim, tem que pagar).

* Não digite senhas e informações sensíveis em sites que não têm HTTPS (aquele cadeadinho ao lado do endereço do site). 

* Cuidado com os metadados, informações que ficam escondidas nos arquivos e trazem dados como o local onde uma foto foi tirada ou quem criou um documento de Word. Eles podem, por exemplo, entregar a localização de uma fonte que esteja escondida. Existem [várias formas de excluir metadados](https://www.makeuseof.com/tag/3-ways-to-remove-exif-metadata-from-photos-and-why-you-might-want-to/) de um arquivo. O mais seguro, muitas vezes, pode ser tirar prints das fotos ou documentos que quer publicar e usar essas imagens em vez do arquivo original.

* Mantenha o HD do computador criptografado. Dessa forma, se alguém tiver acesso ao seu PC, não conseguirá extrair os arquivos facilmente. Há opções para isso no [Windows](https://privacidadeparajornalistas.org/guias/criptografe-seu-hd-bitlocker), [Mac](https://support.apple.com/pt-br/HT204837) e [Linux](https://averagelinuxuser.com/encrypt-hard-drive-in-linux/). O mesmo é possível em celulares iOS e Android, nas configurações.

* Apagar um arquivo não significa que ele desapareceu. Há formas de recuperá-lo. Se precisar apagar um arquivo de modo a dificultar a recuperação, use programas como [Recuva](https://www.ccleaner.com/recuva/features/securely-delete-files-you-want-to-erase-forever) --que também serve para recuperar arquivos deletados, aliás.

* Uso de serviços de VPN (como o super fácil de usar [NordVPN](https://nordvpn.com/pt-br/)) ajuda trazer mais segurança ao se conectar wifi compartilhados (no metrô, em hotéis...). Usar VPNs não confiáveis pode ser um problemão, então opções de procedência duvidosa são **extremamente** perigosas.

* Sempre que possível --e que julgar necessário-- compartimentalize seu trabalho. Isso serve tanto para pessoas que estão ajudando na apuração (informar fontes e compartilhar arquivos sigilosos somente se necessário) quanto no gerenciamento do que você tem (lembra que temos que cuidar também dos dados armazenados? Às vezes pode ser uma boa salvar parte dos arquivos num lugar, parte em outro, parte num terceiro canto... Caso um deles seja comprometido, parte da informação estará segura).

#### Casos mais complexos

Lidar com casos mais complexos pode exigir algumas medidas extremas.

* Por mais que seus dados fiquem criptografados em serviços de nuvem, o provedor pode ser capaz de determinar qual tipo de arquivo está ali e repassar essa informação para autoridades. Se quer mais segurança nisso, prefira serviços que adotam protocolos de conhecimento-zero, como o [Sync](https://privacidadeparajornalistas.org/guias/armazene-arquivos-forma-privada-nuvem).

* Tor: é uma forma de conexão à internet que ajuda a esconder metadados da conexão --fica praticamente impossível determinar quem se comunicou com quem. É possível usar essa comunicação anônima e segura para [navegar](https://securityinabox.org/en/guide/torbrowser/windows/), para [conversar](https://privacidadeparajornalistas.org/guias/conversas-seguras-com-ricochet) ou para [trocar arquivos](https://privacidadeparajornalistas.org/guias/troca-segura-de-arquivos-com-onionshare).

* Se o foco é anonimato, troque o Windows pelo [Tails](https://tails.boum.org/index.pt.html), uma versão do Linux que já vem com Tor configurado por padrão. Se o foco é segurança, o [Qubes](https://www.qubes-os.org/) é uma boa opção.

* Você não precisa excluir seu sistema para usar o Tails, o Qubes ou qualquer outro. Você pode fazê-lo por meio de uma [máquina virtual](https://blog.storagecraft.com/the-dead-simple-guide-to-installing-a-linux-virtual-machine-on-windows/). É como se tivesse um computador dentro do seu computador. Aí dá pra clicar tranquilamente naquele link suspeito porque, se der problema, afetará apenas a máquina virtual --você exclui ela, cria outra e o seu computador fica intacto. 

* Aí precisa da ajuda da TI: [Globaleaks](https://privacidadeparajornalistas.org/guias/troca-arquivos-mensagens-globaleaks) e [Securedrop](https://securedrop.org/) são boas opções para receber arquivos anônimos de _whistleblowers_.

## Comunicação segura

!!!! São vários os caminhos que um hacker pode usar para atacar (ou outros mensageiros): [entenda quais são eles](https://www1.folha.uol.com.br/tec/2019/06/saiba-proteger-seu-whatsapp-de-hackers-e-entenda-como-o-ataque-acontece.shtml).

* WhatsApp e Telegram oferecem criptografia de ponta a ponta, mas é possível saber quem falou com quem e quando --o que fica escondido é apenas o conteúdo das mensagens em trânsito. Uma pessoa com acesso à conta ou ao telefone pode ver as mensagens.

* O Threema (que custa aproximadamente R$ 10 para [Android](https://play.google.com/store/apps/details?id=ch.threema.app&hl=pt_BR) e [iOS](https://apps.apple.com/br/app/threema/id578665578)) é uma opção mais segura por não usar o número de telefone como identificador para garantir acesso à conta. Nesse caso, uma pessoa que clonasse seu número não ganharia acesso ao app também. Também não oculta metadados (quem falou com quem e quando).

* [Ricochet](https://privacidadeparajornalistas.org/guias/conversas-seguras-com-ricochet) (conversas individuais), [Semaphor](https://privacidadeparajornalistas.org/guias/conversas-seguras-equipe) (conversas em grupo) e [Onionshare](https://privacidadeparajornalistas.org/guias/troca-segura-de-arquivos-com-onionshare) (compartilhamento de arquivos) são mais complexos de usar, mas garantem segurança maior por funcionar por meio do Tor. 

* O [PGP](https://privacidadeparajornalistas.org/guias/criar-chaves-pgp-windows) é uma forma de criptografar emails. 

## Plano de defesa

É importante ter um plano de defesa. Um bom plano envolve uma série de receitas simples para resolver cada problema no processo. Ao pensar em como se proteger para uma reportagem, leve em consideração as seguintes perguntas:

