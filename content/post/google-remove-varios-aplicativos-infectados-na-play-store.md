---
title: "Google remove aplicativos infantis com adware da Play Store"
date: 2020-03-24T08:19:18-03:00
images: ["crianca-calular.jpg"]
categories: ["android, hackers"]
description: "Depois de mais de um milhão de downloads, os aplicativos infectados pelo Tekya foram removidos."
tags: ["Privacidade","Segurança","Android"]
authors: ["Leandro Pelegrini"]
draft: false
---

Depois de mais de um milhão de downloads, os aplicativos infectados pelo Tekya foram removidos.
<!--more-->
O Google tem lutado por anos para impedir que aplicativos maliciosos entrem na Play Store, mas uma nova rodada de _takedowns_ está se destacando no desafio de controlar o problema. No início de março, o Google removeu 56 aplicativos que pareciam benignos, mas foram contaminados com _adware_. Eles já foram baixados mais de um milhão de vezes.

Enquanto mais da metade dos aplicativos afirmavam ser utilitários benignos, como calculadoras, ferramentas de tradução ou aplicativos de culinária — aplicativos comuns para _adware_ —, 24 eram especificamente direcionados para crianças. Essas ofertas chamativas, como quebra-cabeças e jogos de corrida, são uma maneira particularmente lamentável para os fraudadores colocarem _malware_ em mais dispositivos de vítimas. Pesquisadores da empresa de segurança _[Check Point](https://www.checkpoint.com/pt/ "Site ChekPoint - Português")_ divulgaram descobertas sobre os aplicativos para o Google como parte de uma pesquisa contínua sobre como os _hackers_ ocultam e distribuem _malware_ no Google Play. E eles estão [publicando detalhes](https://research.checkpoint.com/2020/google-play-store-played-again-tekya-clicker-hides-in-24-childrens-games-and-32-utility-apps/ "Anúncio CheckPoint - Inglês") sobre o _adware_ hoje.

"Como os pais têm a tendência de dar seus dispositivos para seus filhos brincarem, atrair crianças para instalar aplicativos maliciosos é um vetor de ataque proeminente para alcançar dispositivos de adultos", diz Aviran Hazum, gerente de pesquisa móvel da Check Point. "A maioria das crianças não tem o entendimento de rejeitar aplicativos."

O _Adware_ é uma ameaça móvel de longa data, mas os fraudadores ficaram particularmente mais ativos nos últimos meses. A empresa de detecção de ameaças _[Malwarebytes](https://press.malwarebytes.com/ "Blog MalwareBytes - Inglês")_ encontrou em um estudo anual que o _adware_ "reinou supremo" em 2019 como a ameaça mais comum em dispositivos Android, Macs e Windows. No início deste mês, a empresa de antivírus Avast [publicou descobertas](https://press.avast.com/adware-accounts-for-72-of-all-mobile-malware "Anúncio Avast - Inglês") que o _adware_ especificamente representou 72% de todo o _malware_ do Android entre outubro e dezembro do ano passado. E além do Android, todas as plataformas parecem estar lutando para reduzir o risco para os usuários. A Microsoft [anunciou no final de fevereiro](https://blogs.windows.com/msedgedev/2020/02/27/protecting-users-potentially-unwanted-apps/ "Anúncio Microsoft - Inglês"), por exemplo, que seu navegador Edge começaria a digitalização e bloqueio de downloads de _adwares_ por padrão.

{{< figure src="/images/apps-android.jpg" alt="Foto aplicativos android">}}

O _adware_ nos aplicativos contaminados foi projetado para minar o mecanismo "_MotionEvent_" do Android. Os desenvolvedores de aplicativos usam isso para reconhecer movimentos como toques e gestos de vários dedos e coletar informações sobre eles, como suas coordenadas na tela em espaço bidimensional e tridimensional. O _MotionEvent_ ajuda os aplicativos a interpretar essas entradas de usuário a responder em conformidade. O _adware_, que a _Check Point_ chama de _Tekya_, estava manipulando essas entradas para simular usuários tocando anúncios.

Os pesquisadores observaram Tekya criando cliques falsos para gerar receita de redes de anúncios, incluindo Facebook, Unity, AppLovin', e Google AdMob. O _Adware_ manipula o ecossistema de anúncios para ganhar dinheiro para _hackers_, fazendo parecer que um exército de usuários tem visto e interagido com os anúncios. Muitos dos 56 aplicativos infectados que a _Check Point_ identificou não eram apenas utilitários benignos, mas, na verdade, clones de aplicativos legítimos destinados a confundir os usuários e aumentar a chance de que eles acidentalmente baixassem a versão maliciosa — como um jogo falso do Stickman, e versões de Hexa Puzzel e Jewel Block Puzzle. O grupo também incluiu um leitor de PDF falso.

Tekya esconde sua funcionalidade abusiva em uma camada fundamental de aplicativos. Conhecida como "código nativo"," esta parte dos pacotes de software é notoriamente difícil de verificar como componentes maliciosos.

A empresa tem trabalhado ativamente para conter o fluxo de aplicativos maliciosos no Google Play — realizando [takedowns coordenados](https://www.wired.com/story/google-android-chamois-botnet/ "Takedowns coordenados - Inglês") em larga escala e desenvolvendo ferramentas de detecção expandidas para capturar mais fraudes durante o processo de avaliação da Play Store. A empresa até pediu ajuda externa na guerra contra aplicativos maliciosos.

Com mais de 3 milhões de aplicativos no Google Play e centenas de novas submissões a cada dia, porém, ainda é desafiador para o Google detectar tudo. Mesmo que seja relativamente fácil para os fraudadores criarem e espalharem esses aplicativos, o Google vai continuar encontrando formas de removê-los.

---
Foto de Diego Passadori no Unsplash \
Foto de Rami Al-zayat no Unsplash \
Fonte: [Wired](https://www.wired.com/story/google-removes-tekya-adware-kids-apps/ "Wired")