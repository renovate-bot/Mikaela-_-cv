---
layout: default
title: CV in English
versionString: 2023.14.0
date: null
categories: cvinenglish
draft: true
published: false
---

_{{ site.bioenglish }}_

🌍 Helsinki, Finland / [email](mailto:suomalainen+cvfi@mikaela.info) /
[GitHub](https://github.com/Mikaela) / [GitLab.com](https://gitlab.com/Mikaela) /
[LinkedIn](https://www.linkedin.com/in/mikaelahmsuomalainen/) / [OpenHub](https://www.openhub.net/accounts/Mikaela)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Positions of trust / volunteering](#positions-of-trust--volunteering)
- [IT-Skills](#it-skills)
- [Language skills](#language-skills)
- [Work experience](#work-experience)
- [Education](#education)
- [Courses and other education](#courses-and-other-education)
- [Hobbies](#hobbies)
- [Societal and political activities](#societal-and-political-activities)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Positions of trust / volunteering

- 10.2015-- _[Pirate Party Finland](https://piraattipuolue.fi/en)_
  - **Web service and instant messenger administration** <!-- Instant messenger team was officially founded 27.03.2018, documenting web services on 06.08.2019 and IT team since 11.12.2019 -->
  - _Recommender: [Utu Hopiavuori](https://www.hopiavuori.net/)_
  - I unified access control of pirate party's IRC channel to `Atheme GroupServ` rather than having dozens of channels managed separately.
  - I administered connecting channels belonging to the party between `IRC` and `Slack` while the `IRC gateway` was supported. I also administered the Slack workspace.
  - I setup `TeleIRC` and `Discord-IRC` so the party's communications move between `IRC`, `Telegram` and `Discord`.
  - I help PirateIRC oper team in maintaining the network and communicating with the operators (from countries including Australia and Sweden) and users (including Pirate Parties from the Netherlands and Massachusetts).
  - I am PirateIRC contact person to Matrix bridge maintained by Indian Pirates and support with settings on the PirateIRC end so the bridge setup was possible.
  - I executed migration from `TeleIRC` and `Discord-IRC` to `Matterbridge` which was a better solution in which `IRC` is no longer the glue in the middle.
  - I maintain a `Limnoria` instance that amongst other things follows `certificate transparency` feeds, monitors `Git webhooks` and fetches titles from linked websites easening the use of `IRC` and `Matrix` clients that don't show link previews.
  - I setup `role based access control` to the party Discord server so all channels aren't visible instantly and those channels desiring peace for working are only displayed once the user has been decided to be appropiate.
  - TODO TODO TODO TODO TODO
  - Avustan piraattipuolueen verkkopalveluiden ylläpidossa mukaanlukien
    (`Debian`- ja `Ubuntu`-) käyttöjärjestelmien päivityksessä, `systemd`-yksiköiden
    kirjoittamisessa, sekä ohjelmistojen päivittämisessä.
  - Avustan sähköpostiohjausten, sekä postituslistojen luomisessa ja päivittämisessä `CPanel`illa.
  - Avustan puolueen `Nextcloud`-instanssin ylläpidossa luoden tarpeen vaatiessa käyttäjätunnuksia puolueen
    aktiiveille.
  - Pystytin piraattipuolueelle `Matrix`-huoneita, sekä -avaruuksia, jotta
    puolueen pikaviestintään pääsee osallistumaan myös sieltä `Discord`-tyylisellä
    manuaalisella pääsynhallinnalla.
  - Kommunikoin Itävallan piraattipuolueen kanssa, Suomen piraattipuolueen `matterbridge` käyttää heidän `Matrix`-palvelintaan
    ja ylläpidän `Matterbridge`llä toistinta heidän vetämässään kansainvälisten piraattipuolueiden keskustelukanavalla (Global Pirates)
    heidän `Mattermost`-palvelimellaan, `Matrix`issa, `Telegram`missa, `Discord`issa, `PirateIRC`ssä.
  - Avustin PirateIRC-verkkoa siirtymisessä neljästä `Charybdis`-`IRC`-palvelimesta ja
    `Atheme IRC`-palveluista modernimpaan `Ergo IRCd`-ratkaisuun, joka yhdistää IRC-palvelimen
    ja IRC-palvelut.
  - Kommunikoin aktiivisesti puolueen käyttämien ohjelmistojen upstreamin kanssa,
    erityisesti `Charybdis`:ksen, `Atheme`n, `Ergo`n, `Limnoria`n ja `Gitea`n kanssa.
  - Suomensin käyttämämme `TLG_JoinCaptchaBot`in.
- 19.03.2020 - 04.01.2022 _[Federated Networks Association ry (Feneas)](https://feneas.org/)_
  - **Komitean jäsen**
  - Avustan yhä yhdistyksen lakkauttamisen jälkeenkin Feneaksen Matrix-huoneiden ylläpidossa, sekä keskustelen yhteisön
    kanssa.
  - Avustin välillä `Matrix`-palvelimen tai `Element`-asiakasohjelman päivittämisessä
    avaamalla `merge-requeste`jä `GitLab`in `Ansible-playbook`eja kohtaan.
  - Olen Feneaksen ryhmäkontakti [LiberaChat] -IRC-verkolle kommunikoiden
    molemmin puolin mikäli [LiberaChat]in kanssa on ongelmia tai toiseen suuntaan,
    rekisteröin Feneaksen nimiavaruuden kanavia heidän verkossaan, toimin kanavaoperaattorina
    ja vastaan `vhost`ien pyytämisestä jäsenillemme näyttämään heidän yhteytensä
    yhdistykseen.
- 02.04.2019 - 19.04.2020, 07.10.2021-23.11.2021 _[Privacy Guides](https://privacyguides.org/)_
  - **Tiimin jäsen**
  - Osallistuin keskusteluihin `GitHub`issa, `issues`- ja `discussions`-osioissa, sekä
    asetin niille `label`eita helpottaen niiden lajittelua, sekä löytämistä jatkossa.
  - Arvioin `pull request`eja.
  - Osallistuin erityisesti salatun DNS-osion luomiseen keräten tietoja ratkaisuista
    (`DNS over HTTPS`, `DNS over TLS`, `DNSCrypt`) ja seuraan niiden kehittymistä mielenkiinnolla.
  - Osallistuin tiedonhakuun ehdotetuista sovelluksista ja palveluista, arvioiden sopivatko
    ne projektin kriteereihin.

[LiberaChat]: https://libera.chat/

## IT-Skills

- Linux-ylläpito vuodesta 2008
  - Arch Linux, Debian, (Ubuntu, ) Fedora, SailfishOS
  - systemd (`system/user unit`s (palvelut, ajastimet), networkd, resolved, timesyncd…)
  - OpenSSHd, CUPS tulostuspalvelu, UFW-palomuuri
  - Chrony aika-palvelin
- Git
  - GitHub/GitLab/Gitea/Forĝejo orgaisaatiot, issue tracker, labelit
  - GitLab/Gitea/Forĝejo -repojen peilaus
  - GitHub/Gitlab pages
- DNS
  - DNSSEC, zone-hallinta, Unbound
  - DNS-over-HTTPS (iOS 14 ja Windows 11 -asiakkailla) ja DNS-over-TLS (Android, systemd, Unbound -asiakkailla)
- IPv6
  - SixXS, Tunnelbroker, radvd, radvdump, Yggdrasil
- Windows Server
  - Active Directory, Group Policy…
- IRC
  - Charybdis+Atheme, Ergo -palvelut ja -palvelimet
  - KiwiIRC, Gamja -selainpohjaiset asiakasohjelmat
- WordPress -ongelmanratkaisu
- bash-skriptaus, ks. [Mikaela/Scripts](https://gitea.blesmrt.net/mikaela/scripts)
- MySQL-perusteet
- $\LaTeX$ -perusteet, ks. [Mikaela/gist:in LaTeX-hakemisto](https://gitea.blesmrt.net/mikaela/gist/src/branch/master/LaTeX)

## Language skills

- Finnish `🌟🌟🌟🌟🌟🌟` (native)
- English `⭐⭐⭐⭐⭐⚫` (CEFRL: C1)
- Esperanto `⭐⚫⚫⚫⚫⚫` (CEFRL: A1)

## Work experience

- 13.09.2021-28.11.2021 _Digitalents Academy_
  - **Työkokeilu**
  - Loin GitHub-pages pohjaisen CV:n (cv.aminda.eu).
  - Tutustuin `Python`in ja `JavaScript`in perusteisiin.
  - Tutustuin pintapuolisesti `Flask`-web-frameworkiin.
  - Avustin muita työkokeilijoita `git`in käytössä.
- 03.2020 - 09.2020 _[Unicus Finland](https://unicus.com/fi/)_
  - **Työkokeilu**
  - Valmistauduin _ISTQB Foundation Level_-kokeeseen.
  - Tutustuin pintapuolisesti ohjelmointiin mm. `Python 3`:lla, `Ruby`llä, `Go`lla.
  - Tutustuin `Firefox`in kehittäjätyökaluihin, erityisesti saavutettavuustesteihin.
  - Tutustuin _Web Content Accessibility Guidelines_ -ohjeistukseen sekä saavutettavuustestaamiseen,
    ja opin miten saavutettavuus auttaa myös minua itseäni.
- 28.10.2019 - 19.12.2019 _Robuntu Osk_
  - **Työkokeilu**
  - Suoritin moninaisia askareita osuuskunnan tukitoiminnoissa.
  - Avustin osuuskunnan palveluiden markkinoinnissa tutustumalla `Thunderbird`-laajennuksilla
    tapahtuvaan massaviestintään asiakkaille, sekä `Facebook Marketplace`en.

## Education

- 08.08.2012 - 29.05.2015 _Etelä-Kymenlaakson ammattiopisto (Hamina)_
  - **Tieto- ja viestintätekniikan perustutkinto (käytön tuen koulutusohjelma), Datanomi**

## Courses and other education

<!-- * 25.05.2015 - TIEKE: Tietokoneen käyttäjän A-kortti -->

- 25.05.2015 - TIEKE: Tietokoneen käyttäjän AB-kortti
- 16.09.2014 - CCNA Discovery: Working at a Small-to-Medium Business or ISP
- 28.04.2014 - CCNA Discovery: Networking for Home and Small Businesses

## Hobbies

- Tietoturva, seuraan alan uutisia ja verkkoyhteisöjä (IRC, Matrix) jatkuvasti
- "Ohjelmistotestaus", löydän usein käyttämistäni ohjelmista ongelmia tai
  puuttuvia ominaisuuksia ja selkeän ongelmanraportointikanavan ollessa olemassa
  myös ilmoitan siitä.
  - Käyttäjätunnuksen vaativa listaus avaamistani [issueista muiden GitHub-repoihin](https://github.com/issues?q=is%3Aissue+author%3AMikaela+-user%3AMikaela),
    [GitLab.com:issa](https://gitlab.com/dashboard/issues/?scope=all&state=all&author_username=Mikaela).
- Puoluetoiminta, olen aktiivinen Piraattipuolueessa ja kun Helsingissä kampanjoidaan
  olen mukana avustamassa kampanjoinnissa mm. keskustellen ihmisten kanssa,
  jakaen flaikkuja, keittäen kahvia, tai avustamassa vaalikontin ruudun diaesitysten
  käynnistämisessä
- Kielet
- 11.07.2014-- Mikaela.info, 114077943.xyz ja Aminda.eu -kotisivuni ylläpito ja blogin kirjoitus
  - **Webmaster** <!-- https://en.wikipedia.org/wiki/Webmaster vahvistaa termin olevan ok -->
  - Rekisteröin domainin `Gandi`lla, käytin pitkään `Cloudflare`n `DNS`-palveluita
    ennen siirtymistäni takaisin `Gandi`n omaan palveluun, johon tuli tänä aikana
    myös `DNSSEC`-tuki.
  - Ylläpidän sivua `GitHub-pages`issa, kirjoitin sen alunperin `HTML+CSS`, siirtyen
    myöhemmin `Jekyll` -`CMS`ään, joka generoi staattisia sivuja.
  - Kirjoitan sivustolle blogiini moninaisista aiheista, kuten elämästäni ja
    teknisemmistä aiheista, kuten `IRC`- ja `Matrix`-protokollista.
  - Pohdin sivun `issue tracker`issa usein mitä voisin parantaa, mitä voisin
    blogata ja usein sisällytän mukaan pääpiirteittäin mistä haluan kirjoittaa.
- Lukeminen
- Lokalisointi
  - Ylläpidän suomennoksia `FluffyChat`- (19.11.2021--) ja `Nheko`- (04.04.2022--) -`Matrix`-asiakasohjelmissa `Weblate`-käännöstyökalulla. Matrixin ulkopuolella
    olen suomentanut `TLG_JoinCaptchaBot`in (11.04.2022--), joka torjuu roskapostitusta
    Telegram-ryhmissä.
  - Keskustelen muiden kääntäjien kanssa alkuperäisten viestien
    merkityksestä, miten ne on käännetty muille kielille tai mitä erityistä
    merkitystä niillä tarkoitetaan.
  - Seuraan Matrix Suomen keskusteluita ja palautetta käännöksestä.
  - Tuen myös sovellusten käyttäjiä niiden omilla tukikanavilla.

## Societal and political activities

- Piraattipuolueen puoluevaltuusto
  - Varajäsen 26.09.2020-25.02.2021, varsinainen jäsen 25.02.2021-18.06.2022 <!-- 26.09.2020 eteenpäin on sama hallituskausi, kaksi varsinaista poistui, joten "päivitys" -->
- Piraattinuorten hallitus
  - Jäsen 2017-06.06.2018, varajäsen 2018-2019-01-11, 19.01.2020-18.12.2021
- Piraattipuolueen Helsingin piiriyhdistys, hallituksen varajäsen
  - 2017-2018, 2019-2021, 13.07.2022--
- Suomen autismikirjon yhdistys, hallituksen varajäsen
  - 14.04.2018 - 12.04.2019
- Piraattipuolueen kuntavaaliehdokas Helsingissä 2017

---

| Version                  | Date            |
| ------------------------ | --------------- |
| {{ page.versionString }} | {{ page.date }} |
