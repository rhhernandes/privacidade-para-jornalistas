# Privacidade para Jornalistas

Repositório com conteúdo do site [**Privacidade para Jornalistas**](https://privacidadeparajornalistas.org/). 

O convite para colaborar se estende a toda a comunidade: jornalistas, profissionais da área de segurança da informação ou qualquer outro interessado. 

Todo o conteúdo do **Privacidade para Jornalistas** está licenciado sob [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Isso significa que ele pode ser copiado, distribuído e transformado para qualquer propósito, inclusive comercial, desde que acompanhado do devido crédito e de indicações sobre eventuais mudanças. 

O projeto foi originado a partir do [Privacy for Journalists](https://privacyforjournalists.org.au/), da [CryptoAUSTRALIA](https://cryptoaustralia.org.au/).

O PPJ também está disponível no [Facebook](https://www.facebook.com/privacidadeparajornalistas/) e no [Twitter](https://twitter.com/privacidadeJorn/).

## Sobre o repositório

Este repositório é _exclusivamente_ para tratar do _conteúdo_ do **Privacidade para Jornalistas**. Caso não seja familiarizado com o GitHub, tenha dúvidas quanto ao conteúdo aqui disposto ou queira contribuir de outra forma, entre em contato com [contato@privacidadeparajornalistas.org](mailto:contato@privacidadeparajornalistas.org). 

O **PPJ** opera no CMS open-source [Grav](https://getgrav.org). Ele tem algumas peculiaridades e funcionalidades interessantes, descritas abaixo. 

## Como contribuir

No repositório do **PPJ** estão as páginas, [guias](https://privacidadeparajornalistas.org/guias) e [posts de blog](https://privacidadeparajornalistas.org/blog) do site. Os textos usam a linguagem markdown e o formato *.md. 

Importante: o nome do arquivo de texto deverá ser "default.md".

O conteúdo fica dividido em subpastas dentro da pasta de sua respectiva seção no site (por exemplo, o guia [Conversas seguras com Ricochet](https://privacidadeparajornalistas.org/guias/conversas-seguras-com-ricochet) está em “[Pages > 02.guias > 01.conversas-seguras-com-ricochet](https://github.com/rhhernandes/privacidade-para-jornalistas/tree/master/pages/02.guias/01.conversas-seguras-com-ricochet)”). 

Imagens, vídeos e quaisquer outros conteúdos a serem hospedados deverão ser incluídos na mesma pasta em que o texto.

Uma vez feito o _pull request_, a sugestão de melhoria (seja ela uma correção em conteúdo atual ou envio de conteúdo novo) será analisada pela administração do site e, uma vez aceita, já poderá ser vista no **Privacidade para Jornalistas**.

### Organização do _default.md_

Antes do texto, é importante (embora não obrigatório) preencher as _metas_ para os robôs de redes sociais. Coloque-as antes do texto, com três hífens (---) no começo e no fim. Exemplo:

```
---
title: 'Conversas seguras com Ricochet'
metadata:
    author: 'NOME DO AUTOR (se desejar)'
    description: 'DESCRIÇÃO CURTA DO TEXTO'
    'og:title': 'TÍTULO DO TEXTO | Privacidade para Jornalistas'
    'og:type': article
    'og:description': 'DESCRIÇÃO CURTA DO TEXTO'
    'og:image': 'URL PARA IMAGEM DE COMPARTILHAMENTO NO FACEBOOK'
    'twitter:card': summary_large_image
    'twitter:site': '@privacidadeJorn'
    'twitter:creator': 'SE DESEJAR, COLOQUE SEU @ NO TWITTER'
    'twitter:title': 'TÍTULO DO TEXTO| Privacidade para Jornalistas'
    'twitter:description': 'DESCRIÇÃO CURTA DO TEXTO'
    'twitter:image': 'URL PARA IMAGEM DE COMPARTILHAMENTO NO TWITTER'
taxonomy:
    category:
        - Se for um tutorial, nome da categoria em que se encaixa nos [guias do PPJ](https://privacidadeparajornalistas.org/guias)
    tag:
        - Tags para classificar o assunto, por exemplo, "windows"
        - Sinta-se à vontade para adicionar mais de uma tag
---
# Título do texo
Texto...
```

A partir daí basta seguir o texto usando linguagem _markdown_.

Para mais informações sobre a linguagem adotada pelo Grav, acesse a [documentação](https://learn.getgrav.org/content/markdown).

#### Imagem

Para adicionar uma imagem, como elas estarão anexadas diretamente na pasta do texto, basta incluir o nome do arquivo.

```
![Algum nome para a imagem](nomedoarquivo.png)
```

##### Recorte automático de imagem

Graças ao plugin [Featherlight](https://github.com/getgrav/grav-plugin-featherlight), podemos fazer um recorte automático da imagem por meio de lightbox. Basta adicionar os parâmetros após o nome do arquivo:

```
![Algum nome para a imagem](nomedoarquivo.png?lightbox=1024&cropResize=600,600)
```

Não sinta obrigação de usar, mas fica _tão_ melhor...

#### Tabela de conteúdos

Um recurso bacana para guias mais longos é a tabela de conteúdos (table of contents), semelhante à usada na Wikipedia. Um exemplo pode ser visto [neste texto](https://privacidadeparajornalistas.org/guias/escolher-mecanismo-buscas-seguro).

Para incluir uma dessas tabelas no texto, basta adicionar a tag _[TOC]_, toda em caixa alta. Exemplo:

```
# Título do texto
[TOC]
E aqui começa o texto...
```
