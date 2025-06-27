# 🚗 Bilvask-simulering med JaamSim

## 📌 Om prosjektet
Dette prosjektet simulerer en bilvasktjeneste for å analysere og forbedre ventetid, kø og kapasitetsutnyttelse. Simuleringen er laget i **JaamSim** og gjenspeiler en reell tjeneste med maskinvask og to selvvaskstasjoner.

## 🛠 Hva modellen inneholder
- 🕐 Tilfeldig kundetilstrømming (eksponentialfordeling)
- 🧽 Valg mellom vanlig og premium vask
- ⚙️ Vedlikehold og teknisk feil (med ulik varighet og frekvens)
- ⛔ Balking – kunder forlater hvis køen er full
- 📊 KPI-er: ventetid, ressursbruk, kølengde og tapte kunder

## 🔬 Scenarioanalyse
Det er testet **fem ulike scenarioer** over én uke (160 timer), der faktorer som vedlikehold, nedetid, kølengder og ankomstintervall er endret for å se effekt.

### 🔍 Beste resultat: Scenario 4
- ⏱ Kortere ventetid
- 👥 Færre tapte kunder
- ⚖️ Jevnere ressursbruk og mindre overbelastning

## 🤖 Bruk av AI
**ChatGPT** ble brukt som støtteverktøy:
- Til å forme problemstillingen
- Lage komponentnavn i JaamSim
- Strukturere rapport og grafer

## ⭐ Bidra
Synes du prosjektet er interessant? Gi det en ⭐ eller del dine egne forslag til forbedringer!

