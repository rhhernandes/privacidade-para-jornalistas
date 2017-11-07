---
title: Ameaças
published: true
metadata:
    author: 'Raphael Hernandes'
    description: 'Análise de ameaças para jornalistas entenderem quais ferramentas devem usar em diferentes cenários a fim de manter sua privacidade e o sigilo de suas fontes'
    'og:title': 'Ameaças | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'Análise de ameaças para jornalistas entenderem quais ferramentas devem usar em diferentes cenários a fim de manter sua privacidade e o sigilo de suas fontes'
    'og:image': 'https://privacidadeparajornalistas.org/user/pages/01.ameacas/social-ameacas.jpeg'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': '@rhhernandes'
    'twitter:title': 'Ameaças | Privacidade para Jornalistas'
    'twitter:description': 'Análise de ameaças para jornalistas entenderem quais ferramentas devem usar em diferentes cenários a fim de manter sua privacidade e o sigilo de suas fontes'
    'twitter:image': 'https://privacidadeparajornalistas.org/user/pages/01.ameacas/social-ameacas.jpeg'
external_links:
    process: true
    title: false
    no_follow: true
    target: _blank
    mode: active
---

# Análise de ameaças

[TOC]

Quando se trata da proteção de fontes e das informações que já foram coletadas, é bastante claro quem é o principal adversário. Dependendo da pessoa ou organização que está sendo investigada, os recursos disponíveis para cercear os jornalistas podem variar. Portanto, as ferramentas e habilidades devem estar à altura.

!!!! Algum comentário ou correção? Sinta-se à vontade para [**entrar em contato**](mailto:contato@privacidadeparajornalistas.org)

## Aviso

A escolha das ferramentas e práticas adequadas devem ir ao encontro da "análise de ameaças". É uma forma de se entender:

1. Quem está tentando te prejudicar
2. O que eles buscam
3. O que você pode fazer quanto a isso

Baseado nessa informação, você pode selecionar um conjunto de ferramentas de segurança e de privacidade, além de boas práticas para se defender e de proteger suas fontes.

## Análise de ameaças para jornalistas

A tabela abaixo tenta reunir os principals cenários de ameaças a um jornalista no Brasil.


| # | Adversários | O que querem? | O que podem fazer? | Como você pode se defender? |
| -------- | --------- | -------------------- | ----------------- | ---------------------------- |
| **1** | Autoridades e/ou governos | Nomes e detalhes das fontes de um jornalista | Ligar o jornalista à fonte usando metadados retidos em provedores ou outros prestadores de serviço de internet | [Cenário 1](#cenrio-1) |
| **2** | Autoridades e/ou governos | Nomes e detalhes das fontes de um jornalista | Ligar o jornalista à fonte por meio de vigilância direcionada ao profissional | [Cenário 2](#cenrio-2) |
| **3** | Autoridades e/ou governos | Nomes e detalhes das fontes de um jornalista | Ligar o jornalista à fonte tomando posse do computador ou do celular do profissional | [Cenário 3](#cenrio-3) |
| **4** | Autoridades e/ou governos | O conteúdo das conversas entre fonte e jornalista | Grampear a comunicação do jornalista | [Cenário 4](#cenrio-4) |
| **5** | Autoridades e/ou governos | O conteúdo das conversas entre fonte e jornalista | Monitorar a comunicação do jornalista usando um malware | [Cenário 5](#cenrio-5) |
| **6** | Autoridades e/ou governos | O conteúdo das conversas entre fonte e jornalista | Apropriar-se de um computador ou celular de um jornalista para ler arquivos, registros de conversas e histórico do navegador | [Cenário 6](#cenrio-6) |
| **7** | Hacking corporativo | Nome e detalhes das fontes e o conteúdo das conversas entre elas e os jornalistas | Monitorar as comunicações no computador do jornalista usando um malware | [Cenário 7](#cenrio-7) |
| **8** | Criminosos digitais | Senhas, dinheiro e informações bancárias do jornalista | Instalar ransomware (malware que cobra resgate de um computador) ou programas para roubar as informações usando falhas de segurança em navegadores, links maliciosos ou anexos em emails | [Cenário 8](#cenrio-8) |
| **9** | Bisbilhoteiro casual | Nada em particular | Divulgar quaisquer dados encontrados, como num pen drive perdido, ou um computador roubado | [Cenário 9](#cenrio-9) |

!!! **Metadados** são informações de acesso à internet, como registros de conexão e registros de acessos a sites

!! Novos [guias](../guias) são constantemente adicionados a este site, por isso continue checando a página

### Cenários de defesa

A seção abaixo detalha algumas ferramentas e práticas de acordo com as situações mencionadas na [análise de ameaças](#analise-de-ameacas-para-jornalis-...).

#### Cenário 1

Metadados são coletados e retidos em provedores por um ano no Brasil, e podem ser requisitados pro meio de ordem judicial ([Lei Noº 12.965/14](http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l12965.htm#art7)). Um projeto de lei em tramitação na Câmara ([PL 5074/2016](http://www.camara.gov.br/proposicoesWeb/fichadetramitacao?idProposicao=2082488)) pretende retirar a necessidade de ordem judicial para o acesso a esses dados para delegados e membros do Ministério Público. In this scenario, you have to leave as little footprint as possible. 

Este cenário imagina uma situação na qual você tem que (ou quer) deixar o mínimo de rastros possível. Para isso, recomendamos as seguintes ferramentas dos nossos [guias](../guias):

| Casos de uso | Recomendação |
| --------- | --------------- |
| Navegação na internet | **Como usar o navegador Tor** _(em breve)_ <br> **[Como escolher um mecanismo de buscas seguro](../guias/escolher-mecanismo-buscas-seguro)** |
| Email | _Não recomendado (mesmo com PGP)_ |
| Mensageiros instantâneos | **[Conversas seguras usando Ricochet](../guias/conversas-seguras-com-ricochet#)** |
| Chamadas de voz | _Ferramenta não existe_ |
| Chamadas de vídeo | _Ferramenta não existe_ |
| Mensagens de texto (SMS) | _Não recomendado_ |
| Trocas de arquivos | **[Troca de arquivos segura usando OnionShare](../guias/troca-segura-de-arquivos-com-OnionShare)** <br> **[Trocando mensagens e arquivos com GlobalLeaks](../guias/troca-arquivos-mensagens-globaleaks)** |

! O uso de **PGP** (sigla em inglês para "privacidade muito boa", um programa de encriptação de dados) é uma [boa forma de proteger o conteúdo](../guias#seguranca-de-email) das conversas entre duas partes, mas não esconde o fato de que elas existiram

#### Cenário 2

Neste cenário, o tráfego na internet do jornalista são ativamente monitorados. Suas comunicações por voz e por texto no celular também são. 

O objetivo é encriptar a informação e deixar o mínimo de metadados.

| Casos de uso | Recomendações |
| --------- | --------------- |
| Navegação na internet | **Como usar o navegador Tor** _(em breve)_ |
| Email | _Não recomendado (mesmo com PGP)_ |
| Mensageiros instantâneos | **[Conversas seguras usando Ricochet](../guias/conversas-seguras-com-ricochet#)** |
| Chamadas de voz | _Ferramenta não existe_ |
| Chamadas de vídeo | _Ferramenta não existe_ |
| Mensagens de texto (SMS) | _Não recomendado_ |
| Trocas de arquivos | **[Troca de arquivos segura usando OnionShare](../guias/troca-segura-de-arquivos-com-OnionShare)** <br> **[Trocando mensagens e arquivos com GlobalLeaks](../guias/troca-arquivos-mensagens-globaleaks)** |

#### Cenário 3

Este cenário considera situações em que computadores e celulares são tomados por alguém que quer obter seus arquivos, além de seus históricos de conversas e de navegação. Portanto, o objetivo é encriptar o armazenamento dos dispositivos, de modo que seus detalhes só possam ser acessados por aqueles que têm a senha correta.

Veja algumas sugestões:

* [**Criptografe seu HD usando BitLocker**](/guias/criptografe-seu-hd-bitlocker) no Windows
* [**Codifique seus dispositivos USB usando BitLocker**](/guias/criptografe-dispositivos-usb-bitlocker) no Windows
* **Encripte telefones Android** _(em breve)_
* **Definindo uma senha no iPhone** _(em breve)_

#### Cenário 4

Neste caso, o tráfego de internet no computador e celular do jornalista está sendo gravado e analisado. Ligações e mensagens de texto também são gravadas. O foco é ver o conteúdo da comunicação entre repórter e fonte. 

! Este cenário assume que a ligação entre o jornalista e a fonte não é secreto, por isso a retenção de [**metadados**](#cenrio-1) não é uma preocupação, apenas o conteúdo em si. O propósito das ferramentas listadas é encriptar a comunicação entre as duas partes.

| Casos de uso | Recomendações |
| --------- | --------------- |
| Navegação na internet | **Como usar o navegador Tor** _(em breve)_ <br> **Configurando uma VPN** _(em breve)_ |
| Email | **[Criptografar emails com PGP](../guias#seguranca-de-email)** |
| Mensagens instantâneas | **Como encriptar mensagens de texto** _(em breve)_ |
| Chamadas de voz | **Como encriptar ligações telefônicas** _(em breve)_ |
| Chamadas de vídeo | **[Chamadas de vídeo encriptadas de ponta-a-ponta com Wire](../guias/chamadas-video-criptografadas-ponta-a-ponta)** |
| Mensagens de texto (SMS) | **Como encriptar mensagens de texto** _(em breve)_ |
| Troca de arquivos | **[Trocas seguras de arquivos](../guias#troca-de-arquivos)** |
| Armazenamento de arquivos| **[Como armazenar arquivos de maneira segura na nuvem](../guias/armazene-arquivos-forma-privada-nuvem)** |
| Colaboração em equipe | **[Conversas seguras em equipe com Semaphor](../guias/conversas-seguras-equipe)** |

#### Cenário 5

Desde os [vazamentos do Hacking Team](https://pt.wikipedia.org/wiki/Hacking_Team#Vazamento_de_2015?target_blank) e do [FinFisher](https://en.wikipedia.org/wiki/FinFisher?target=_blank), ou de notícias a respeito do [FBI poder hackear qualquer computador em qualquer lugar](http://www.newsweek.com/supreme-court-allows-fbi-hack-any-computer-anywhere-if-warrant-454278?target=_blank), sabemos que certas autoridades governamentais têm a intenção de explorar computadores e smartphones para instalar backdoors neles.

!!! **Backdoors** são softwares que exploram falhas de segurança e permitem o acesso à máquina de maneira remota

Essas backdoors são instaladas sem o conhecimento e consentimento dos indivíduos, e monitoram praticamente toda a atividade do dispositivo. Isso inclui a gravação de áudio e vídeo, registro de todas as teclas que são pressionadas no teclado, gravar imagens da tela, recuperar o histórico de navegação e por aí vai. Uma vez que uma backdoor é instalada no computador ou no smartphone, praticamente todas as técnicas de proteção mostradas nos [guias deste site](../guias) se tornam inúteis.

! Se você suspeita que seu dispostivo está comprometido, a melhor opção é limpar definitivamente toda a informação ou fazer um reset de fábrica e reinstalar tudo a partir de mídias consideradas seguras

| Casos de uso | Recomendação |
| --------- | --------------- |
| Navegação na internet | Não segura se o computador/smartphone está comprometido |
| Email | Não seguro se o computador/smartphone está comprometido |
| Mensagens instantâneas | Não seguras se o computador/smartphone está comprometido |
| Chamadas de voz | Não seguras se o computador/smartphone está comprometido |
| Chamadas de vídeo | Não seguras se o computador/smartphone está comprometido |
| Mensagens de texto (SMS) | Não seguras se o computador/smartphone está comprometido |
| Troca de arquivos | Não segura se o computador/smartphone está comprometido |

Os objetivos nesse cenário os objetivos são os seguintes: impedir que esses softwares explorem seus dispostivos, compartimentar as suas atividades para que o estrago seja menor, detectar se há alguma anomalia no aparelho. Eis uam lista de ações recomendadas:

* ** Usar Tails e Qubes OS ** _(em breve)_
* ** [Como proteger seu PC de Backdoors](../guias/proteja-seu-pc-backdoors) **
* ** Compartimentalize seu trabalho** _(em breve)_
* ** Meu celular está comprometido? ** _(em breve)_

#### Cenário 6

Neste cenário, os dispositivos foram tomados à força para a extração de seus arquivos, históricos de conversas e históricos de navegação. Portanto, o objetivo é manter o armazenamento da informação encriptado, de modo que os detalhes só possam ser acessados quando a senha correta é inserida.

Esses guias são focados na segurança física:

* [**Criptografe seu HD usando BitLocker**](/guias/criptografe-seu-hd-bitlocker) no Windows
* [**Codifique seus dispositivos USB usando BitLocker**](/guias/criptografe-dispositivos-usb-bitlocker) no Windows
* **Dispostivos USB encriptados** _(em breve)_
* **Como encriptar telefones Android** _(em breve)_
* **Como definir uma senha no iPhone** _(em breve)_

#### Cenário 7

Este cenário é semelhante [Cenário 5](#cenrio-5), mencionado anteriormente. Empresas descontentes com suas reportagens investigativas podem contratar hackers para tentar rastrear suas fontes.

Tipicamente, hackers lhe mandarão links e arquivos especialmente construídos para instalar uma backdoor no seu computador. Como o alvo é especificamente você, eles não serão identificados pelos anti-vírus tradicionais.

Essas backdoors são instaladas sem o conhecimento e consentimento dos indivíduos, e monitoram praticamente toda a atividade do dispositivo. Isso inclui a gravação de áudio e vídeo, registro de todas as teclas que são pressionadas no teclado, gravar imagens da tela, recuperar o histórico de navegação e por aí vai. Uma vez que uma backdoor é instalada no computador ou no smartphone, praticamente todas as técnicas de proteção mostradas nos [guias deste site](../guias) se tornam inúteis.

! Se você suspeita que seu dispostivo está comprometido, a melhor opção é limpar definitivamente toda a informação ou fazer um reset de fábrica e reinstalar tudo a partir de mídias consideradas seguras

| Casos de uso | Recomendação |
| --------- | --------------- |
| **Navegação na internet** | Não segura se o computador/smartphone está comprometido |
| **Email** | Não seguro se o computador/smartphone está comprometido |
| **Mensagens instantâneas** | Não seguras se o computador/smartphone está comprometido |
| **Chamadas de voz** | Não seguras se o computador/smartphone está comprometido |
| **Chamadas de vídeo** | Não seguras se o computador/smartphone está comprometido |
| **Mensagens de texto (SMS)** | Não seguras se o computador/smartphone está comprometido |
| **Troca de arquivos** | Não segura se o computador/smartphone está comprometido |


Para se proteger, você deve compartimentalizar o trabalho para limitar o estrago. Além disso, você não deve nunca usar a mesma senha para contas diferentes. Uma autenticação em duas etapas deve ser usada em todos os lugares possíveis. Finalmente, um anti-vírus mais avançado pode ajudar a bloquear alguns dos arquivos maliciosos feitos especialmente para você.

* ** Usar Tails e Qubes OS ** _(em breve)_
* ** [Como proteger seu PC de Backdoors](../guias/proteja-seu-pc-backdoors) **
* ** Compartimentalize seu trabalho** _(em breve)_
* ** Meu celular está comprometido? ** _(em breve)_
* ** Armazenar senhas em carteiras para _passwords_ ** _(em breve)_
* ** Proteja suas contas com autenticação em duas etapas ** _(em breve)_

#### Cenário 8

Este é um pouco parecido com o [Cenário 5](#cenrio-5), com ad iferença de que o jornalista e a fonte não são especificamente o alvo. Cibercriminosos têm um negócio lucrativo ao infectar computadores vulnerávels com malwares (como para roubar informações bancárias) ou ransomwares (que encriptam os arquivos da vítima e exigem um resgate para liberá-los).

Portanto, uma ferramentas genéricas como um bom anti-vírus podem ser efetivos contra esse tipo de ataque.

* **[Proteja seu computador de backdoors](../guias/proteja-seu-pc-backdoors) **
* **Compartimentalize seu trabalho** _(em breve)_
* **Proteja suas contas com autenticação em duas etapas** _(em breve)_

#### Cenário 9

Este cenário cobre alguns casos em que seus dados vão parar nas mãos erradas, mas que o jornalista e a fonte não são exatamente o alvo. Exemplos de situações típicas são computadores ou pen drives perdidos, ou um smartphone roubado.

O objetivo é encriptar toda a informação para que o atacante casual não seja capaz de acessar os dados. Portanto,a s recomendações giram em torno de segurança física:

* [**Encripte seu HD usando BitLocker**](../guias/criptografe-seu-hd-bitlocker) no Windows
* [**Codifique seus dispositivos USB usando BitLocker**](../guias/criptografe-dispositivos-usb-bitlocker) no Windows
* **Dispositivos USB encriptados** _(em breve)_
* **Encripte telefones Android** _(em breve)_
* **Definindo uma senha no iPhone** _(em breve)_

## Leia mais

* [Uma introdução à modelagem de ameaças](https://ssd.eff.org/pt-br/node/64#uma-introdu%C3%A7%C3%A3o-%C3%A0-modelagem-de-amea%C3%A7as?target=_blank) parte do **'Guia contra vigilância'** da EFF, fundação que defende direitos civis no mundo digital 
* [Segurança da Informação](https://cpj.org/pt/2014/06/information-security.php?target=_blank) do **'Manual de Segurança para Jornalistas'** criado pelo Comitê para a Proteção de Jornalistas
* [Why every journalist should have a threat model (with cats)](https://onlinejournalismblog.com/2014/07/16/why-every-journalist-should-have-a-threat-model-with-cats/?target=_blank) - Guia básico para análise de ameaças (_em inglês_)
* [Security for Journalists, Part Two: Threat Modeling](https://source.opennews.org/en-US/learning/security-journalists-part-two-threat-modeling/?target=_blank) - Jonathan Stray, da escola de jornalismo de Columbia, fala sobre como se proteger em histórias sensíveis (_em inglês_)
* [Introduction](http://www.tcij.org/resources/handbooks/infosec/introduction?target=_blank) parte do **'Segurança da informação para jornalistas'** do Centro de Jornalismo Investigativo (_em inglês_)