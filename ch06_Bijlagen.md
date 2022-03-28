# bijlagen

## Bijlage A: Afkortingen, begrippen en symbolen {#bijlage-a-afkortingen-begrippen-en-symbolen .list-paragraph}

  **Afkorting**   **Omschrijving**
  --------------- -------------------------------------------
  BAG             Basisregistratie Adressen en Gebouwen
  BRP             Basisregistratie Personen
  GEMMA           Gemeentelijke modelarchitectuur
  ICTU            ICT Uitvoeringsorganisatie
  KING            Kwaliteitsinstituut Nederlandse Gemeenten
  HR              Handelsregister
  NUP             Nationaal Uitvoeringsprogramma
  StUF            Standaarduitwisselingsformaat

**\
**

## Bijlage B : Geadviseerde Statussen {#bijlage-b-geadviseerde-statussen .list-paragraph}

*Diagram*

Op een terugmelding kunnen verschillende statussen van toepassing zijn.
In onderstaand figuur zijn de verschillende statussen en hun relatie
afgebeeld.

*Definities*

  naar                     *geen*   Gemeld   In behandeling   Ingetrokken   Onvoldoende informatie   Verkeerde Bronhouder   Ingepland   Afgehandeld   
  ------------------------ -------- -------- ---------------- ------------- ------------------------ ---------------------- ----------- ------------- --
  van                                                                                                                                                 
  *Geen*                            x                                                                                                                 
  Gemeld                                     x                x             x                        x                                                
  In behandeling                                              x                                                             x           x             
  Ingetrokken                                                                                                                                         
  Onvoldoende informatie                                                                                                                              
  Verkeerde Bronhouder              x                         x                                       x                                               
  Ingepland                                                                                                                             x             
  Afgehandeld                                                                                                                                         

  Eindstatus                                                                                                                                          
  overgang mogelijk        X                                                                                                                          

[^1]: De eHerkenningmiddelenleverancier stuurt een SAML token terug met
    daarin o.a. het 'OIN' zoals in de eHerkenningskoppelvlakstandaard is
    gespecificeerd. Dit 'OIN' met een prefix 00000003 is niet gelijk aan
    het door Logius uitgegeven OIN zoals in het OIN-register is
    opgenomen.

[^2]: Best Effort, beveiligd met tweezijdige TLS

[^3]: Best Effort, beveiligd met tweezijdige TLS en gesigneerde
    berichten

[^4]: Zie voorstel "foutafhandeling synchrone berichten" van de
    "gemeenschappelijke afspraken berichtstandaarden"
    <https://digistandaarden.pleio.nl/groups/profile/24027452/gemeenschappelijke-afspraken-berichtstandaarden-gab>

[^5]: Zie <http://www.w3.org/TR/2000/NOTE-SOAP-20000508> sectie 4.4.1
    voor uitleg

[^6]: Zie <http://www.w3.org/TR/2000/NOTE-SOAP-20000508> sectie 4.4.1
    voor uitleg
