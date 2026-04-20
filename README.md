# veselskysach-theme
Back-up of theme of the chess web veselskysach.cz running on Ghost CMS./Záloha designu šachového webu veselskysach.cz postaveném na Ghost CMS platformě.

Zatím onen jediný json soubor je záloha stavu stránek ke dni 21. 4. 2026. Ruku v ruce s routes.yaml vytváří mapu webu s obsahem. Design - HTML, CSS a JavaScript kód je napsán v jednotlivých .hbs souborech (handlebars). Složka partials obsahuje dílčí komponenty jako třeba komponenta kalendáře (calendar.hbs), stránkování (pagination.hbs), meníčka atd. 

# Jak to použít při naistalování Ghostu
routes.yaml se vloží do content/settings, složka veselskysach se vloží do content/themes a nakonec ten json soubor se nahraje až v Dashboard, když už Ghost běží. Tím se doplní veškerý obsah až na obrázky, které jsem nezálohoval. Je jich dost pomálu a pravděpodobně bude udržitelnější sdílet fotky prostě mezi sebou na WhatsAppu. 
