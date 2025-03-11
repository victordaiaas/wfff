1.- Introducció
En aquest petit informe s’explicarà en primer lloc el disseny purament del website, seguidament el disseny dels layouts aplicats en cadascuna de les pàgines i una justificació de la tècnica responsive aplicada per poder adaptar la nostra aplicació a tots els dispositius.
En primer lloc destacar que la web es sobre un restaurant en concret de Cadaqués que es diu Norai. Aquesta idea ve donada ja que jo vaig treballar l’estiu de l’any 2020 i vaig veure que no tenien pàgina web. Em va semblar molt interessant ja que veig que estic fent una web que en la vida real podria tenir un sentit i una aplicació.  
2.- Estructura ‘site web’
La pàgina web s’estructura en 5 pàgines. 
Primer tenim una pàgina principal ‘INICI’ , on es presenta el restaurant, una mica del tipus de cuina que es fa i unes primeres fotografies que ens apropen al lloc.
La segona pàgina és la galeria, la qual he agafat les fotografies que més m’han agradat d’internet i de la conta oficial d’Instagram perquè el client pugui veure un ‘carrusel’ amb les millors fotos de l’indret i ja poder fer-se la idea d’alguns dels plats i presentacions.
En tercer lloc tenim la carta, la qual es va fer lo més real possible de totes les propostes que recordava. Com es pot veure és una carta curta i sobretot sempre es posava en valor el peix del dia que depenia la seva disponibilitat.
En quart lloc tenim la pàgina de ‘Com Arribar’. En aquest apartat tenim un mapa interactiu on tenim digitalitzat i marcat en primer lloc la localització del local, tots els pàrquings a menys de 2 kilòmetres i gairebé tots els allotjaments del municipi. Cadaqués al ser molt petit i turístic, tenim molta densitat d’allotjaments.
I per últim tenim la pàgina de reserves, on tenim un caixetí el qual podem omplir tant amb el nom, la data de la reserva, la hora i el número de persones per les quals es vol reservar. Aquest apartat des del meu punt de vista en la web d’un restaurant és clau, ja que agilitza tot el procés de reserva i facilita la feina a tothom.











3.- Disseny dels layouts
PÀGINA ‘INICI’
Aquest apartat correspon a la secció "Inici" del site web del restaurant. La seva estructura general és la següent:
1.- Encapçalament (head)
Es defineix el títol del document (<title>Inici</title>).
- S’inclou la configuració de codificació (UTF-8) i el viewport per la seva correcta adaptabilitat.
- Es carrega un favicon (img/Favi.png).
- S’importen varies fulles d’ estilo CSS (menu.css, footer.css, index.css, cookies.css).
- S’ incorporen scripts de JavaScript (menu.js, footer.js, cookies.js).
- I per últim s’utilitza  ‘Font Awesome’ per a icones i ‘SweetAlert2’ per a les alertes de les cookies. 
 2.- Cos (body)
 El body conté els principals elements del site web: 
- Barra de navegació superior (<div class="topnav">)
- Inclou enllaços a diferents seccions de la web: Inici, Galeria, Carta, Ubicació i Reserves.
- Conté una opció de menú responsive.
- Secció de presentació (<div class="parallax">)
- Contingut principal (<div class="container">)
- Es distribueix en dos columnes:
Una columna amplia (column-66) amb el títol "DESCOBREIX NORAI CDQ" i un text descriptiu sobre el restuarant, com a petita introducció per l’usuari.
Una columna menor (column-33) que conté una imatge del restaurant.
- Secció secundària (<div class="container2">)
- Proporciona informació adicional sobre el restaurant i la seva proposta gastronòmica.
- El contingut es `resenta dins d’un contenidor amb un disseny estructurat (<div class="caja">).
- Peu de pàgina (<footer class="footer">)
Conté informació de contacte i enllaços a les xarxes socials 
S’ agregen elements visuals com el logo de la universitat i un botó de ‘’Tornar adalt’’.
Missatge de cookies (<div id="cookie-message">)
Notifica al usuari sobre l’ús de cookies i proporciona opcions d’acceptació o rebuig.

 3. Disseny de Layouts
El disseny del site web es basa en una estructura de quadrícula (grid) amb l’ús de dividir per organitzar el contingut. S’implmeenten classes CSS que divideixen la pantalla en porcions:
- column-66: Ocupa aproximadament el 66% del ample, proporcionant el contingut textual principal.
- column-33: Ocupa el 33% restant, utilitzat per la imatge complementària.
- topnav: Menú de navegació horitzontal amb enllaços estructurats.
- parallax: Secció visual que millora l’experiència del usuari.
- footer: Peu de pàgina amb enllaços a les xarxes socials i el contacte. 
El site web està ben estructurat i compta amb una navegació clara i eficient. La imolementació d’estils CSS ben organitzats, juntament amb Java Scriptper a la interactivitat, permet una experiència agradable al usuari. 
PÀGINA ‘GALERÍA’
Aquest apartat correspon a la secció "Galería" del site web del restaurant. La seva estructura general és la següent:
 1.-  Encapçalament (head)
- Defineix el títol ‘GALERÍA’.
- Inclueix un disseny responsive.
- Carga un favicon desde "img/Favi.png".
- Importa fulles d’estil CSS (menu.css, footer.css, galeria.css, cookies.css).
- Incorpora scripts de JavaScript (menu.js, footer.js, cookies.js).
- Usa Font Awesome per a les icones. 
2.-  Cos del document (body): El contingut principal de la pàgina s’estructura en:
- Barra de navegació superior (div class=’’topnav’’)
 - Conté enllaços a les altres seccions del site web.
 - Integra un menú responsive.
- Imagen destacada (img src= ‘’img/norai.jpg) 
- Secció visual principal amb una imagen representativa.
- Galería d’imágenes en slider (div class=’’slider-frame’’) 
- Conté una lista de imágenes (Salon1, Salon2, Salon3, Salon4). 
- Permet un efecte de transició per a la visualizació dinámica deles imatges escollides. 
- Peu de pàgina (footer class=’’footer’’)
 - Secció amb tota la informació de contacte, xarxes socials y el logo de URV. 
- Missatge de cookies (div id=’’cookie-message’’), i la notificació per al usuari amb opcions d’ aceptació o rebuig. 
3. Diseny de Layouts 
El disseny d’aquesta página segueix una estructura simple amb els elements organitzats en:
Un encapçalament de navegació fixe
Una imatge destacada de gran tamany.
Un carrusel d’imágenes dins d’un contenedor lliscant.
Un peu de pàgina amb informació adicional
En conclusió, la pàgina "Galeria" està dissenyada per a oferir una experiència visual atractiva mitjançant imatges destacades y un carrusel de fotos. El seu disseny responsive permet la visualització que s’adapti als diferents dispositius.
PÀGINA ‘CARTA’
Aquest apartat correspon a la secció "Carta" del site web del restaurant. La seva estructura general és la següent:
1.- Encapçalament (head)
 - Conté el títol de la pàgina y metadades cruciales per tindre una justificació responsive correcta.
- Enllaça diversos arxius de fulles d’estil CSS, lo que fa una separación adecuada entre la estructura HTML, la presentación CSS i la funcionalitat mitjançant JavaScript. 
2.- Cos (body)
- Barra de navegació (div class=’’topnav’’): Conté enllaços a diferentes pàginess com "Inici", "Galeria", "Carta", "Com Arribar", i "Reserves". Ademés, inclou una icona per a canviar al mode fosc i una justificació responsive adecuada.
- Carrusel (div id=’’demo’’ class=carousel slide’’): S’utilitza un component interactiu per mostrar imatges rotatives, lo que dona dinamismo visual a la página web. 
- Menú (div class=’’footer’’): Presenta una lista detallada dels plats del restaurant, dividits en "Entrants", "Peixos", "Arrossos" i "Postres", de manera clara y jeràrquica.
 - Peu de pàgina (footer class=’’footer’’): Ofereix informació adicional sobre la empresa, enllaços a xarxes socials i un avís de copyright. 
- Botó per a tornar a l’inici: Es tracta d’un botó flotant que permet a l’usuari desplaçar-se ràpidament fins la part superior de la página. 
- Cookie Message (div id=’’cookie-message’’): Es muestra el típic missatge de cookies que es per a cumplir amb les normatives de privacitat. 

3.- Diseño de Layouts
El disseny general del site web té una estructura sencilla i clara, dividida en seccions ben definides. A continuació es descríuen els aspectes clau del seu disseny: 
• Barra de Navegació Superior: 
-	S’utilitza el disseny d’una barra de navegació tradicional amb enllaços per a cadascuna de les pàgines de la web. Té també un disseny responsive per adaptar la visualització en tots els dispositius. 
• Carrusel: 
-	L’ús d’un carrusel d’imatges li dona un toc visual atractiu.
-	Els controls de navegació permeten als usuaris moure les imatges. 
• Menú del Restaurant:
-	El menú está estructurat de manera jeràrquica camb diferents seccions (entrants, peixos, arrossos i postres), lo que facilita la navegació visual d’una carta típica de les pàgines web de restaurants. 
• Peu de Pàgina: 
-	El peu de página com en totes les pàgines conté informació important sobre la empresa, el contacte i els enllaços a les xarxes socials.

PÀGINA ‘COM ARRIBAR’
En aquest apartat és on es tracta el disseny cartogràfic de la web. S’ha dissenyat un mapa amb SIG, concretament amb ‘qgis’.
En primer lloc s’han descarregat les imatges ‘svg’ adients per tal de poder entendre el mapa de manera ràpida i visual sense haver de posar la llegenda.  S’ha digitalitzat tan la localització del restaurant, com els pàrquings i els allotjaments a menys de 2 kilòmetres de distància del local.
Un cop tenim el mapa fet, amb el complement ‘qgis2web’ hem pogut exportar una carpeta amb totes les capes en format web.

La carpeta generada del QGIS la posem dintre la carpeta arrel i mostrem el mapa a través dels codis que veieu en la captura de l’informe. 

PÀGINA ‘RESERVES’
Aquest apartat correspon a la secció "Reserves" del site web del restaurant. La seva estructura general és la següent:
1.	Encapçalament (Head): 
-	Archius CSS y JS: S’ enllaça arxius d’estilsi script per donar-li un disseny i una funcionalitat addicional. S’inclouen fulles d’estil per al menú, el peu de pàgina i per a la pàgina de contacte.
Ademés, s’ utiliza una justificació responsive per poder adaptar la web a tots els dispositius. 
2.	Cuerpo (Body): 
-	Barra de navegació superior: Inclou enllaços a les altres seccions de la web. 
-	Formulari de Contacte:  
Aquest és un formulari simple que permet al usuari reservar una taula mitjançant el nom, la data de la reserva, la hora i el nombre de persones que vindran al restaurant. Aquest té un disseny senzill i net amb camps d’entrada i botons estilitzats.
En el camp de la data s’utiliza el plugin (Flatpickr), que millora la 
interfície de selecció de la data.
Per últim un botó de "Reserva" realitza una validació per assegurar-se de 
que tots els camps s’haguin omplert a través d’un missatge d’alerta. 
3. Peu de pàgina (Footer): 
- Proporciona informació sobre l’empresa i enllaços a les xarxes socials.
- També es troba el botó per a tornar cap adalt de la pàgina. 
4. Gestió de cookies: També en el footer, la pàgina inclou un avís sobre el ús de les cookies per complir amb la normativa. 

5. Disseny de Layouts: 
El disseny de la pàgina es centra en una estructura simple i funcional: 
-	Layout principal:  
Formulari de reserva: Un únic contenidor (.reserva-container) 
centralitza tots els camps del formulari, amb un fons blanc amb les bores arrodonits per donar una sensació més de modernitat. 
Estil del formulari: Els camps d’entrada, com els de text i selecció, estàn estandarditzats amb el mateix estil per proporcionar una experiència millor a l’usuari. El botó de ‘Reserva’ té un estil visual que el fa destacar i facilita la interacció. 
-	Responsividad:  
Gracies a la utilització del viewport meta tag i la seva estructura simple, el disseny 
respon adecuadament aa diferents tamnys de pantalla i dispositius. 
El CSS de contacte (contact.css): Aquest arxiu defineix les regles dels estil per la estructura del formulari i altres elements visuals de la pàgina.

La utilizació de pràctiques modernes com la implementació d’un sistema de reserves simple, i la optimització per a dispositius mòbils mitjançant un disseny responsive milloren tant l’experiència de l’usuari com també com a facilitador de feina al organitzar les reserves d’un restaurant.

<h2>4.- Justificació de la tècnica responsive aplicada</h2>
S’ha aplicat una estratègia responsive per garantir una correcta visualització i usabilitat en diferents dispositius, com ordinadors, tauletes i telèfons mòbils. L’objectiu principal ha estat mantenir la coherència del format i assegurar que el contingut sigui accessible per l’usuari.
Per aconseguir-ho, s’han utilitzat ‘containers’ tant en els blocs de text com en les imatges. Aquesta estratègia permet que els elements s’adaptin dinàmicament a la mida de la pantalla, evitant desplaçaments horitzontals innecessaris i garantint una lectura fluida. Els containers ajuden a mantenir una estructura ordenada i proporcionada, adaptant-se automàticament a l’amplada disponible segons el dispositiu utilitzat. 
Pel que fa a l’estil del text, s’ha optat per una utilització moderada de la negreta, ja que en pantalles més petites, com les dels telèfons mòbils, un excés d’aquesta tipologia pot afectar negativament la llegibilitat i sobrecarregar visualment el contingut. 
A nivell de CSS, s’han aplicat regles ‘media queries’ per ajustar les dimensions i el disseny dels elements segons la mida de la pantalla. Així, s’ha garantit una experiència d’usuari homogènia independentment del dispositiu emprat. 
En conclusió, l’elecció d’aquesta tècnica responsive ha estat essencial per assegurar una navegació intuïtiva i un format adaptat a qualsevol dispositiu, millorant tant l’accessibilitat com l’experiència d’usuari del website, alhora que es manté un bon rendiment i una estètica atractiva en qualsevol pantalla.

