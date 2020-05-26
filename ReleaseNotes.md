# Release Notes

## iWlz Release 2.2

* [iWlz2.2-v0.1](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.2 Versie 0.1 - concept
  * nieuwe (concept) xsd's voor iWlz Release 2.2 - voor een volledig overzicht van de wijzigingen zie informatiemodel
  * overzicht xsd wijzigingen in: [mutaties.md](https://github.com/iStandaarden/iWlz-Xsd/../../../../XSD/mutaties.md)

## iWlz Release 2.1

* [iWlz2.1-v1.2.1](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.1 Versie 1.2.1 - 31 maart 2020
  * Nieuwe versie IO31: XsdVersie 1.0.2
    * Achtergrond: element Besluitnummer heeft een pattern gekregen die waarde 0(nul) niet mogelijk maakt.

* [iWlz2.1-v1.2](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.1 Versie 1.2.0 - 3 oktober 2019
  * Nieuwe versie basisschema: XsdVersie 1.1.0
    * Retourcodes toegevoegd
    * ZZP codes toegevoegd t.b.v. ggz
    * BasisschemaXsdMinVersie = 1.0.0
    * BasisschemaXsdMaxVersie = 1.1.0

  * Nieuwe versies van berichtschema's
    * appInfo gewijzigd: BasisschemaXsdVersie 1.1.0
    * Voor alle berichten m.u.v. ZK35/ZK36 en ZK39/ZK310:
      * BerichtXsdVersie = 1.0.1
      * BerichtXsdMinVersie = 1.0.0
      * BerichtXsdMaxVersie = 1.0.1
    * Voor ZK35/ZK36:
      * BerichtXsdVersie = 1.1.1
      * BerichtXsdMinVersie = 1.0.0
      * BerichtXsdMaxVersie = 1.1.1
    * Voor ZK39/ZK310:
      * BerichtXsdVersie = 1.1.1
      * BerichtXsdMinVersie = 1.1.0
      * BerichtXsdMaxVersie = 1.1.1  

* [iWlz2.1-v1.1](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.1 Versie 1.1.0 - 29 augustus 2019
  * Nieuwe versie voor ZK35 en ZK39 - berichtversie 1.1.0
    * ZK35/ZK36: klasse GeleverdZorgzwaartpakket aangevuld met een optioneel element Etmalen (conform AW35:GeleverdZorgzwaartepakket)
    * ZK39/ZK310: klasse Aanvraag aangevuld met een optioneel element Etmalen + optioneel element Afgiftedatum (conform AW39:Aanvraag)

* [iWlz2.1-v1.0](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.1 Versie 1.0.0 - 3 juli 2019
  * Alle xsd's nieuw gepubliceerd met wijzigingen voor iWlz 2.1
  * AW33/AW34
  * AW35/AW36
  * AW39/AW310
  * AW317/AW318
  * IO31/IO32
  * ZK31/ZK32
  * ZK33/ZK34
  * ZK35/ZK36
  * ZK39/ZK310
  * CA317/CA318
  * CA319/CA320
  * basisschema.xsd

## iWlz Release 2.0.x

* [iWlz2.0-v1.9](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0.2 versie 1.9 - 22-05-2019 - iWlz 2.0.2
  * nieuwe publicatie van ZK31/ZK32 bericht
  * Belangrijkste wijziging, 1 client per bericht, opname van relatie- en contactgegevens.

* [iWlz2.0-v1.8](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0.2 versie 1.8 - 20-12-2018
  * basisschema: ten behoeve van TR108/TR109/TR110/TR111 (allen van toepassing op het ZK31 bericht) bijbehorende retourcodes toegevoegd aan de codelijst.

* [iWlz2.0-v1.7](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0.1 versie 1.7 - 3 juli 2018
  * AW317 / AW318: binnen de klasse &lt;Client> is &lt;VolgnummerClient> vervangen door &ltBSN>
  * overige xsd's blijven ongewijzigd

* [iWlz2.0-v1.6](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0.1 Versie 1.6 - 5 juni 2018
  * basisschema.xsd: enumeratie gewijzigd op LDT_ExtraKostenThuis t.b.v. revisierelease 2.0.1
  * overige xsd's blijven ongewijzigd

* [iWlz2.0-v1.4](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0 Versie 1.4 - 18 april 2018
  * basisschema.xsd: element Huisnummertoevoeging:
    * Het pattern (<xs:pattern value="(\[A-Z0-9\])+"/>) dat alleen hoofdletters of cijfers zijn toegestaan is verwijderd van LDT_Huisnummertoevoeging.
    * Het pattern dat geen leeg element toestaat (geen whitespaces), blijft gehandhaafd
  * overige xsd's blijven ongewijzigd

* [iWlz2.0_v1.3](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0 Versie 1.3 - 30 maart 2018
  * AW317.xsd/AW318.xsd: nieuw optioneel element &lt;Opname>
    * Het element &lt;Opname> is toegevoegd aan de klasse \[WachtlijstZorgzwaartepakket\].
  * overige xsd's blijven ongewijzigd

* [iWlz2.0_v1.2](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.0 versie 1.2 - 19-12-2017
  * intiele versie
  * nieuw bericht: ZK31/ZK32 - verhuisbericht

## iWlz Release 1.2

* [iWlz1.2_v1.2](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 1.2 versie 1.2 - 31-10-2016
  * bijgewerkt basisschema
    * LDT_Telefoonnummer pattern value aangepast en minLength
    * LDT Commentaar pattern restrictie aangepast

* [iWlz1.2_v1.1](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 1.2 versie 1.1 - 19-09-2016
  * bijgewerkt basisschema
    * LDT_Voorletters en LDT_Telefoonnummer zijn voorzien van restrictie

* [iWlz1.2_v1.0](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 1.2 versie 1.0 - 01-07-2016
  * Xsd's voor iWlz Release 1.2
  * Berichten io35/io36 zijn niet meer van toepassing

## iWlz Release 1.1

* [iWlz1.1_v1.0](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 1.1 versie 1.0 - 26-8-2015
  * Xsd's voor iWlz Release 1.1
  * Datum in productie: 1 januari 2016
  * wijziging Namespace van "zorgregistratie.nl" naar "iStandaarden.nl"

## iWlz Release 1.0

* [iWlz1.0_v1.0](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 1.0 versie 1.0 - 09-07-2015
  * Initiele versie xsd's voor iWlz Release 1.0.
  * Datum in productie: niet
