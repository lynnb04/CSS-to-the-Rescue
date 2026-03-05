# CSS to the Rescue
Mijn repo voor het vak CSS to the Rescue


## Mijn leerdoelen
- Ik wil leren hoe ik creatieve en speelse interacties kan bouwen met HTML, CSS en JavaScript in plaats van “alleen functionele” interfaces.
- Ik wil beter worden in experimenteren, niet terughoudend zijn met dingen uitproberen.
- Ik wil beter worden in het maken en vastleggen van verschillende iteraties en hoe feedback hierin terugkomt.


## Mijn voortgang

### Woensdag 18/02
**Wat heb ik vandaag gedaan?**  
  Kick-off van CSS gehad. Toen de hele dag gewerkt aan scroll state queries en hier een Codepen mee gemaakt.    
**Hoeveel tijd heeft me dat gekost?**  
  Tot half 4 ben ik hiermee bezig geweest, met +/- anderhalf uur pauze tussendoor.    
**Wat heb ik geleerd?** 
  Scroll state queries zorgen ervoor dat je styles kan toepassen gebaseerd op de richting waarin de gebruiker scrollt. Je past het toe door container-type: scroll-state; op de parent element te zetten. Daarna kan je scroll-state() gebruiken als een container query: bijv scroll-state(scrolled: bottom).    
**Wat ga ik morgen doen?** 
  Presenteren en beginnen aan de eindopdracht.    

### Donderdag 19/02
**Wat heb ik vandaag gedaan?**  
  Werk van gisteren gepresenteerd. Toen om 1u de kick-off van de eindopdracht gehad en hieraan gewerkt tot half 4. Ik heb inspiratie opgedaan voor de eindopdracht. Toen de check-out gedaan en daarna ben ik naar de Weekly Nerd sessie gegaan.    
**Hoeveel tijd heeft me dat gekost?**  
  De presentaties waren van 10-12. Daarna een uurtje pauze en toen heb ik van 13-15:30 gewerkt.    
**Wat heb ik geleerd?** 
  Heel veel nieuwe dingen bij de presentaties. Vooral anchors en :has vond ik heel cool.    
**Wat ga ik morgen doen?** 
  Feedbackgesprekken en ik ga verder werken.    

### Voortgang week 1
  Ik ga de opdracht CMD Artifaction doen. Ik wil hiervoor sowieso CSS nesting en @layer gebruiken.
  Inspiratie tot nu toe:    
  <img width="270" height="480" alt="image" src="https://github.com/user-attachments/assets/c9cb16a7-817c-453e-8333-77b8f7b8c1a6" />
  <img width="270" height="480" alt="image" src="https://github.com/user-attachments/assets/70979d79-2262-41b0-9e8a-c083c13f1bb5" />  
Meeting notes:    
- svgomg  
- svg { { path fill: ...; }  }  
- border: solid currentColor;  
- preserveAspectRatio = "none" svg stretch  
- url encoder for svg  
- ana tudor  
- je kan keyframes in url() zetten  

### Woensdag 04/03
**Wat heb ik vandaag gedaan?**  
  Geluisterd naar de Weekly Nerd talk, toen 3 workshops gedaan en daarna heb ik mijn mappenstructuur gemaakt. Ben begonnen met html en css. Ik had wat coole ideeën gevonden, waardoor ik geïnspireerd werd, in combinatie met de workshops. Ik wil elementen 3d animeren om een soort sterrenstelsel effect te krijgen, en hier randomness op toepassen.    
**Hoeveel tijd heeft me dat gekost?**  
  Om 13:00 begon ik met de mappen enz, tot die tijd de talk en workshops. Een half uurtje gedaan over readme updaten.    
**Wat heb ik geleerd?**  
  Vrijwel alles wat aan bod kwam bij de workshops. Ik vond steps() heel interessant en Nils liet zien hoe je een color randomizer maakt, dat vond ik ook heel vet. Dit was ook nieuw voor mij: animation-delay: calc(-2s / sibling-count() * sibling-index() );.    
**Wat ga ik morgen doen?**  
  Verder aan de code en in de middag het voortgangsgesprek doen.    

### Donderdag 05/03
**Wat heb ik vandaag gedaan?**  
  Ik heb de workshop over animeren gevolgd. Daarna ben ik gaan werken aan css, fonts in gitignore en toen de check-out.
**Hoeveel tijd heeft me dat gekost?**  
  Workshop duurde een uur. Ik heb tot kwart voor 3 gewerkt aan mijn code en daarna heb ik het voortgangsgesprek gedaan. Daarna heb ik mijn readme geüpdated. 
**Wat heb ik geleerd?**  
  Introductie van keyframe animaties en pixel art animation maken met steps(2, jump-none).
**Wat ga ik morgen doen?**  
  Voortgangsgesprek voor BT en aan mijn blog werken.

### Voortgang week 2
  Ik ga een zonnestelsel geïnspireerd iets maken wat op (seemingly) random manieren beweegt. Voor de planeten wil ik de CMD iconen gebruiken en deze zo aanpassen dat ze op planeten lijken. Het lijkt me ook leuk als je met een knop/refresh de iconen kan randomizen.    
  Inspiratie: https://nl.pinterest.com/pin/624311567142357621/    

  Meeting notes:    
  - sibling index for random movement of the planets
  - randomness on media query width
  - add a line in the middle that you can't see from the front but is visible from the side
  - pill shape: border-radius: 100vw;
  - animato to/from: sometimes it is helpful to leave out from, if elements have different starting points and travel to the same point

  - Show your progress (text, code and pictures):
  - What went smoothly, and what was challenging?
  - What experiments did you conduct that 'failed'?
  - Do you have new insights into how to leverage the power of CSS (or not)?
  - Incorporate changes to your initial plan:
  - The challenges for next week: