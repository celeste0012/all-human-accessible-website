# Accessible Website

Ontwerp en maak voor een opdrachtgever een website toegankelijk volgens WCAG richtlijnen.

De instructie van deze leertaak staat in [WIKI](https://github.com/fdnd-task/all-human-accessible-website/wiki)

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Voor iedereen die rechtenvrije iconen wil is deze website gemaakt, met iconen en illustraties die rechtenvrij zijn. De pagina is responsive en is Mobile first ontworpen en gemaakt.

Foto van iconen pagina:
<img width="1485" height="710" alt="afbeelding" src="https://github.com/user-attachments/assets/5a4b5a2a-416e-4ea8-8ae2-57e3a1b55d1e" />

Link naar github:
https://celeste0012.github.io/all-human-accessible-website/

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

### HTML
In de main zit een variant selector, deze heb ik zo gemaakt:
```html

<p>Kies een variant</p>
            <div class="radio">
                <div>
                    <input type="radio" name="variant" value="regular" id="variant_regular" checked>
                    <label for="variant_regular">Regular</label>
                </div>
                <div>
                    <input type="radio" name="variant" value="line" id="variant_line">
                    <label for="variant_line">Line</label>
                </div>
                <div>
                    <input type="radio" name="variant" value="fill" id="variant_fill">
                    <label for="variant_fill">Fill</label>
                </div>
                <div>
                    <input type="radio" name="variant" value="diapositive" id="variant_diapositive">
                    <label for="variant_diapositive">Diapositive</label>
                </div>
            </div>
```
Ook zitten alle soorten iconen in losse ul's :
```html
<ul class="icons icons_regular">
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/Aanmelden.svg" alt=""></li>
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/Actueel.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/Afval.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalGFT.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalGlascontainer.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalGroenbak.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalOphalen.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalPMD.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalScheiden.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/df35e33dbe51d88ac358f549701198103ac033d8/Svg/Regular/AfvalbakAfvalzak.svg" alt=""></li>
        </ul>
        <ul class="icons icons_line">
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/Aanmelden.svg" alt=""></li>
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/Actueel.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/Afval.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalGFT.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalGlascontainer.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalGroenbak.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalOphalen.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalPMD.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalScheiden.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Line/AfvalbakAfvalzak.svg" alt=""></li>
        </ul>
        <ul class="icons icons_fill">
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/Aanmelden.svg" alt=""></li>
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/Actueel.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/Afval.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalGFT.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalGlascontainer.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalGroenbak.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalOphalen.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalPMD.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalScheiden.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Fill/AfvalbakAfvalzak.svg" alt=""></li>
        </ul>
        <ul class="icons icons_diapositive">
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/Aanmelden.svg" alt=""></li>
            <li class="svg"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/Actueel.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/Afval.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalGFT.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalGlascontainer.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalGroenbak.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalOphalen.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalPMD.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalScheiden.svg" alt=""></li>
            <li class="svg afval"><img src="https://raw.githubusercontent.com/OpenGemeenten/Iconenset/fa603235cc5faf9faaf280a0f7736859b509a581/Svg/Regular%20diapositive/AfvalbakAfvalzak.svg" alt=""></li>
```

### CSS
De radio buttons en de filter hebben een css om ervoor te zorgen dat ze werken.
De iconen hebben @media waarin een veel kortere code in zit dan voorheen waardoor het veel overzichtelijker is.
En de diapositive iconen hebben wat code zodat ze ook echt diapositive zijn.

## WCAG audit
Ik heb minstens drie problemen opgelost:
1. skip links toegevoegd
2. kleur contrast beter gemaakt
3. alt's ingevuld

## Bronnen
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/clamp

https://www.codecenter.nl/tryit/html/ex/form_keuzelijsten1

https://www.youtube.com/watch?v=f6ocDCkCmhM

https://stackoverflow.com/questions/710089/how-do-i-make-an-html-link-look-like-a-button

https://www.w3schools.com/css/css3_shadows_box.asp

https://stackoverflow.com/questions/58177903/css-translate-creates-white-space-on-original-position
## Licentie
This project is licensed under the terms of the [MIT license](./LICENSE).
