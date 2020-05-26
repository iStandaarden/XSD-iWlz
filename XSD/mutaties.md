# iWlz Release 2.2 - xsd

* [iWlz2.2-v0.1](https://github.com/iStandaarden/iWlz-Xsd/releases) - iWlz Release 2.2 Versie 0.1 - concept
  * nieuwe (concept) xsd's voor iWlz Release 2.2 - voor een volledig overzicht van de wijzigingen zie informatiemodel

  * alle berichten:
    * namespace 2_1 naar 2_2
    * berichtSubversie van 1 naar 2

  * basisschema.xsd
    * nieuw:
      * LDT_Besluitnummer
      * 2 nieuwe codes aan LDT_Leveringsstatus
      * LDT_LeveringsstatusClassificatie
      * 1 nieuwe code aan LDT_Leveringsvorm
      * 2 nieuwe codes aan LDT_ToeslagOverig
      * 1 nieuwe code aan LDT_VoorkeurClient
      * nieuwe retourcodes
    * verwijderd:
      * LDT_JuridischeStatus
      * vervallen retourcodes verwijderd

  * io31.xsd
    * verwijderd:
      * JuridischeStatus
    * gewijzigd:
      * Besluitnummer is LDT_Besluitnummer ipv LDT_Nummer

  * aw33.xsd / zk33.xsd
    * verwijderd:
      * JuridischeStatus
    * gewijzigd:
      * Besluitnummer is LDT_Besluitnummer ipv LDT_Nummer

  * aw35.xsd / zk35.xsd
    * nieuw:
      * GeleverdZorgzwaartepakket/Behandeling
    * verwijderd:
      * GeleverdeFunctie/Leveringsstatus

  * aw39.xsd / zk39.xsd
    * nieuw:
      * MutatieZorgzwaartepakket/LeveringsstatusClassificatie
      * Aanvraag/Instelling
    * verwijderd:
      * MutatieFunctie/Leveringsstatus

  * aw317.xsd
    * nieuw:
      * Leveringsstatus/LeveringsstatusClassificatie

  * zk31.xsd
    * nieuw:
      * ToegewezenZorgzwaartepakket/LeveringsstatusClassificatie
    * verwijderd:
      * JuridischeStatus
      * ToegewezenFunctie/Leveringsstatus
    * gewijzigd:
      * Besluitnummer is LDT_Besluitnummer ipv LDT_Nummer

  * ca317.xsd / ca319.xsd
    * verwijderd:
      * Geboortedatum
