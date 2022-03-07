# Fase 2. Een onderzoeksvraag formuleren

Noteer in dit document je ideeën voor een onderwerp en onderzoeksvraag. Je hoeft je nog niet te beperken tot één onderwerp! Schrijf verschillende ideeën uit, later kan je een definitieve keuze maken.

## Towards a digital Twin of the Ocean
### FAIR and open data sharing in support of healthy oceans, seas, coastal and inland waters
### ILIAD: Integrated Digital Framework FOR Comprehensive MARITIME DATA AND INFORMATION SERVICES    
the ILIAD DTO will fuse a large volume of diverse data, in a semantically rich and data agnistic approach to enable simultaneous communication with real world systems and models
### Enabling an operational, open and FAIR EOSC ecosystem (2022)    
https://www.ocean-twin.eu/    
https://www.oceandecade.org/actions/digital-twins-of-the-ocean-ditto/    
https://marine.copernicus.eu/news/ocean-and-its-digital-twin-whats-copernicus-marine    
https://www.blue-cloud.org/events/digital-twin-ocean    
https://unworldoceansday.org/events/the-digital-twin-ocean/    
https://www.mercator-ocean.eu/en/digital-twin-ocean/    
https://digitaltwinocean.mercator-ocean.eu/    
https://ec.europa.eu/info/sites/default/files/research_and_innovation/green_deal/gdc_stakeholder_engagement_topic_09-3_digital_ocean.pdf    
https://ec.europa.eu/info/research-and-innovation/funding/funding-opportunities/funding-programmes-and-open-calls/horizon-europe/eu-missions-horizon-europe/healthy-oceans-seas-coastal-and-inland-waters/european-digital-twin-ocean-european-dto_en    
https://cordis.europa.eu/project/id/101037643    
    
    lijkt moeilijk om concreet te maken, onderwerp is veel te breed
    
## Digisprong
### react native e-learning    
https://onderwijs.vlaanderen.be/sites/default/files/2021-07/VR%202020%201112%20DOC.1424_1QUATER.pdf    
https://www.klascement.net/    
https://www.i-learn.vlaanderen/    
https://www.i-learn.be/    
lijkt moeilijk om concreet te maken, welk doel kunnen we stellen, wat kan de valorisatie zijn in de context van een bachelorproef?

## Reading datafrom Huawei inverter SUN2000
### Huawei omvormer SUN2000 data uitlezen    
### Zonnepanelen omvormer data lokaal uitlezen    
https://community.openhab.org/t/reading-data-from-huawei-inverter-sun-2000-3ktl-10ktl-via-modbus-tcp-and-rtu/87670    
https://web-relays.com/en/blog/raspberry-pi-reading-data-from-huawei-inverter-sun-2000/    
https://github.com/sammachin/sun2000_rs485    
https://support.huawei.com/enterprise/en/doc/EDOC1100050690    
https://forum.huawei.com/enterprise/en/sun2000-smart-dongle-modbus-tcp-issues/thread/675885-100027    
https://forum.huawei.com/enterprise/en/modbus-tcp-connection-from-home-network-sun2000-8ktl-m0/thread/615790-100027    
https://forum.huawei.com/enterprise/en/sun2000-4k-tkl-inverter-modbus-tcp-connection/thread/603386-100027    
https://forum.huawei.com/enterprise/en/how-to-change-modbus-tcp-salve-id-from-0-to-1/thread/670233-100027    
    
    SMART
    *Specifiek: Lokaal de data van een zonnepanelen omvormer uitlezen. Concreet geval met operationele Huawei inverter SUN 2000. De applicatie connecteert met de omvormer over het netwerk.    
    De applicatie spreekt de API van de omvormer aan om de gegevens uit te lezen. De applicatie slaat de gegevens incrementeel op (geen duplicaten, enkel aanvullen ontbrekende gegevens tot op heden).    
    De gebruiker kan via de applicatie de gegevens opvragen en visualiseren.
    *Meetbaar: Gebruik van de applicatie moet de relevante gegevens weergeven. Deze kunnen vergeleken worden met de gegevens die beschikbaar zijn via de app van de fabrikant zelf.
    *Acceptabel: Zonnepanelen zijn meer en meer aanwezig in onze maatschappij. De beschikbaarheid van een geautomatiseerde applicatie die ten allen tijde de opbrengst bijhoudt en weergeeft lijkt een meerwaarde te bieden. Vooral wanneer we naast de opbrengst ook het verbruik integreren, zijn er zeer interessante analyses zoals de zelfconsumptie mogelijk die een gebruiker in staat stellen om de opbrengst van zijn zonnepanelen beter te begrijpen.
    *Realistisch: De applicatie lijkt mogelijk mits combinatie van verschillende klassieke technologieën waaronder netwerken, data science, applicatieontwikkeling
    *Tijdsgebonden: De onderzoeksvraag is zeer concreet en daarenboven ook schaalbaar. We kunnen een Minimal Viable Product definieren bestaande uit: 
    	*een connectie met de omvormer over het lokaan netwerk
    	*incrementeel data uitlezen
    	*data opslaan
    	*data visualiseren
    
    Dit kan verder uitgebreid worden met:
    	*opslaan op centrale server
    	*usability: smartphone app verbonden met lokale netwerk
    	*uitgebreide data science en visualisatie
    	*tijdreeksen


