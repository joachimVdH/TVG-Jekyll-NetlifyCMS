---
layout: page
title: Weeklessen
permalink: /weeklessen
---
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.4.0/dist/leaflet.css"
  integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA=="
  crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"
  integrity="sha512-QVftwZFqvtRNi0ZyCtsznlKSWOStnDORoefr1enyq5mVL4tmKB3S/EnC3rRJcxCPavG10IcrVGSmPh6Qw5lwrg=="
  crossorigin=""></script>

De lessen worden gegeven door Taijimeester Eddy Present, Anne-Marie Van den Bossche, Nancy Bevers en Marc Hermans. Ze worden langzaam en degelijk opgebouwd, zodat je de bewegingen ook thuis kan uitvoeren. Gemakkelijke, losse kledij en platte pantoffeltjes zijn aanbevolen. Iets om te drinken meebrengen is altijd verstandig.  

## Grimbergen

<!-- \\\[Download Agenda Grimbergen 2019-2020 - pdf - 47kb](/flyers/Grimbergen_2019-2020.pdf){:target="_blank"}   -->

[Charleroyhoeve, Lierbaan, Grimbergen](https://goo.gl/maps/zuG3MTbFtg82){:target="_blank"}\
Er is voldoende parkeergelegenheid (gratis) en er is vlakbij een bushalte.  

#### Maandag

* 18:45-20:15 : Vergevorderden door Anne-Marie Van den Bossche  
* 20:30-22:00 : Gevorderden  (3°deel) door Anne-Marie Van den Bossche  

#### Woensdag

* 18:45-20:15 : Vergevorderd door Nancy Bevers
* 20:30-22:00 : Beginners (1°deel) door Nancy Bevers  

#### Vrijdag

* 13:30-15:00 : Vergevorderd  door Eddy Present &amp; Anne-Marie Van den Bossche  
* 15:15-16:30 : Beginners (1°deel) door Anne-Marie Van den Bossche  
* 18:45-20:15 : Halfgevorderd (2°deel) door Anne-Marie Van den Bossche  
* 20:30-22:00 : Vergevorderd door Eddy Present &amp; Anne-Marie Van den Bossche  



## Mechelen

<!-- \\\[Download Agenda Mechelen 2019-2020 - pdf - 46kb](/flyers/Mechelen_2019-2020.pdf){:target="_blank"}   -->

[Basisschool "De Spreeuwen", Battelsesteenweg 259, Mechelen](https://maps.google.be/maps?q=51.030872,4.461348&hl=en&num=1&gl=BE&t=m&z=16){:target="_blank"}  

#### dinsdag

* 18:45-20:15 : Gevorderden  (3°deel) door Eddy Present &amp; Marc Hermans  
* 20:30-22:00 : Beginners (1°deel) door Eddy Present &amp; Marc Hermans  

#### donderdag

* 18:45-20:15 : Vergevorderd door Eddy Present &amp; Marc Hermans  
* 20:30-22:00 : Vergevorderd door Eddy Present &amp; Marc Hermans  



### Een proefles is steeds gratis en vrijblijvend.

### Lesgelden (BTW inbegrepen)

* per les van 1,5 uur = 13 &euro;
* per 10 beurtenkaart = 120 &euro; 
* jaarlijks lidgeld €15 (inclusief verzekering)
* 10 beurtenkaart wordt aangeschaft via overschrijving naar **BE88 9733 8425 6541** van de Taiji Vereniging Grimbergen met vermelding '**naam deelnemer**'
  Deze kaart is één kalenderjaar geldig. Op deze rekening kan je ook je lidgeld storten met de vermelding '**naam deelnemer + lidgeld**'.

Een factuur of een bewijs kan verkregen worden. Vraag informatie!

### Docenten

* Eddy Present 015 34 35 63 - eddy@taiji-vereniging-grimbergen.be

  Anne-Marie Van den Bossche 0488 56 50 99 - am@taiji-vereniging-grimbergen.be

  Nancy Bevers 0478 92 12 60 - nancy@taiji-vereniging-grimbergen.be

  Marc Hermans 0486 92 12 00 - marc@taiji-vereniging-grimbergen.be

<div id="mapid" style="width: 100%; height: 400px;"></div>
<script>
	var mymap = L.map('mapid').setView(\\\[50.9889,4.3807], 11);

```
L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
	attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
	maxZoom: 18,
	id: 'mapbox.streets',
	accessToken: 'pk.eyJ1Ijoiam9hY2hpbXZkaCIsImEiOiJjanR4MDh5b2oyNm5zNDRsbGF6cTM5bzh1In0.OpFnYagI-skcvKS3OxC65w'
}).addTo(mymap);

var markerGrimbergen = L.marker([50.93568, 4.37484]).addTo(mymap);
markerGrimbergen.bindPopup("Charleroyhoeve, Lierbaan, Grimbergen").openPopup();

var markerMechelen = L.marker([51.03067, 4.45947]).addTo(mymap);
markerMechelen.bindPopup("Basisschool De Spreeuwen, Battelsesteenweg 259, Mechelen").openPopup();
```

</script>