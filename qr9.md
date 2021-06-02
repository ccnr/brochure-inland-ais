# Wat zijn de meest voorkomende gegevensvelden van het Inland AIS-apparaat?

De gegevens die het Inland AIS-apparaat verzendt, moeten in overeenstemming met de daadwerkelijke situatie zijn. Op deze pagina staan daarom enkele tips voor schippers en wordt uitgelegd \(indien van toepassing\) waarvoor de gegevens worden gebruikt. Er is ook een [checklist](qr28.md) opgesteld die de schipper tijdens zijn dagelijkse activiteiten kan gebruiken.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Gegevensveld</th>
      <th style="text-align:left">Beschrijving</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Gebruikersidentificatie (MMSI-nummer)</b>
      </td>
      <td style="text-align:left">Het MMSI-nummer is het identificatienummer van het zendende Inland AIS-apparaat
        dat door de bevoegde telecommunicatieautoriteit wordt toegekend voor radiocommunicatieapparatuur
        aan boord. Het toegewezen MMSI-nummer wordt bij de installatie van het
        Inland AIS-apparaat ingevoerd door het erkend deskundig bedrijf. Aan de
        hand van dit nummer kan het schip in het verkeersmanagementsysteem van
        de autoriteiten worden ge&#xEF;dentificeerd en aan actuele reisgegevens
        worden gekoppeld.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Naam van het schip</b>
      </td>
      <td style="text-align:left">De naam van het schip wordt tijdens de installatie door het erkend deskundig
        bedrijf in het Inland AIS-apparaat ingesteld. Aan de hand van de naam kan
        de schipper andere schepen in zijn omgeving identificeren.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Scheeps- of samensteltype</b>
      </td>
      <td style="text-align:left">Het <em>scheeps- of samensteltype</em> wordt in de verkeersmanagementsystemen
        van de autoriteiten gebruikt om de samenstelling van een samenstel te identificeren
        en/of het gebruik van de sluizen te plannen. Inland AIS bevat een lijst
        van verschillende scheeps- en samensteltypen waaruit kan worden gekozen.
        Bij een samenstel kan het samensteltype van het vaartuig wijzigen afhankelijk
        van het aantal en het type gekoppelde duwbakken. Ook voor sommige schepen
        kan het type wijzigen. De schipper dient deze informatie voor elke reis
        te actualiseren.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>ENI-nummer</b>
      </td>
      <td style="text-align:left">Het ENI-nummer is het Uniek Europees scheepsidentificatienummer. Het wordt
        bij de installatie van het Inland AIS-apparaat ingesteld door het erkend
        deskundig bedrijf. In de verkeersmanagementsystemen van de autoriteiten
        wordt het ENI-nummer gebruikt om schepen te identificeren en aan hun actuele
        reisgegevens te koppelen.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Afmetingen</b>
      </td>
      <td style="text-align:left">
        <p>De afmetingen zijn de lengte over alles en de breedte over alles van het
          schip of samenstel. Voor een enkel schip worden deze waarden ingesteld
          door het erkend deskundig bedrijf tijdens de installatie van het Inland
          AIS-apparaat. Voor een samenstel moeten de waarden worden ingevoerd door
          de schipper overeenkomstig de afmetingen van het samenstel op dat moment.
          De schipper raadpleegt de informatie over de afmetingen van andere vaartuigen
          om ervoor te zorgen dat het ontmoeten en voorbijlopen op een veilige manier
          geschiedt.</p>
        <p>De autoriteiten gebruiken de informatie over de afmetingen in hun verkeersmanagementsystemen
          om het gebruik van de sluizen te plannen en/of voor VTS-diensten.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Positie</b>
      </td>
      <td style="text-align:left">De positie wordt gebruikt om het vaartuig op een kaart weer te geven.
        Deze positie-informatie geeft de werkelijke positie van de gps-antenne
        van het Inland AIS-apparaat aan boord van het vaartuig weer en wordt gebruikt
        door de andere schippers en de autoriteiten.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Snelheid over de grond</b>
      </td>
      <td style="text-align:left">
        <p>Het Inland AIS-apparaat verzendt de snelheid over de grond automatisch.
          Schippers gebruiken deze informatie om te bepalen of een schip zich verplaatst
          en tegen welke snelheid.</p>
        <p>Aan de hand van de snelheid over de grond kunnen de verkeersmanagementsystemen
          van de autoriteiten bepalen of een vaartuig in beweging is. Op deze manier
          kan een onderscheid worden gemaakt tussen vaartuigen die varen, en vaartuigen
          die afgemeerd liggen.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Koers</b>
      </td>
      <td style="text-align:left">Het Inland AIS-apparaat verzendt de koers van het vaartuig automatisch.
        De andere schippers en de autoriteiten gebruiken deze informatie om de
        vaarrichting van een schip te bepalen.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Vaarstatus</b>
      </td>
      <td style="text-align:left">De vaarstatus verstrekt informatie over de bedrijfstoestand van het vaartuig
        (bijvoorbeeld &#x201C;is onderweg op de motor&#x201D;, &#x201C;ligt voor
        anker&#x201D;, &#x201C;ligt afgemeerd&#x201D;). De schipper is verantwoordelijk
        voor het invoeren van de vaarstatus. In de verkeersmanagementsystemen van
        de autoriteiten wordt deze informatie gebruikt voor planningsdoeleinden.
        De informatie over de vaarstatus is misschien niet zo belangrijk voor de
        schipper, maar er wordt op gewezen dat een Inland AIS-apparaat dat &#x201C;is
        onderweg op de motor&#x201D; verzendt, veel meer time-slots voor het zenden
        vereist dan wanneer de vaarstatus is ingesteld op &#x201C;ligt afgemeerd&#x201D;.
        Met name in drukke zones (zoals havens) wordt het systeem minder belast
        als de vaarstatus wordt ingesteld op &#x201C;ligt afgemeerd&#x201D; wanneer
        een vaartuig daadwerkelijk is afgemeerd. De vaarstatus wordt ingevoerd
        door de schipper, maar sommige leveranciers (vooral fabrikanten van Inland
        ECDIS) voorzien de mogelijkheid om de vaarstatus (semi)automatisch in te
        stellen op basis van de snelheid over de grond. De schipper blijft echter
        verantwoordelijk voor de verzonden informatie.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Referentiepunt</b>
      </td>
      <td style="text-align:left">Het referentiepunt van een vaartuig is doorgaans de positie van de gps-antenne
        van het AIS-apparaat. Het referentiepunt wordt bij de inbouw van het Inland
        AIS-apparaat ingesteld door het erkend deskundig bedrijf. Het referentiepunt
        moet alleen worden gewijzigd voor samenstellen en dit in functie van de
        samenstelling ervan. Deze informatie wordt doorgaans aangepast samen met
        de afmetingen van het samenstel. Als het referentiepunt niet correct is
        ingesteld, wordt de werkelijke positie van het vaartuig mogelijk niet correct
        weergegeven.</td>
    </tr>
  </tbody>
</table>

