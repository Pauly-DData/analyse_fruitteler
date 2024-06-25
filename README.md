# analyse_fruitteler
In deze repo zal ik aan de hand van aangeleverde data en data uit onze eigen db een mooie analyse neerzetten voor een potentële klant.


1. Begrijp de Basisgegevens
Totaal Opgewekte Energie: 900.000 kWh
Zelf Verbruikte Energie: 450.000 kWh
Totaal Verbruik: Tussen 1.400.000 kWh en 1.500.000 kWh
Aansluitingen: 1 Grootverbruik (GV) en 2 Kleinverbruik (KV)
Huidig Energiecontract: Tot 31-12-2024 met van Helden Energie

2. Data Verzamelen en Analyseren
Ik importeer het uurwaardebestand met de verbruiksgegevens van vorige week.
Ik controleer de kolommen:
Totale import van het net
Afname van bewaarkoelcellen (niet schakelbaar)
Afname van werkmateriaal (sorteermachine etc.)
Schakelbaar volume

3. Energieverbruik Visualiseren
Ik maak een lijngrafiek van het energieverbruik per uur over de dag van de vorige week.
Ik visualiseer de schakelbare volumes en de niet-schakelbare volumes in de grafiek.

4. Onbalans Analyse
Ik bereken de onbalans per uur (verschil tussen opgewekte energie en verbruikte energie).
Ik visualiseer de onbalans in een aparte grafiek.

5. Besparingsmogelijkheden
Ik simuleer een dynamisch afgerekend energiecontract:
Hoe zou de klant betalen als hij voor een dynamisch contract kiest?
Ik bereken de mogelijke besparingen door gebruik te maken van het schakelbare volume en onbalans.

6. Offerte Opmaken
Ik bepaal de kostenbesparingen door gebruik te maken van de dynamische tariefstructuren.
Ik vergelijk de huidige kosten met de verwachte kosten onder het nieuwe contract.
Ik stel een duidelijke en overzichtelijke offerte op met de verwachte besparingen.

Concrete Eerste Analyse Stappen:
Inlezen van de gegevens:
Ik importeer de uurdata van vorige week in een analyse tool zoals Excel of Python (bijv. pandas).
Data opschonen en verwerken:
Ik zorg dat de data goed gestructureerd is.
Ik splits de data op in de verschillende kolommen zoals aangegeven.
Lijngrafiek maken:
Ik maak een lijngrafiek waarin ik het totale verbruik, de niet-schakelbare afname, de schakelbare afname, en de import van het net over de tijd laat zien.
Onbalans berekenen:
Ik bereken de onbalans per uur.
Ik visualiseer deze onbalans in een grafiek.
Schakelbaar volume analyseren:
Ik bekijk de mogelijkheden van het schakelbare volume in relatie tot de onbalans en verbruikspatronen.
Kostenbesparing berekenen:
Ik gebruik historische en verwachte energieprijzen om de besparingen te simuleren.
Ik bereken de mogelijke besparingen bij een dynamisch afgerekend energiecontract.