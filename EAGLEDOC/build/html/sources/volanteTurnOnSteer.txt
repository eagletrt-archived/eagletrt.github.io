.. image:: /images/wallpaper.png

Eagle Steering Wheel
=============================

Accensione Chimera Evoluzione
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. note:: La procedura può essere seguita da chiunque fintanto che sono accesi i sistemi Low Voltage (LV), non appena il Tractice System (TS) è accesso rifarsi ad un ESO o ad una persona esperta.

.. note:: Per questa procedura sono necessari almeno un pilota e uno o due ESO. Il secondo ESO è facoltativo e deve solamente assicurarsi di premere i funghi di shutdown in caso di emergenza.

* **Accensione sistema low voltage**

	- Assicurarsi che la macchina sia spenta verificando che gli interrutori TSMS (Tractive System Master Switch) e GLVMS (Grounded Low Voltage System) posti sul lato destro della macchina siano in posizione di OFF (posizione verticale)

	- Assicurarsi che tutti i cavi/collegamenti siano in ordine, se non si è sicuro chiedere a chi può saperlo e aspettare la conferma.

	- Assicurarsi che nessuno stia lavorando alla macchina.

	- Accendere l'interrutore (BMSLV) posto sul porchetto sul lato sinistro della macchina e aspettare 5 secondi, se il LED si accende lampeggiando o in dissolvenza procedere al punto 4 altrimenti spegnere l'interruttore.

* **FASE DI IDLE**

	- Girare in senso orario e con decisione l'interruttore cerchiato rosso GLVMS (lato destro macchina), assicurarsi che i sistemi LV si accendano correttamente (TSAL e volante accesi sono sufficienti). Se nessun sistema si accende rigirare immediatamente l'interrutore sulla posizione di spegnimento (posizione verticale).

	- Una volta acceso il volante controllare le varie tab e la presenza di tutte le centraline collegate specialmente:

		- **Electronic Control Unit (ECU)** -> Presenza di bollino verde.
		- **BMS High Voltage** -> Presenza del voltaggio totale, temperatura.
		- **Pedaliera** -> Presenza del bollino verde.
		- **BMS Low Voltage** -> Presenza del voltaggio totale, temperatura.

* **Accensione Tractive System**

	- Procurarsi un multimetro, impostarlo sulla scala 1000V e inserire i suoi terminali "banana" tra le bocchette TS- e TS+ (le bocchette sono all'interno di un'area rettangolare arancione) presenti sotto l'interruttore TSMS (Tractive System Master Switch).

	- Assicurarsi di indossare gli appositi guanti isolati.

	- Girare in senso orario e con decisione l'interruttore cerchiato arancione TSMS (lato destro macchina), assicurarsi che il multimetro non misuri tensione altrimenti rigirare immediatamente l'interruttore sulla posizione di OFF.

	- PRECARICA: A questo punto si preme il tasto a volante in basso a SX (vicino al tasto START verde insomma) e scatta il primo AIR, in questa fase il voltaggio misurato aumenta lentamente fino al 90% del voltaggio letto sul volante. Dopo 15 Secondi scatta anche il secondo AIR e il voltaggio misurato raggiunge il voltaggio letto sul volante. Se la tensione diminuisce o non aumenta significa che lo shutdown è stato attivato quindi girare con decisione TSMS sulla posizione di spegnimento, aspettare di misurare 0 Volt sul multimetro e poi girare con decisione GLVMS sulla posizione di spegnimento. Ripetere tutta la procedura dal punto 0 verificando il motivo di spegnimento (chiedere ad ESO).

* **FASE DI SET-UP**

	.. note:: Da questa fase in poi tenere sempre una mano sui funghi di shutdown. In caso di pericolo premerli con forza.

	- ACCENSIONE INVERTER: A questo punto in alto a destra si vedrà che la macchina passa da IDLE a SET-UP (icona gialla). Andare quindi nella terza tab (paddle DX 2 volte). Qui si vede che la precharge è verde. Premere il tasto in basso a DX una volta per entrare nella modalità di selezione, e un'altra volta per scendere di una riga e selezionare l'inverter sinistro. Premere il tasto in basso a SX per accenderlo. Una volta acceso, il led (virtuale, quello grigio) corrispondente diventerà verde. Premere quindi di nuovo in basso a DX per selezionare la riga dopo, e premere in basso a SX per accenderlo. Una volta acceso anche questo (tutto verde quindi), premere in alto a SX per uscire dalla modalità di selezione. Premere quindi il paddle DX per andare nella racing page.

		- .. note:: In caso di emergenza (ruote che schizzano) premere i funghi di shutdown!

		- .. note:: ci mette tipo un secondo perchè deve caricare tutte le immagini di quella tab, portate pazienza, non schiacciate il paddle millemila volte. Fatto questo, selezionate la mappa con il manettino a destra (blu). La 1 è la retro e preferirei non venga usata per ora (mai testata). Usate le altre mappe, dalla 2 alla 6. A vadena usavamo max la 4 perchè la 5 era quella che faceva spegnere tutto. Mappa 4 sono circa 72kw a quanto pare.

	- Controllare sempre che i valori di tensione e temperature letti a volante siano nella norma e verificare che la tensione letta con il multimentro corresponda a quella sul volante.

* **FASE DI RUN**

	- Scelta la mappa, tenete frenato e schiacciate in alto a SX. Questo fa andare la macchina in RUN, facendo suonare il buzzer per almeno due secondi e facendo diventare l'icona verde.

	- Verificare che la tensione letta con il multimentro corresponda a quella sul volante e poi rimuovere le "banane" dalle bocchette TS+ e TS-. Se la tensione diminuisce significa che lo shutdown è stato attivato quindi girare con decisione TSMS sulla posizione di spegnimento, aspettare di misurare 0 Volt sul multimetro e poi girare con decisione GLVMS sulla posizione di spegnimento. Ripetere tutta la procedura dal punto 0 verificando il motivo di spegnimento (chiedere ad ESO).

	- Se tutte le procedure precedenti sono state seguite correttamente la macchina è accesa. Enjoy it.


* **FASE DA RUN A SET-UP E SPEGNIMENTO**

	- Per tornare in set-up una volta fermi, premere di nuovo in alto a SX. Se dopo 2-3 secondi non è in set-up, rischiacciatelo. Se la macchina non torna in set-up verificare che la tensione letta con il multimentro tra le bocchette TS+ e TS- corrisponda a quella sul volante. Se la tensione letta corrisponde la macchina è bloccata quindi spegnere la macchina tramite una delle due procedure:
	- Procedura di arresto di emergenza tramite funghi di shutdown.
	- Girare con decisione TSMS sulla posizione di spegnimento, aspettare di misurare 0 Volt sul multimetro e poi girare con decisione GLVMS sulla posizione di spegnimento. Ripetere tutta la procedura dal punto 0 verificando il motivo di spegnimento (chiedere ad un ESO).

	- Una volta in set-up (icona gialla), tornare sulla tab 1 e premere STOP (in basso a DX) per spegnere la macchina. Verificare che la tensione letta con il multimentro tra le bocchette TS+ e TS- corrisponda sia 0V. Se la tensione non scende spegnere la macchina tramite una delle due procedure:

		- Procedura di arresto di emergenza tramite funghi di shutdown.

		- Girare con decisione TSMS sulla posizione di spegnimento, aspettare di misurare 0 Volt sul multimetro e poi girare con decisione GLVMS sulla posizione di spegnimento. Ripetere tutta la procedura dal punto 0 verificando il motivo di spegnimento (chiedere ad un ESO).

	.. note:: In tutto questo, in ogni momento, si può usare il manettino di sinistra. Indipendentemente dalla sua posizione iniziale, quando parte la macchina le pompe vanno in automatico (come se il manettono fosse su AUTO). Se si vuole invece usare un'altra modalità, una volta partita l'interfaccia grafica del volante, bisogna girarlo sulla posizione voluta. Se è su 2 e si vuole lasciare su 2, per esempio, bisogna comunque metterlo tipo su 1 e poi di nuovo su 2, altrimenti rimane in AUTO. La posizione 1 (la seconda, ma quella con il numero 1) non funziona per qualche motivo, quindi usate solo posizioni OFF, 2 (50%), 3 (75%), 4 (100%) e AUTO.


Collegamento al Volante via SSH
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Per connettersi al volate è necessario che questo sia acceso (si può testarlo in macchina oppure attaccandolo all'alimentatore da banco.)
Bisognerà poi creare un hotspot al quale il raspberry si collegherà automaticamente, come anche il vostro dispositivo per poter effettuare una connesione SSH.

.. code-block:: sh

	ssh pi@eaglepi

Il prompt vi richiederà la password di pi@eaglepi: la password è :program:`eaglepi`

Una volta collegati al volante, per far iniziare il programma è necessario cercare l'eseguibile e digitare questo comando:

.. code-block:: sh

	./EagleSteeringWheel

Per riavviare il programma è sufficiente premere <Ctrl-C>

Effettuare modifiche al codice e fare il deploy dell'eseguibile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Se si desiderano effettuare modifiche al codice (sia alla parte C++ che a quella QML) e vederle applicate sul volante è sufficiente utilzzare gli script rasp_deploy.sh e deploy.sh entrambi presenti nella cartella Volante.

Il primo inizialmente monta la cartella contente il filesystem presente sul raspberry in una cartella di sistema (qualora non fosse ancora stata montata), successivamente compila il programma per Raspberry (in caso ci fossero file modificati rispetto alla versione già compilata) e lo invia tramite scp (SSH COPY) al volante collegato wireless.

Se l'output finale fosse qualcosa di simile a "./EagleSteeringWheel: file busy", significa che il programma è ancora in esecuzione sul Raspberry. In questo caso è sufficiente chiudere il programma sul Raspberry e far girare nuovamente lo script rasp_deploy.sh

.. code-block:: sh

	sudo killall Eaglestee(tab)

Oppure, con top, trovaimo il pid del processo e killiamo il processo. P.S. (tab) per autocompletamento

.. code-block:: sh

	kill -9 pid

Comando per compilare & deploy (su terminale):

.. code-block:: sh

	./rasp_deploy.sh

Ora dobbiamo far partire il programma con:

.. code-block:: sh

	sudo ./Eaglestee(tab)

Dalla cartella locale Volante mandare lo script e inserire :program:`raspberry`, se è vuoa inserire la password sudo personale.

.. code-block:: sh

	sudo ./raspberry


Il secondo (deploy.sh) serve per far partire il simulatore del volante sul PC locale. Questo script compila un progetto diverso che integra i file necessari per emulare i tasti e la seriale che si trovano sul volante quando è collegato in macchina.
Lo scopo di questo simulatore è di testare il codice in locale, velocemente e con maggiore controllo di quello che sta accandendo e di verificarne il reale funzionamento in macchina in una seconda fase.

Questo script crea una seriale virtuale con socat e due symlink (ttyV0 e ttyV1) che servono come endpoint per scrivere e leggere sulla seriale. Lo script fa partire sia il simulatore del volante che il simulatore della centralina, che risponde opportunamente agli input del volante.

Comando per compilare & deploy (su terminale):

.. code-block:: sh

	./deploy.sh

.. warning::

	IMPORTANTE CREARE UNA CARTELLA BUILD NELLA DIRECTORY CORRENTE
