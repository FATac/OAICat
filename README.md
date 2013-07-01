OAICat
======

Modificació del codi trobat [aquí](http://code.google.com/p/oaicat/) 
per tal d'afegir el format "ese" d'europeana i afegir setSpec d'Arxiu.


Passos a seguir per desplegar
-----------------------------

  1) Desplegar el [war](http://code.google.com/p/oaicat/downloads/detail?name=oaicat.war&can=2&q=) al servidor.

  2) Modificar el codi de la manera oportuna.

  3) Compilar el codi amb ant: ``ant dist``. 
  
  4) No s'ha trobat la manera de poder desplegar directament el jar que es genera, així que anem a ``build/`` a 
  cercar les classes que s'hagin modificat i les posem al jar dins ``WEB-INF/lib/oaicat.jar`` del servidor.
  
  5) Reiniciem l'aplicació.
  
  
S'hauria d'investigar perquè no es pot desplegar directament la versió del jar que es genera amb ant.
Dóna un error al intentar cercar el servlet principal de l'aplicació (que no s'ha tocat).
