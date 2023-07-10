# Projekat Digitalne Pedale za Audio Efekte

## Uvod
Ovaj dokument predstavlja opis projekta digitalne pedale za gitarske audio efekte. Projekat ima za cilj razvoj digitalnog sistema koji će obraditi audio signal koristeći digitalni signalni procesor (DSP) i omogućiti korisnicima da prilagode i kombinuju efekte putem aplikacije na mobilnom telefonu. Rezultirajući audio signal se šalje do pojačala ili zvučnika.

## Istorija i Motivacija
Ideja za ovaj projekat proistekla je iz istraživanja modifikacija gitara, posebno dodavanja pasivne distorzije pomoću diode clipping-a. Ovo je podstaklo razmišljanje o tome kako se relativno lako i pristupačno može implementirati širok spektar efekata i zvukova na gitarski signal. Nakon analize različitih pristupa, došao sam do zaključka da bi digitalna obrada signala uz pomoć mikrokontrolera bio najoptimalniji izbor.

## Rešenje
Nakon razmatranja različitih platformi za DSP, odlučio sam se za upotrebu Teensy mikrokontrolera. Teensy mikrokontroleri su slični Arduino platformi, sa dodatnim prednostima koje ih čine idealnim za ovu namenu. U poređenju sa Raspberry Pi, Teensy mikrokontroleri pružaju napredne mogućnosti obrade zvuka i real-time clock funkcionalnost koja je od suštinskog značaja za ovakve projekte. Kao rešenje, planiram koristiti Teensy verzije 4.0 ili 4.1, koje su posebno dizajnirane za audio primene.

Kako bih ostvario kvalitetan ulaz i izlaz zvuka, planiram koristiti audio shield koji će biti povezan sa Teensy mikrokontrolerom. Ovaj dodatak omogućava visokokvalitetnu reprodukciju i snimanje zvuka, pružajući veći stepen kontrole nad audio signalom. Imajući u vidu trenutnu nestašicu čipova koja je uticala na proizvodnju Teensy verzije 3.x, smatram da će jeftinija opcija, poput Teensy 4.0 sa audio shield-om, biti najbolji izbor.

## Link ka grafičkom interfejsu

https://github.com/GnuPixie/DSPedal_Avalonia
