# Infomatik-logbog
Her er min mega seje infomatik logbog som mark bliver mega glad for

## grundforløbet

I grundforløbet har jeg lavet en app på applab, hvor vi har lavet en hifi prototype af en app tilbilmærket astonmartin, her havde vi stort fokus på:

- Målgruppe analyse
- De 5 gestaltlove
  - Loven om- nærhed, lighed, lukkethed, forbundethed og firgur og bagrunde
- Bruger test
  - Tænke højt test
- En god bruger opblevelse
- Hi-Fi og Lo-Fi prototyper

## kodning

Efter vi startede i vores studieretningsklasse, havde vi et forløb om programering, her havde vi stort fokus på:

- At lære at læse og skrive kode
  - Lære at skrive i p5js (Java script)
  - lære basis syntax
  - lære at skrive kommentar i koden
- Lære at lave og aflæse flowcharts
- lære om data typer
  - int (alle tal da java script ikke skælner mellem hele tal og komma tal)
  - boolean (sandt eller falsk / 1 eller 0)
  - str (tekst)
-variabler (et navn der kan have en bestemt værdi tilknyttet, og hvor der nogle gange vil kunne ændres på værdien) 
- Lære om forskellige typer af loops
  - For loop (gentaer et stykke kode et bestemt antal gange, mens den ligger en til en hovde variable (den der også styre hvor mange gange det køre)(det samme som en sigma sum))
  - while loop (gentager et stykke kode, så længe et udtryk er sandt)
- if statements (udføre en linje kode, så læge et udtryk er sandt)
  - else statements (udførekode hvis udtrykket ikke er sandt)
  - if else (udføre koden hvis det første udtryk ikke er sandt, men et andet er)
- Lister (en gruppering af værdier, i en systematisk rekkefølge, hvor der kan læses fjernes og/eller tilføjes værdier)

  ### Projekter 
vi har også lavet et par små projkter her hvor vi har haft om kodning, vi har lavet:
- Jeg har lavet et program hvor jeg har kodet en tegneblock, hvor man som brugeren kan tegne i (https://editor.p5js.org/sylvesterblaa/sketches/x0iUDvgQX)
- jeg har også lavet et program af 2 "bolde" der hopper på kanterne af skærmen (https://editor.p5js.org/sylvesterblaa/sketches/z9Bdv-H3L)
- og så har jeg lavet et program som der tegner sierpinskis trekant (https://editor.p5js.org/sylvesterblaa/sketches/U-oo_1SdJ)
 
## kryptering

Efter vi har haft om progrmering havde vi om kryptering, her havde vi om:
- kryptering
  - symmetrisk kryptering (hvor både modtager og sender har den samme nøgle. fx cesar kryptering)
  - asymetrisk kryptering (hvor sender og modtager har hver sin nøgle, en offenlig nøgle og en privat nøgle. fx RSA)
 
### projkter 

her havde vi også et lille projket:

- vi skulle lave et lille program der kunne cecar kryptere en string (https://editor.p5js.org/sylvesterblaa/sketches/av8SzHfc-) (dog så blev jeg ikke helt færdig :( )

## 3d stuff

Vi har også haft om 3d stuff, her havde vi om:

- at lave 3d modeller
  - at tegne i cad (her har jeg brugt fusion og onshape)
  - slicer (vi har også brugt en slicer til at omdanne vores 3d figurere til gkode så en 3d printer kan læse)
- vi har også haft om alt det seje der er i makerspace (3d printer, laser skære, venyl skære, mm)

### projkter 

- her havde vi et lille projkt hvor vi skulle 3dprint en figur med et rumfanget på 5cm^3

## vandmåler

vi havde et ståre projekt hvor vi skulle lave en fugtighedsmåler, til at tjekke om en plante skulle vandes.(https://github.com/andersvinbaek/rainbow-cache/blob/main/README.md)

her har vi brugt: en Arduino UNO, Grove capacitive moisture sensor, grove 16x2 LCD RGB backlight, DFPlayer mini og en højtaler. 

her var målet at få den til at afspille musik, når ens plante manglede vand.

flowchart til ideen:
<img width="1043" height="412" alt="image" src="https://github.com/user-attachments/assets/eedb570b-fb0f-40ac-b209-d46ee6e54030" />

blockdiagram: 
<img width="886" height="550" alt="image" src="https://github.com/user-attachments/assets/b8d3cfd2-d2d0-4734-92d7-5fdb61ba43d7" />

flowchart til koden:
https://miro.com/app/board/uXjVG2YV6VM=/

Så har vi også 3D printede en kasse til højtalerenheden, som vi gjorde gennem fusion, og printede på bambolab printerne.

vi havde dog en del problemer, som vi skulle undersøge og løse undervejs, blandt andet med tx og rx pins på ardinouen. men alt i alt fik vi det til at virke 

- gennem dette projket havde jeg stort fokus på at lære, hvordan man koder på arfuino UNo
- hvordan man får analogdata ind og behandler det
- hvordan man sænder signaler ud igen
- fil typer
- hvordan man skaber komunikition mellen de forskellige dele
- hvordan man 3d printer

## Drone projket

vi har også været igennem et lille droneforløb (https://github.com/sebball5/Tello-projekt)

  ### Problemformulering
  - Vi vil meget gerne lave en nemmere måde at styre dronen på, da den lige nu skal programeres, det vil vi gerne ændre til en mere brugervenlig overflade.

### Flowchart

<img width="625" height="706" alt="image" src="https://github.com/user-attachments/assets/a3c96fa9-6700-4ac7-a006-f852dd1487ef" />

flowchartet delt i 2, den øverste del til venstre, den nederste til højer

### Blokdiagram

<img width="975" height="494" alt="image" src="https://github.com/user-attachments/assets/a7bf5324-f86e-4d55-9656-38aa75482729" />

som der ses på blokdiagrammet snakker manden tysk, computerens mikrofon opfanger det og sender det til google API tyske lydbibliotek. Lydbibilioteket registrere så hvilken lyd det er og skriver det tilbage til computeren. computeren tjekker så hvilken command der korropondere til lyden, dronen aflyder så ordren.


### Trelags model 

<img width="653" height="700" alt="image" src="https://github.com/user-attachments/assets/e41fe399-95d0-47fc-8aeb-e22d6fa81a2d" />

### Client- Server akitektuktur

<img width="975" height="364" alt="image" src="https://github.com/user-attachments/assets/16c4743b-b10c-439d-b80f-f01b7ff85b52" />

i dette projekt har jeg haft stort fokus på:
  - hvordan man koder i python
  - internet
  - hvordan man komunikere til api's
  - hvordan man får forskellige dele til at komunikere
  - hvordan man sender fejlkoder


