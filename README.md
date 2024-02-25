# Solar Router comparison to be used with Home Assistant

## MaxPV (previously EcoPV)

 <https://github.com/Jetblack31/MaxPV>

 evolution from EcoPV (<https://github.com/Jetblack31/EcoPV>)

* support MQTT and home assistant
* code on github
* PCB can be bought
* API to control router

## Routeur Profs'solaire

<https://sites.google.com/view/le-professolaire/routeur-professolaire>

* MQTT / Home assistant (sensor and control)
* community on Discord
* code drop
* can enable automatically water boiler at night based on solar routing during day

## Mon petit routeur Wifi / Clyric

<https://ota.apper-solaire.org/>
<https://github.com/xlyric/pv-router-esp32>

* **pro**
* PCB available
* support shelly with MQTT
* fully opensource (with source on github)
* timer available to bypass router during the night
* MQTT / Home Assistant data export
* **con**
* possible to send API call to control router

## F1ATB
  
  <https://f1atb.fr/fr/category/francais/domotique/photovoltaique/> (French)

  <https://f1atb.fr/category/english/home_automation/photovoltaic/> (English)

* **pro**
* very extensible
* can use shelly to measure current
* regular updates
* export sensor to MQTT / Home Assistant

* **con**
* source code is available but only as code drop, no git repository
* rely on a single contributor
* no forum, discussions with comments on the author website on each page
* MQTT integration is only exporting data, no way to control router

## domo rem81

<https://domo.rem81.com/index.php/2023/07/18/pv-routeur-solaire/>

  * done using esphome

## Arsun

 <https://arsun-concept.com/>

 *proprietary solution*

## Ard-tek MSunPV

<https://ard-tek.com/>

* fully autonomous
* configuration over wifi with proprietary app (Linux / Windows)
* already assembled

## Mk2 PV Routeur

<https://mk2pvrouter.com/>
old website <https://mk2pvrouter.co.uk/>

* fully autonomous
* no data export

## Tignous / Rolrider

<http://forum-photovoltaique.fr/viewtopic.php?f=110&t=40512>

* fully autonomous
* no control
* no Home Assistant export

## Atmega PV routeur

<https://oshwlab.com/valentincabanes82/atmega_pv_router_copy>

<https://forum-photovoltaique.fr/viewtopic.php?p=697017#p695263>

* fully autonomous
* MQTT data export