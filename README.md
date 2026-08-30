<div align="center">

<a href="https://solarys431.github.io/vortex-communication-os/"><img src="assets/banner.png" alt="VORTEX Meet — prototipo per riunioni multilingue" width="100%"></a>

<strong>Italiano</strong> · <a href="README_EN.md">English</a>

🌐 <a href="https://solarys431.github.io/vortex-communication-os/">Landing page</a>

</div>

---

## Cos'è

VORTEX Meet è un **prototipo funzionale** per riunioni multilingue. Un **modulo di traduzione simultanea AI** produce voce e sottotitoli tradotti nelle dieci lingue supportate; un **assistente** trascrive la sessione e genera verbale e sintesi al termine. È autonomo e predisposto per future integrazioni broadcast.

![La stanza VORTEX Meet con traduzione simultanea AI](assets/software-reale/meet-stanza-reale.jpg)

---

## Funzioni principali

### Tre modalità: traduci, assisti o resta privato
Quando crei la stanza scegli la modalità: **Traduzione** (sottotitoli e voce dal vivo), **Assistente** (trascrive e interviene solo quando lo chiami per nome), oppure **Privato** (nessun agente). Inviti i partecipanti con un link; microfono e camera si attivano solo dopo il consenso.

![Creazione della stanza e scelta dell'agente](assets/software-reale/meet-lobby.jpg)

### Traduzione simultanea, parlata e scritta
In tempo reale, ogni partecipante può ascoltare e leggere la traduzione nella lingua selezionata. Sono supportate dieci lingue: italiano, inglese, spagnolo, francese, tedesco, portoghese, olandese, russo, giapponese e cinese. Un canale dati è predisposto per future integrazioni broadcast.

### Sottotitoli dal vivo e verbale
Sottotitoli tradotti in tempo reale, attribuiti all'identità del partecipante. Nelle riunioni con memoria la trascrizione resta ricercabile; a fine sessione l'assistente genera il **verbale**, con decisioni e attività da seguire.

### Connettività tramite relay
La stanza usa un **relay esterno** configurato per migliorare la connettività attraverso reti, NAT e firewall, da casa, dall'ufficio o da rete mobile. Le prestazioni dipendono comunque dalla qualità della connessione.

---

## Come funziona

La logica gira su un server LiveKit autogestito e l'audio usa un trasporto in tempo reale. I moduli AI per traduzione e assistenza entrano nella stanza in base alla modalità selezionata. L'assistente interviene solo quando viene chiamato per nome.

---

## Stato

**Prototipo funzionale.** Questa repository e la relativa landing sono pubbliche; il codice sorgente dell'applicazione non è incluso. Il sito è statico, senza cookie né tracciamento; le schermate mostrano il prodotto con dati dimostrativi.

<div align="center">

© 2026 Daniele Cappello

</div>
