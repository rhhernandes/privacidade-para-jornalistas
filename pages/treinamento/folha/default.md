---
title: 'Treinamento Folha'
visible: true
content:
    items: '@self.children'
    limit: '5'
    order:
        by: date
        dir: desc
    pagination: '1'
    url_taxonomy_filters: '1'
---

# Folha - Técnicas para proteger suas fontes digitalmente

_Raphael Hernandes - abril/2017_

Um computador pode ser comprometido de muitas formas. E, se isso acontecer, o sigilo de suas fontes e a sua própria privacidade estarão ameaçadas. 

Com o crescente número de ameaças, veja algumas formas de se proteger. Você não precisa saber programar, ser um hacker ou qualquer coisa assim para garantir um pouco mais de segurança.


## Por que me importar?

As ameaças são muitas e crescentes. Você pode já ter sido vítima de hacking e nem saber, além disso, certamente já esteve em contato com algum arquivo malicioso. Veja exemplos de situações.

#### Você já foi vítima de hacking?

* [haveibeenpwned.com](https://haveibeenpwned.com/) - Site para verificar se alguma de suas contas em sites populares já foi exposta
* Ataques de "homem no meio" (_man in the middle_) interceptam sua comunicação com modem
	* Pode ser associado a outras técnicas, como fazer uma rede pública falsa pra as pessoas se conectarem

Veja uma simulação de dados de acesso ao IVC sendo interceptados. Nesse caso, o acesso foi feito no próprio computador, mas é possível direcionar o tráfego de outras máquinas e roubar seus dados:

<iframe src="https://drive.google.com/file/d/0B39oFN-pSo5hMzJmV2FFbUktQms/preview" width="640" height="480"></iframe>

__A dificuldade de atacar__

Um software completo para espionagem de celulares, voltado a um uso "caseiro", custa R$ 37 por mês: <br> ![Site espião oferece planos completos por pouco dinheiro](ss-mspy.png?lightbox&resize=800)

#### Casos reais

Casos no Brasil mostram decisões judiciais para extrair informações, como no caso do [Blog da Cidadania](http://www1.folha.uol.com.br/colunas/monicabergamo/2017/03/1868346-pf-conduz-coercitivamente-blogueiro-ligado-a-esquerda.shtml). Mais comuns são as quebras de sigilo telefônico, como os contra uma [ex-jornalista da Folha](http://www1.folha.uol.com.br/poder/2016/11/1836918-juiz-de-sao-paulo-manda-quebrar-sigilo-telefonico-de-jornalista.shtml) e a um [colunista da Época](http://epoca.globo.com/tempo/noticia/2016/10/ameaca-imprensa-juiza-quebra-sigilo-telefonico-de-jornalista-de-epoca.html) no fim do ano passado.

[Relatório](https://necessaryandproportionate.org/pt/country-reports/brazil) encabeçado pela Electronic Frontier Foundation fala da falta de transparência com os dados que são coletados nas conexões com a internet no Brasil.

!!! **No exterior:** contas e sites estrangeiros como AP, BBC e Forbes já foram vítimas de ataques para roubo de informação de leitores e para divulgação de informações falsas. <br> ![Hackers usaram conta do E!](ss-e.jpg?lightbox&resize=400) <br> ![BBC também foi vítima de hackers](ss-bbc.jpg?lightbox&resize=400)


## Análise de ameaças

Para se proteger de forma eficiente e viver sem paranoia devemos analisar as ameaças que nos rondam e montar formas de defesa adequadas.

A segurança pode usar algumas ferramentas especiais, mas a boa segurança não vem dos softwares. Vem de pensar e analisar o processo. Um bom plano deve diminuir as chances do adversário e minimizar os efeitos caso ele tenha sucesso. Não existe método universal, por isso é importante pensar na situação. Caso a caso.

! **Custo:** segurança custa tempo, dinheiro e conveniência. Há uma balança em jogo: se a dificuldade para monitorar pesar menos do que o custo para fazê-lo, você terá problemas. É bom desde já elucidar que não existe método completamente seguro. Se o seu adversário tem recursos, motivação e tempo em abundância (como uma NSA, mas eu duvido muito que seja o caso), fica bem difícil se defender 

#### Modelo de análise de ameaças

* O que você não quer que os outros saibam?
* Por que alguém iria querer saber isso? Quem?
* Como alguém pode conseguir essa info?
* O que acontece se o atacante vencer?

!! **Possíveis consequências de um ataque:** publicação de informações falsas, phishing a partir do seu e-mail, acesso a informações sensíveis, perda de reputação ou confiança.

!!!! _[**Leia mais** sobre análise de ameaças](https://onlinejournalismblog.com/2014/07/16/why-every-journalist-should-have-a-threat-model-with-cats/), em inglês_

#### Conheça o seu adversário

O adversário mais óbvio é o assunto da sua matéria. Pode também ser qualquer pessoa com algum tipo de interesse financeiro ou político, concorrentes, criminosos ou até trolls.

!! **O perigo vai muito além do hacking:** existem problemas muito mais prováveis, como alguém roubar seu laptop ou conseguir um mandado judicial. Ataques com malwares, backdoors, quebras de senha ou hacking são mais difíceis. 

#### Algumas possibilidades de problemas

**Hacking**
* Malwares
* [Backdoors](https://privacidadeparajornalistas.org/guias/proteja-seu-pc-backdoors) – que extraem toda a informação do computador, como tudo o que foi digitado, gravam a tela, ligam a webcam, e muito mais.


**Ataques legais**
* Quebras de sigilo – bastante comuns no Brasil

**Furtos** – _se alguém roubar seu computador, suas informações estão seguras?_

**Engenharia social** _– não necessariamente vem sozinha. São ações focadas no ser humano e em suas vulnerabilidades_
* Phishing – envio de emails falsos para coletar informações
* Papagaio de pirata – será que não tem ninguém de olho no que você digita?


|Email de phishing: | Em aproximadamente 12h, mais de 350 pessoas clicaram no link: | Outro site de phishing, enviado por email, imita o Santander: |
|----|----|----|
| ![Email de phishing recebido, entre outros lugares, na Folha](phishingsantander.png?lightbox&resize=300) <br>  | ![Em 12h ativo, mais de 300 pessoas clicaram no link](phishingresultado.png?lightbox&resize=300)  | ![Outro site de phishing enviado para o email da Folha imita o Santander](Phishing2.png?lightbox&resize=300) | 



## Conceitos básicos

**Defense in depth –** também conhecido como abordagem do castelo, diz que é importante ter redundância na segurança. Não é porque meu computador tem antivírus que não preciso criptografar meus dados. São várias camadas de segurança.

**Transferência de pacotes -** Na internet, as informações são passadas de ponto em ponto até chegar ao destino. Você faz um pedido para o servidor, o pacote sai do seu computador, passa por seu modem, vai para o provedor… Pode ser interceptado e lido nesse meio tempo

**Lei Noº 12.965/14 Art. 13 -** Na provisão de conexão à internet, cabe ao administrador de sistema autônomo respectivo o dever de manter os registros de conexão, sob sigilo, em ambiente controlado e de segurança, pelo prazo de 1 (um) ano

**Metadados -** Informações de acesso à internet, como registros de conexão e ou de acessos a sites. Podem estar fora da internet, como informações de quem criou um arquivo de Word. Foi por um erro nisso que, em 2012, a [Vice entregou a localização](https://www.wired.com/2012/12/how-vice-got-john-mcafee-caught/) do programador e especialista em segurança John McAfee. Na época ele era procurado pela polícia e metadados numa foto publicada pelo site revelaram sua localização

**Data at rest x Data in motion –** importante lembrar que nem todos os dados estão em trânsito. Alguns estão simplesmente guardados em algum lugar. A gente tende a se esquecer deles.

## Como se defender
_Técnicas e práticas simples para proteção_

#### Boas senhas
São duas opções: usar um gerenciador ou criar um bom protocolo

Gerenciador pode ser o [LastPass](https://www.lastpass.com/). O problema é que se ele for violado, vai tudo de uma vez. Pode-se também criar um método para montar uma boa senha, diferente em todos lugares.

**Exemplo de protocolo (não use esse)**

Senha de uma conta no Facebook: __040204F@+1650MzEs@mDmCh!__
* **040204** - Data de fundação do site
* **F@** - Duas primeiras letras do nome
* **+1650** - Código telefônico do país e da área da sede da empresa
* **MzEs@mDmCh** - Iniciais dos fundadores
* **@!** - Letra “A” substituída por @ e adicionado um “!” 

!!! **Reuso:** o mesmo protocolo pode ser aplicado a outros sites (no Twitter seria _210306Tw+1415JdNgBsEw!_). Seriam senhas diferentes, mas não seria necessário decorar todas elas, só a forma de gerar elas usando o protocolo.

#### Autenticação em duas etapas

Camada extra de segurança. O seu banco provavelmente usa isso.

* **turnon2fa.com -** Site gratuito com tutoriais para a ativação de autenticação em duas etapas
* **Authenticator –** App do Google que gerencia os autenticadores. Para [Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=pt_BR) e [iOS](https://itunes.apple.com/br/app/google-authenticator/id388497605?mt=8)

![Authenticator mostra códigos para acesso em duas etapas](ss-autheticator.jpg?lightbox&resize=300)

#### Boas práticas

**Use um bom anti-vírus**
* [Kaspersky](https://www.kaspersky.com.br/home-security?ksid=cac7b062-ae4d-4f74-a8cf-c0509d7cb87d&ksprof_id=64&ksaffcode=90564&ksdevice=c&gclid=CjwKEAjw5_vHBRCBtt2NqqCDjiESJABD5rCJJzuWufPtRQn2NMjV5JJnNLD-5tZpjJnbIb7jcEM7yBoCXNrw_wcB) Internet Security (pago)
* [Bitdefender](https://www.bitdefender.com/media/html/2017/cl25off/?pid=50off&cid=ppc|c|Google|50off&gclid=CjwKEAjw5_vHBRCBtt2NqqCDjiESJABD5rCJG7OsV3Dgg2BdmbB9412L1jNPvkp7NY3kPLWb2ujtKRoC8Jnw_wcB) (pago)
* [Panda](http://www.pandasecurity.com/brazil/homeusers/solutions/free-antivirus/) e [Avast](https://www.avast.com//pt-br/index) (se for para pagar, prefira os outros, mas esses têm boas versões grátis)

**Mantenha sistema e softwares atualizados**

**Criptografia de discos**
* [Windows](https://privacidadeparajornalistas.org/guias/criptografe-seu-hd-bitlocker) 
* [Mac](https://support.apple.com/pt-br/HT204837) 
* [Linux](https://gitlab.com/cryptsetup/cryptsetup)
* [Android](http://www.androidauthority.com/how-to-encrypt-android-device-326700/)
* [iPhone](https://ssd.eff.org/pt-br/module/como-encriptar-seu-iphone)
* [Dispositivos USB](https://privacidadeparajornalistas.org/guias/criptografe-dispositivos-usb-bitlocker)

**HTTPS**
* Segurança no browser. Criptografa a comunicação. A URL começa com _http**s**://_.

**Apagar arquivos corretamente** - Excluir um arquivo não significa que ele foi destruído. Pode ser recuperado. Para evitar isso:
Use o recurso "Secure Empty Trash", no Mac
* E o [erase free space](https://support.apple.com/pt-br/HT201949) pra garantir
No Windows
* [Eraser](http://eraser.heidi.ie/) para arquivos específicos
* [CCleaner](https://www.piriform.com/CCLEANER) para limpar o espaço geral

! **Cuidado:** esse método não é 100% seguro. Por isso, é bom usar nomes genéricos em arquivos mais sensíveis. Em vez de salvar um arquivo com o nome "Lista de pessoas que receberam propina", prefira algo como "discurso de fim de ano".

**Remover metadados**
[Scrubbing](https://www.cnet.com/how-to/remove-metadata-from-office-files-pdfs-and-images/)  

! **Método ainda mais seguro:** se possível, em vez de mandar o documento ou a foto original, tire um print da tela e use ele. É mais garantido.

**Compartimentalização**
Dependendo, pode ser uma boa ideia compartimentalizar tanto as pessoas que sabem de todo o processo de apuração (cada um sabe só o que precisa saber) e onde você guarda as coisas (uma parte dos arquivos em um lugar, outra parte em outro)

**Guardar senhas**
Não guarde o papel onde anotou a senha que destrava o seu computador/celular junto da máquina ou em lugar de fácil acesso.

**Celulares**
São um desastre, pois armazenam e compartilham todo o tipo de informação o tempo todo. Considere a possibilidade de deixá-lo em casa. 

No mínimo tem que ter uma senha. Bom também usar criptografia nos arquivos, disponível em Android e iOS nas configurações do dispositivo.

!!!! **Stalkers:** um político alemão fez o teste e pediu que uma telecom lhe enviasse as informações que tinham registradas sobre ele. Os dados foram repassados para um jornal local que produziu uma [visualização bem interessante](http://www.zeit.de/datenschutz/malte-spitz-data-retention) desses dados. Rolou um TED também: <br> <br> <iframe src="https://embed.ted.com/talks/malte_spitz_your_phone_company_is_watching" width="640" height="360" frameborder="0" scrolling="no" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

#### Algumas ferramentas
**Signal, Cryptocat e [Wire](https://privacidadeparajornalistas.org/guias/chamadas-video-criptografadas-ponta-a-ponta)**
* Ferramentas para chat
* Deixam metadados

[**Tor**](https://www.torproject.org/)
* Navegador anônimo, mas não esconde o fato de que você está usando ele, o que por si só [pode ser revelador](https://www.forbes.com/sites/runasandvik/2013/12/18/harvard-student-receives-f-for-tor-failure-while-sending-anonymous-bomb-threat/#679b17205457)
* Não faça login em nada!

[**PGP**](https://privacidadeparajornalistas.org/guias#seguranca-de-email)
* Para criptografar emails


**[Ricochet](https://privacidadeparajornalistas.org/guias/conversas-seguras-com-ricochet) e [OnionShare](https://privacidadeparajornalistas.org/guias/troca-segura-de-arquivos-com-OnionShare)**
* Para conversas e trocas de arquivos, respectivamente
* Não deixam metadados


[**Sync**](https://privacidadeparajornalistas.org/guias/armazene-arquivos-forma-privada-nuvem)
* Armazenamento com protocolo de conhecimento-zero (ele só armazena seu arquivo, criptografado, e não sabe o que está guardando)

## O Plano

Lembre-se de pensar no adversário e montar pequenas receitas para resolver cada parte do problema. Os melhores planos para se defender são simples. Um bom plano vai responder as seguintes perguntas:

* Como as partes vão se comunicar?
* Quem terá acesso a essa informação? Como?
* Quais ações são cruciais para que isso fique seguro?
* Será necessário se encontrar pessoalmente? Como vocês vão organizar isso? Onde vão se encontrar?
* Onde a informação confidencial está armazenada fisicamente? Quantas cópias tem?
* Quem tem acesso físico ao equipamento? Considere escritórios, servidores, cartões de memória, etc.
* Qual a política de arquivamento e para deletar esses dados? Não cria backup automático em algum lugar? É apagado de forma segura?
* Qual parte da informação pode ser divulgada na reportagem e qual parte deve ficar confidencial?
* E os telefones? O registro das localizações pelo GPS é um problema?
* Você configurou o seu equipamento para ficar da forma mais segura possível? Por exemplo, lembrou de desligar o GPS e o backup do chat?
* Quais questões legais também podem se tornar problemas de segurança nesse caso?
* Consultou um advogado? Precisa?
* O plano tem algum problema ético? Todas as partes estão cientes dos riscos?
* Se houver uma grande falha de segurança, você teria como lidar com as consequências?
* Quem é o grande responsável para que o plano dê certo?
* Como esse plano será repassado para todas as partes?
* Ele é apropriado? Todos têm os conhecimentos e habilidades necessárias para ele funcionar?
* Você vai ter que treinar os interessados ou oferecer exercícios de prática?
* Onde que alguém pode cometer um erro? O que acontece se ele for cometido?

## Links úteis e contato

Veja no [Privacidade para Jornalistas](https://privacidadeparajornalistas.org/) uma lista de [links úteis](https://privacidadeparajornalistas.org/links-uteis) com mais informações pra se manter protegidos. 

Se precisarem de ajuda, estou sempre pela Folha, na editoria de Audiência e Dados (me chamo Raphael). Podem falar comigo por [email](mailto:r@privacidadeparajornalistas.org), [Twitter](https://twitter.com/rhhernandes) ou [Facebook](https://www.facebook.com/henriqueraphael) também.