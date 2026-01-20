Tema proiectului

Să se proiecteze un microsistem cu următoarea structură: 
- unitate centrală cu microprocesorul 8086; 
- 128 KB memorie EPROM, utilizând circuite 27C512; 
- 64 KB memorie SRAM, utilizând circuite 62256; 
- interfaţă serială, cu circuitul 8251, plasată în zona 04D0H – 04D2H sau 05D0H – 05D2H, în funcţie de poziţia microcomutatorului S1; 
- interfaţă paralelă, cu circuitul 8255, plasată în zona 0250H – 0256H sau 0A50H – 0A56H, în funcţie de poziţia microcomutatorului S2; 
- o minitastatură cu 9 contacte; 
- 10 led-uri; 
- un modul de afişare cu 7 segmente, cu 8 ranguri (se pot afişa maxim 8 caractere hexa simultan); 
- un modul LCD, cu 2 linii a câte 16 caractere fiecare, cu o interfaţă la alegerea studentului.

Toate programele în limbaj de asamblare vor fi concepute sub formă de subrutine. Programele necesare sunt: 
- rutinele de programare ale circuitelor 8251 şi 8255; 
- rutinele de emisie/ recepţie caracter pe interfaţa serială;
- rutina de emisie caracter pe interfaţă paralelă;
- rutina de scanare a minitastaturii; 
- rutina de aprindere/ stingere a unui led; 
- rutina de afişare a unui caracter hexa pe un rang cu segmente. 

Structura rutinelor (intrări, secvenţe, ieşiri) va fi stabilită de fiecare student.

