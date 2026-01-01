
Il subagente riportato sotto è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione) 

- per VOX
VOX come è riportato nel file allegato è troppo complesso per essere utile: ricordati che lo scopo è quello di creare una scheda personaggio completa, e in questo caso in base all'età e alle caratteristiche specifiche del personaggio VOX dovrebbe immaginare che tipo di idoletto il personaggio parla, quindi produrre esempi e schemi di comunicazione verbale che il personaggio plausibilmente produrrà in vari contesti e con vari interlocutori (distinti per essere pari d'età, più anziani, o di ceto sociale ed economico diverso). Quindi verifica le istruzioni che possono essere funzionali a questo tipo di output

per PSYCHE: 
**PSYCHE** come è riportato nel file allegato è troppo complesso per essere utile: ricordati che lo scopo del ChatBOT è quello di creare una scheda personaggio completa, e in questo caso in base all'età e alle caratteristiche specifiche del personaggio (prese dai file presenti nella conoscenza del progetto) PSYCHE dovrebbe immaginare che tipo di personalità (carattere, temperamento) il personaggio abbia, quindi produrre esempi e schemi di comunicazione non-verbale (GESTUALITA e MICROCOMPORTAMENTI), motivazioni esterne, motivazioni interne, che il personaggio presenta anche in vari contesti e in varie situazioni, e dialogando con gli altri subagenti specializzati nel riconoscere e valorizzare altri aspetti rilevanti del personaggio e che possono influenzare il suo profilo psichico (MEMORIA, PERSONA, VOX, CONTEXTO, EVOLUTIO). Quindi verifica le istruzioni che possono essere funzionali alla capacità di questo subagente di interrogare gli altri subagenti e di produrre come output efficace la sezione dedicata al PROFILO PSICOLOGICO DEL PERSONAGGIO (che dovrà ovviamente contenere le sottosezioni più adatte a descrivere le mille sfaccettature della psiche di un personaggio).

- **TESSITORE CAPO**
Le istruzioni riportate sotto sono pensato per istruire TESSITORE CAPO il coordinatore di un architettura ChtBOT multiagente  in grado di interagire con 7 subagenti per contribuire alla produzione di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione) 

TESSITORE CAPO ha diversi compiti specificati nelle istruzioni. Rendilo in grado di funzionare da interfaccia di collegamento tra utente e sistemi multiagenti dedicati alle diverse specifiche funzioni. Deve capire quali agenti attivare, poter rilevare conflitti tra i dati in memoria e i nuovi dati presentati dall'utente o prodotti dai subagenti, specificarli senza nasconderli e suggerire opzioni per superarli e risolverli



Il subagente riportato sotto è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione)

per PERSONA: 
**PERSONA** come è riportato nel file allegato, in seguito a feedback ricevuti dall'Utente deve stabilire aspetto fisico, linguaggio corporeo, semiotica vestimentaria, presenza scenica del personaggio. Il processo deve essere dialettico e dialogico, grazie al confronto con altri aspetti che sono presenti nella scheda. Persona può anche interagire con gli altri subagenti per farsi aiutare a raffinare la sua risposta e per e rendere coerenti gli aspetti fisici e l'abbigliamento con quelli caratteriali e sociali. suggerisci cambiamenti e implementali rispetto alle istruzioni originali. Ricorda che alla fine l’output deve essere in formato markdown strutturato e chiaramente suddiviso per sezioni e sottosezioni, con titoli e, per ogni sottosezione (DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, etc.), una parte **ragionata** (spiega come arrivi a quell'attribuzione a partire dai dati-evidenza e dagli input degli altri agenti) e una parte **sintetica/conclusiva** utilizzabile direttamente nella scheda personaggio.

---

Il subagente CONTEXTO  è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una parte di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, CONTESTO CULTURALE, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione)

 Aiutami a istruire 🌍 CONTEXTO subagente specializzato per generare Background Socio-Culturale del personaggio in seguito a feedback ricevuti dall'Utente o a dati disponibili nella conoscenza del progetto. Il suo compito è di stabilire il contesto storico, culturale, sociale ed economico dove il personaggio è inserito. 
 Il processo deve essere dialettico e dialogico, grazie al confronto con altri aspetti che sono presenti nella scheda. CONTEXTO può anche interagire con gli altri subagenti per farsi aiutare a raffinare la sua risposta e per e rendere coerenti gli aspetti contestuali con l'abbigliamento, l'acconciatura, il senso comune e i "costumi culturali e sociali" del personaggio. Suggerisci cambiamenti e implementali rispetto alle istruzioni originali. Ricorda che alla fine l’output deve essere in formato markdown strutturato e chiaramente suddiviso per sezioni e sottosezioni, con titoli e, per ogni sottosezione (CONTESTO CULTURALE, CONTESTO SOCIALE etc.), una parte **ragionata** (spiega come arrivi a quell'attribuzione a partire dai dati-evidenza e dagli input degli altri agenti) e una parte **sintetica/conclusiva** utilizzabile direttamente nella scheda personaggio.

---
Il subagente NEXUS  è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una parte di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, CONTESTO CULTURALE, RELAZIONI E DINAMICHE, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione)

 Aiutami a istruire ⚡ NEXUS (Relazioni e Dinamiche) subagente specializzato per generare relazioni interpersonali del personaggio in seguito a feedback ricevuti dall'Utente o a dati disponibili nella conoscenza del progetto (schede di atri personaggi, in particolare la sezione dedicata alle interazioni interpersonali). Il suo compito è di stabilire la rete di rapporti personali (agonismo e antagonismo) con gli altri personaggi della storia, aiutando a definire le complesse dinamiche che si stabiliscono tra i personaggi. 
 Il processo deve essere dialettico e dialogico, grazie al confronto con altri aspetti che sono presenti nella scheda. NEXUS può anche interagire con gli altri subagenti per farsi aiutare a raffinare la sua risposta e per rendere coerenti gli aspetti di rapporti interpersonali e relazionali con le motivazioni, gli aspetti psicologici e caratteriali in quanto possono favorire amicizie e inimicizie tra personaggi. Suggerisci cambiamenti e implementali rispetto alle istruzioni originali. Ricorda che alla fine l’output deve essere in formato markdown strutturato e chiaramente suddiviso per sezioni e sottosezioni, con titoli e, per ogni sottosezione (RELAZIONI E DINAMICHE, CONTESTO CULTURALE, CONTESTO SOCIALE etc.), una parte **ragionata** (spiega come arrivi a quell'attribuzione a partire dai dati-evidenza e dagli input degli altri agenti) e una parte **sintetica/conclusiva** utilizzabile direttamente nella scheda personaggio.

---


## Memoria 
Il subagente 📜 MEMORIA (Repository e Continuità)  è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una parte di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, CONTESTO CULTURALE, RELAZIONI E DINAMICHE, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione)

 Aiutami a istruire 📜 MEMORIA (Repository e Continuità) subagente specializzato per garantire la raccolta e la consultazione dei dati salvati nella conoscenza del progetto. Il suo compito è di interagire con gli altri subagenti per aiutarli a raffinare le loro risposte con le schede personaggio e i loro dati più pertinenti per rendere coerenti gli output degli altri subagenti. Suggerisci cambiamenti e implementali rispetto alle istruzioni originali. Ricorda che alla fine l’output deve essere in formato markdown strutturato e chiaramente suddiviso per sezioni e sottosezioni, con titoli e, per ogni sottosezione (RELAZIONI E DINAMICHE, CONTESTO CULTURALE, CONTESTO SOCIALE etc.), una parte **ragionata** (spiega come arrivi a quell'attribuzione a partire dai dati-evidenza e dagli input degli altri agenti) e una parte **sintetica/conclusiva** utilizzabile direttamente nella scheda personaggio.
 
---
#🔄
# 🔄 EVOLUTIO (Arco di Trasformazione)

Il subagente 🔄 EVOLUTIO (Arco di Trasformazione)  è pensato per rispondere alle chiamate di TESSITORE CAPO e di interagire con altri subagenti per contribuire alla produzione di una parte di una scheda personaggio (ogni subagente avendo una funzione specializzata e quindi un compito di definire aspetti specifici ed esempi pratici della scheda del personaggio, per es., DATI ANAGRAFICI; ASPETTO FISICO, VOLTO E LINEAMENTI, PROFILO PSICOLOGICO STRATIFICATO, CONTESTO CULTURALE, RELAZIONI E DINAMICHE, ecc.). 

Gli altri subagenti sono parte di questa architettura: ## 
TESSITORE CAPO coordina: 
├── 🧠 PSYCHE (Psicologia e Motivazioni) 
├── 🎭 PERSONA (Aspetto Fisico e Presenza) 
├── 🗣️ VOX (Voce e Idioletto)
├── 🌍 CONTEXTO (Background Socio-Culturale)
├── ⚡ NEXUS (Relazioni e Dinamiche) 
├── 📜 MEMORIA (Repository e Continuità) 
└── 🔄 EVOLUTIO (Arco di Trasformazione)

 Aiutami a istruire EVOLUTIO (Arco di Trasformazione) subagente specializzato per garantire l'ideazione degli archi narrativi, presente e futuri del personaggio. Il suo compito è di interagire con gli altri subagenti per integrare i loro dati sulla scheda personaggio e suggerire almeno tre opzioni pertinenti per gli archi narrativi del personaggio. Suggerisci cambiamenti e implementali rispetto alle istruzioni originali. Ricorda che alla fine l’output deve essere in formato markdown strutturato e chiaramente suddiviso per sezioni e sottosezioni, con titoli e, per ogni sottosezione (RELAZIONI E DINAMICHE, CONTESTO CULTURALE, CONTESTO SOCIALE etc., ARCHI NARRATIVI), una parte **ragionata** (spiega come arrivi a quell'attribuzione a partire dai dati-evidenza e dagli input degli altri agenti) e una parte **sintetica/conclusiva** utilizzabile direttamente nella scheda personaggio.



