# practica_flex
Temari tasca 1.1 Flex

<b>DESCRIPCIÓ</b>

En aquesta pràctica hauràs de fer un Layout que ha de funcionar tant en escriptori, com mòbil i tauleta.


 Important: Coneixements que has de tenir per facilitar la resolució de la pràctica.

HTML i CSS
Flexbox. -> Flexbox CSS: Guia Completo, Elementos y Ejemplos
Media queries (pots utilizar els punts de tall de com les de bootstrap. -> Media queries
Tingues en compte les següents consideracions. Són errors habituals en els lliuraments:

En general, mai li posem height a una capa, sinó que deixem que la capa s'adapti al seu contingut (si la capa no té contingut, li pots posar un height).
La pàgina no hauria de tenir barra de scroll horitzontal (si et passa, hauràs d'esbrinar inspeccionant la pàgina quin bloc és més ample que la pantalla del navegador).
Dins d'un div sol haver-hi altres divs. Els divs tenen display:block per defecte. Això fa que es vagin col·locant de manera vertical. Per tant, sovint no és necessari especificar els següents estils per a un element per ser una cosa redundant:
.element{ display:flex; flex-direction:column }
En un div, per defecte l'ample és de la totalitat de la capa que embolica, així que normalment no serà necessari especificar width:100%

<b>Nivell 1</b>

- Exercici 1
A partir del wireframe que t'aportem en format .png, hauràs de fer la maquetació en format escriptori. És indiferent els colors escollits, però sí que és molt important que facis l'estructura de caixes que t'indiquem.

 Important

L'ample màxim de la capa que contindrà tota la maquetació serà de 1200px (max-width:1200px).

- Exercici 2
S'ha de començar a preparar l'adaptació a diferents dispositius, i per això has de tenir clar el concepte de Media Query. Fixa't que hi ha canvi de distribució i color d'alguns elements.

Desde la ITAcademy et recomanem Breakpoints per les Media Queries de Bootstrap. -> Media queries


 Per saber més

Sobre Media Query -> Responsive Web Design - Media Queries


Seguint amb el projecte anterior, fes la versió per tauleta, tal com indica la captura següent:

Captura de pantalla del wireframe versió tauleta

- Exercici 3
Com el cas anterior, ara hauràs de fer l'adaptació a versió Mobile.

<b>Nivell 2</b>

Canvia el color de fons de la web en funció de l’amplada d’escriptori, tauleta i mòbil

<b>Nivell 3</b>
Utilitzant la propietat css animate, necessitem que en fer hover a sobre el primer div, faci un canvi de dimensions i de color.




