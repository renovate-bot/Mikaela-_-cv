---
versionString: 2023.14.0
date: 2023-04-06 11:01:00 +0300
categories: cvsuomeksi
redirect_from:
  - fi/index.html
  - index.html
---

<!-- https://workwithcarolyn.com/blog/digital-cv-guide
Due to having two different language versions, I need to be aware which state particular version is to keep them in sync, I have decided to use CalVer format YYYY.0W.MICRO (year.week.numberofEdit e.g. 2022.01.00).

Additionally more human readable date is provided for convenience of the reader for when I have made changes or confirmed the CV to still be up-to-date.

Internally both of these are provided in the YAML front matter and refer to variable on the bottom of the page.
-->

<!-- _{{ site.biosuomi }}_ -->

_Aminda Suomalainen on avointa lähdekoodia tukeva verkkopalveluylläpitäjä piraattipuolueessa._

**_[Google Translated into English](https://cv-aminda-eu.translate.goog/fi/?_x_tr_sl=fi&_x_tr_tl=en&_x_tr_hl=fi&_x_tr_pto=nui), proper [English version is planned](https://github.com/Mikaela/cv/issues/1)._**

🌍 Helsinki, Suomi / [email](mailto:suomalainen+cvfi@mikaela.info) /
[GitHub](https://github.com/Mikaela) / [GitLab.com](https://gitlab.com/Mikaela) /
[LinkedIn](https://www.linkedin.com/in/mikaelahmsuomalainen/) / [OpenHub](https://www.openhub.net/accounts/Mikaela)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Luottamustehtävät / vapaa-ehtoistyö](#luottamusteht%C3%A4v%C3%A4t--vapaa-ehtoisty%C3%B6)
- [IT-Taidot](#it-taidot)
- [Kielitaito](#kielitaito)
- [Työkokemus](#ty%C3%B6kokemus)
- [Koulutus](#koulutus)
- [Kurssit ja muu koulutus](#kurssit-ja-muu-koulutus)
- [Harrastukset](#harrastukset)
- [Yhteiskunnallinen ja poliittinen toiminta](#yhteiskunnallinen-ja-poliittinen-toiminta)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Luottamustehtävät / vapaa-ehtoistyö

- 10.2015-- _[Piraattipuolue r.p.](https://piraattipuolue.fi/)_
  - **Verkkopalveluiden- ja Pikaviestinten ylläpito** <!-- Pikaviestintiimi perustettiin virallisesti 27.03.2018, verkkopalveluiden selvitys 06.08.2019 ja IT-tiimi on ollut 11.12.2019 -->
  - _Suosittelija: [Utu Hopiavuori](https://www.hopiavuori.net/)_
  - Yhtenäistin piraattipuolueen IRC-kanavien hallinnan `Atheme`n `GroupServ`in
    alaisuuteen keskittäen pääsynhallinnan kymmenien eri kanavien omien listojen sijaan.
  - Ylläpidin puolueen kanavien yhdistämistä `IRC`stä `Slack`iin käyttäen `Slack`in
    `IRC-gateway`tä sen ollessa tuettu, sekä ylläpidin `Slack`-työtilaa.
  - Pystytin `TeleIRC`:n ja `Discord-IRC`:n, jotta piraattipuolueen viestintä kulkee
    `IRC`n, `Discord`in ja `Telegram`min välillä.
  - Avustan PirateIRC:n oper-tiimiä -verkon ylläpidossa kommunikoiden mm.
    Australian ja Ruotsin Piraattipuolueiden operaattoreiden kanssa, sekä
    käyttäjiemme kanssa (mm. Alankomaiden Piraattipuolue, Massachusetts:in piraattipuolue).
  - Toimin PirateIRC:n kontaktihenkilönä Intian Piraattien ylläpitämälle Matrix-sillalle,
    avustaen PirateIRC-päädyn asetusten kanssa, jotta silta voitiin pystyttää.
  - Suoritin siirtymän `TeleIRC`stä ja `Discord-IRC`stä `Matterbridge`en parempana
    ratkaisuna, jolloin `IRC` ei enää ole väliliima.
  - Ylläpidän `Limnoria`-instanssia, joka mm. seuraa `certificate transparency`-syötteitä, valvoo `Git-webhook`eja
    hakee linkitettyjen sivustojen otsikot helpottaen useiden `IRC`- ja `Matrix`-asiakasohjelmien käyttäjiä, jotka eivät
    hae linkkien otsikoita käyttäjän puolesta.
  - Asetin piraattipuolueen `Discord`-palvelimelle roolipohjaisen pääsynhallinnan,
    jotta kaikki kanavat eivät näy kaikille vaan työrauhaa kaipaaville kanaville
    pääsee kun käyttäjä on todettu asialliseksi.
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

## IT-Taidot

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

## Kielitaito

- suomi `🌟🌟🌟🌟🌟🌟` (äidinkieli)
- englanti `⭐⭐⭐⭐⭐⚫` (CEFRL: C1)
- esperanto `⭐⚫⚫⚫⚫⚫` (CEFRL: A1)

## Työkokemus

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

## Koulutus

- 08.08.2012 - 29.05.2015 _Etelä-Kymenlaakson ammattiopisto (Hamina)_
  - **Tieto- ja viestintätekniikan perustutkinto (käytön tuen koulutusohjelma), Datanomi**

## Kurssit ja muu koulutus

<!-- * 25.05.2015 - TIEKE: Tietokoneen käyttäjän A-kortti -->

- 25.05.2015 - TIEKE: Tietokoneen käyttäjän AB-kortti
- 16.09.2014 - CCNA Discovery: Working at a Small-to-Medium Business or ISP
- 28.04.2014 - CCNA Discovery: Networking for Home and Small Businesses

## Harrastukset

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

## Yhteiskunnallinen ja poliittinen toiminta

- Piraattipuolueen puoluevaltuusto
  - Varajäsen 26.09.2020-25.02.2021, varsinainen jäsen 25.02.2021-18.06.2022 <!-- 26.09.2020 eteenpäin on sama hallituskausi, kaksi varsinaista poistui, joten "päivitys" -->
- Piraattinuorten hallitus
  - Jäsen 2017-06.06.2018, varajäsen 2018-2019-01-11, 19.01.2020-18.12.2021
- Piraattipuolueen Helsingin piiriyhdistys, hallituksen varajäsen
  - 2017-2018, 2019-2021, 13.07.2022--
- Suomen autismikirjon yhdistys, hallituksen varajäsen
  - 14.04.2018 - 12.04.2019
- Piraattipuolueen kuntavaaliehdokas Helsingissä 2017

<!-- ## Suosittelijat

Lisätään tähän kun heitä on

-->

---

| Versio                   | Päiväys         |
| ------------------------ | --------------- |
| {{ page.versionString }} | {{ page.date }} |
