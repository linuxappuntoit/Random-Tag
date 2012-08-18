Random tag
====================================

Block for the cms Accessible Portal and Php Nuke


/* Accessible Portal: Web Portal System                 */

/* ==================================================== */

/* Blocco TagCloud Random 0.1  			*/

/* by luciano apolito #=-> linuxap.it 2012              */ 

/* www.linuxap.it 					*/

/* Licenza Gnu-GPL 2.0 				        */



/

Blocco TagCloud Random - per Accessible Portal e PhpNuke  
========================================================= 		

Permette di creare un  blocco laterale con una serie di tag presi      
casualmente  da una tabella (per esempio le news) senza alcun ordine   
logico.  Configurabile all'interno dello script con diverse opzioni.

Installazione
=============
Copiare il file block-Tag.php nella dir portal/blocks del vostro sito 
e abilitare da Pannello di controllo

Configurazione
==============
Per configurare il blocco , aprire con un editor e modificare le variabili
 

$numparole=100; // le prime n. parole da visualizzare

$lettere=5; // minimo numero di lettere di cui è composta la parola per il tag

$min = '8'; // Font size minimo in pixel.

$max = '34'; // Font size massimo in pixel

$backg=false; // abilita il colore random come sottofondo del blocco

Queste variabili sono per sceglier edov fare il prelievo delle parole,


$campo="title"; // il campo dove prelevare le parole

$tabella="stories"; // la tabella dove prelevare le parole

$id="sid"; // l'identificativo della tabella 

$module_name="News"; // nome del modulo

$file2="article"; // nel caso servisse il nome del file da caricare come per le news. In genere il file è index



luglio 2012 by l.apolito 

http://www.linuxap.it
