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

* 

## Comunicação segura