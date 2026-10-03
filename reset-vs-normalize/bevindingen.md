1. Hoeveel declaraties (regels die eindigen op `;`) staan er in elk `style.css`? Verrast het
   resultaat je?
   39 in de reset
   27 in de normalise
   het verrast me niet echt want bij reset moet je eigenlijk met een blanco template beginnen en normalise wordt het niet helemaal gereset.
2. Welke declaraties had je **enkel** nodig in de reset-versie? Verklaar per declaratie welke
   browserstijl de reset weggegooid heeft.

   h1: font-size: 32px en font-weight: bold, want de browser gaf koppen een grootte en maakte ze vet;
p: margin-bottom: 16px, want de browser gaf alinea's 1em marge;
strong: font-weight: bold en em: font-style: italic, want de browser maakte die vet en cursief;
a: text-decoration: underline, want de browser onderlijnde links;
ul: list-style-type: disc (de reset zet uitdrukkelijk list-style: none) en margin-bottom: 16px

3. Welke declaraties had je **enkel** nodig in de normalize-versie? Waarom moest je die in de
   reset-versie niet schrijven?
   normalise heeft de h2 in het vet gelaten dat is alles wat ik merkte
4. Welke van de twee zou je kiezen voor dit ontwerp? En voor een pagina met enkel lange lappen
   tekst? Motiveer.
   met normalise schrijf je minder code en is dit op de lange termijn efficienter om te gebruiken denk ik