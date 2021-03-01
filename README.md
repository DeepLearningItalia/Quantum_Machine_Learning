# Quantum_Machine_Learning

Benvenuto studente!
Questo repository si divide in 4 parti:
- QBoost --> Credits: https://github.com/dwavesystems/qboost
- Feature Selection --> https://github.com/dwave-examples/mutual-information-feature-selection
- Clustering --> https://github.com/dwave-examples/clustering
- Quantum Restricted Boltzmann Machines --> https://github.com/mercari/CFQIRBM

Molto del codice forkato qui è preso da altri repository, e per questo sono indicati in modo da darvi la possibilità di seguire eventuali aggiornamenti della codebase.
Il concetto più importante del fare scienza è il "non reinventare mai la ruota", quindi invito tutti voi a cercare sempre qualcosa che assomiglia al vostro problema e partire ad elaborare da quel punto, piuttosto che iniziare sempre from scratch.

Per eseguire i codici presenti all'interno del corso avrete bisogno di:
- Python 3.7
- D-Wave Ocean SDK
- D-Wave DMod
- Numpy, Scipy, Pandas

Tutta la codebase è pensata per essere eseguita su un Quantum Annealer, nello specifico quello proprietario di D-Wave. Il motivo di questa scelta risiede nel fatto che il ML non richiede necessariamente la soluzione ottima alla funzione obbiettivo per poter essere utilizzato in pratica, ed una piattaforma di adiabatic computing con abbastanza qubits può fin da subito essere impiegata per iniziare a risolvere i primi problemi pratici, anche al di fuori dalla sfera didattica. Per ulteriori dettagli rimando il video relativo dove spiego il motivo alla base della scelta del quantum annealer di D-Wave.

Autore:

Calogero Zarbo - calogerozarbo88@gmail.com
