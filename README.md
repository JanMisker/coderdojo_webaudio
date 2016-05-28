Workshop WebAudio
===

Intro: http://webaudioplayground.appspot.com 

Alle code kan toegevoegd worden aan `index.html`, er staan tips in de functies die afgemaakt moeten worden. 

Deel 1: een geluid afspelen
--
Maak de functie `Geluid.prototype.speelAf` af.

Deel 2: meerdere geluiden afspelen in een compositie
--
Doe dit in het `function speelGeluiden()` codeblok

Deel 3: de sequencer afmaken
--
Doe dit in het `function speelSequence(t)` codeblok

Geavanceerd: geluidseffecten
--
  Stuur bij afspelen de geluiden naar een ConvolverNode om een 
  geluids effect toe te voegen.
  Gebruik hiervoor 
  - audioContext.createConvolver om een ConvolverNode te maken
  - zet een .buffer op de ConvolverNode 
  - connect de ConvolverNode met de normale destination
  - in speelAf verbind de BufferSourceNode niet met de normale destination
    maar met de ConvolverNode