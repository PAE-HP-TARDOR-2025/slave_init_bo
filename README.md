# slave_init_bo
He hagut de fer uns canvis al CMake del CanOpenNode. Si només us voleu descarregar el main, primer mireu que us quadrin els CMake. El que he fet és accedir als fitxers d'exemple. 

Potser en un futur caldrà treure aquests fitxers d'exemple de dins de la carpeta exemples. 

L'slave es on es configura l'adressa LSS única per després poder fer l'assignació automàtica dels nodes
Hi ha l'inicialització de la memòria volàtil. Això és perquè hi hagi paràmetres del node que es guardin encara que es faci un reset. 
Quan un node ja està configurat, no entrarà a la parafernalia de reconfigurar-se, sinó que ja tindrà tot a lloc i esperarà el NMT operational command. 

