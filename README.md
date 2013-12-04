Document col·laboratiu AgroEvolution BETA
=========================================

AgroEvolution és un projecte integral de distribució de producte de pagès. Pensat de forma senzilla i accessible per a tot els públics a través de plugins per a wordpress. 






DESENVOLUPAMENT TÈCNIC DEL PROGRAMA
___________________________________

S’ha triat la base de wordpress per la seva interconecció i practicitat.

L’estructuració de tot el projecte es presenta sobre un plugin/mòdul per a wordpress que compacti les diferents funcionalitats establertes. Que es pugui adaptar a diferents temes que s'especificaran per la millor integració.
En tot cas es pot contemplar que dintre del mòdul es puguin anular certes funcions (aïllables) com la taula de cultius, l’autorització de treball com a moneda, etc.

 
 
 
 

FUNCIONALITATS
______________

REGISTRE – El registre ha de ser de forma quasi completa per poder inscriure socis/sòcies a una associació. És dir que ha de reunir els camps i passos del procés fins al punt de rebre l’autorització signada de l’associat i el rebut d’inscripció de la caixa/banc. ///  els camps del formulari han de poder ser modificables  ///  ha de limitar la inscripció estrictament a gent dels pobles que s’hagin preestablert.  /// Ha de diferenciar entre soci productor i soci consumidor. La diferència bàsica a part de camps diferents i quotes diferents, és que el soci productor s’ha d’aprobar per l’usuari de l’assemblea/associació abans de fer el pagament.  /// Tots els camps dels formularis han de poder-se modificar des de l’administrador del wordpress.  /// En la secció de pagaments, hi haurà les quotes. Les quals s’han de poder modificar posteriorment per l’usuari de forma mensual. És dir que sempre hi haurà d’haver-hi una quota preestablerta i triada, però l’usuari la podrà modificar   i tindrà efectes pel mes següent (cicle econòmic mitjà)*
el cicle econòmic curt és setmanal que marca el ritme de repartiment i el cicle llarg és anual que marca el ritme de collites /// S’ha d’especificar que el cobrament de les quotes es farà de forma mensual i inclou el servei d’alimentació pagesa. I per tant s’ha d’incloure les dades de domiciliació bancària.  /// A part de les quotes amb servei de distribució pagesa inclòs, també hi haurà una quota mínima la qual donarà dret als serveis bàsics de l’associació i permetrà sense crèdit estar al dia del producte de temporada.  /// També ha de contemplar la baixa total de l’associació amb verificació (especificant borrat del registre de l’associació). I la pausa completa de quotes i serveis amb possibilitat de reactivar (seguin contant com a associat inactiu).


FITXES PRODUCTORS – En la mesura que s’aprovin nous productors, se’ls ha d’obrir una pàgina pròpia on tinguin un formulari per omplir d’explicació com a productor i finca (possibilitat de diferents finques). Així com la introducció de fitxes per cada producte. I una taula sobre aquests productes introduits per especificar l’stock del que disposen (amb algun mètode de verificació). Del qual el producte s’acumularà i guardarà sempre, però de la taula dels productors se’ls borraran els stocks quan s’acabin. En una altre part de la fitxa pot haver-hi l’historial de stocks.  /// 
D’una forma òptima hi hauria el fet de poder tenir una aplicació per mòbils en aquest sentit que sincronitzes les taules de stocks, etc per els productors. Així com de cara als consumidors el fet de poder fer la comanda per allí també.

FITXES DE CONSUMIDORS – Les fitxes dels consumidors són bàsicament per gestionar les quotes (les quals cada canvi haurà d’anar verificat). També s’hauràn de poder deixar observacions i un sistema de missatgeria per poder mantenir contacte constant amb els consumidors per incidències, etc.  També ha de comprendre un sistema de cistella bàsic setmanal amb el crèdit sobre la quota preestablerta (menys les taxes de distribució).

MOTOR MERCAT VIRTUAL - Aquesta és l’essència. La qual treballà amb la resta de bases de dades. Però que aquí s’han de conjurar els productors diferenciadament, els productes amb la quantitat d’stock i les comandes dels consumidors sobre aquest stock de cada productor. /// Sobre la base de dades motora es treballarà amb el cicle econòmic curt. El qual s’haurà de prestablir el dia/dies de repartiment per l’associació gestora. Així com el dia de tancament de comanda. De manera que servirà per anunciar setmanalment de quan són els cicles de comanda i el dia de repartimet de cada setmana. I s’haurà de visualitzar d’una forma clara. Amb la opció de canviar de forma excepcional el dia de repartiment per coincidència amb dies festius de forma prèvia.  /// Sobre totes aquestes dades s’han d’imprimir estadístiques d’una forma organitzada i completa. De manera que amb unes dades prèvies es puguin imprimir volums de cultius segons número d’associats. Fent mitjanes per exemple de cada producte i establint “patrons de consum” de manera que es puguin preveure les collites amb el número actual de socis i així poder-les distribuir. Per tant totes les dades han d’estar ben indexades i disponibles.  /// El crèdit dels associats el marcarà la quota. Que serà la mateixa per tot el cicle mensual. De la qual es descontarà la taxa d’associació i distribució prèviament al crèdit resultant. Que de forma preestablerta però modificable s’estableix en el 30%.

MONEDA VIRTUAL En aquest sentit s’estableix una moneda base anomenada solidari, la qual a través d’una equivalència preestablerta per l’associació gestora (amb la possibilitat de desactivar-ho també) es podrà bescanviar per hores de col·laboracions puntuals dels socis que ho necessitin a finques productores que així ho hagin indicat a la seva fitxa.  Tant una certificació com l’altre han d’anar autoritzades per l’usari Assemblea i es sol·licitarà únicament a través de les fitxes un cop ja associats, no al formulari d’inscripció.

TAULA DE CULTIUS Segons totes les dades de volum de producte per associat, etc en el cicle economic llarg anual. S’ha de pensar i generar un sistema fiable que creii patrons de consum sobre les dades existents (entenent que ha d’anar incorporant els nous productes i productors) i pugui imprimir la previsió de comandes. Oferint aquesta impressió de dos opcions:

-S’oferirà la possibilitat de reunir tota la estadística en un sol bloc d’informació per oferir-lo a l’associació gestora quan ho necessiti i fer el repartiment de cultius físicament.

-O bé la opció d’automatitzar-ho i poder-ho fer a través del mateix sistema amb autoadjudicacions dels productors sobre una taula virtual.
