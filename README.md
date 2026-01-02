# ARACNE Tessi_PERSONE

Sistema multiagente per la creazione dialettica di personaggi narrativi complessi.

## Cosa fa

ARACNE guida la creazione di personaggi attraverso un processo dialettico: ogni scelta viene esplorata con 3+ opzioni motivate, ogni conflitto diventa opportunità di profondità narrativa.

## Quick Start

1. Copia il contenuto di `ARACNE_SYSTEM_PROMPT.md`
2. Incollalo come system prompt in Claude, GPT-4 o altro LLM avanzato
3. Inizia a creare personaggi

## Struttura Repository

```
ARACNE_Tessi_PERSONE/
├── ARACNE_SYSTEM_PROMPT.md        # Prompt principale (usa questo!)
├── ARACNE Tessi_PERSONE.md        # Documentazione metodologia
│
├── ARACNE PERSONE MULTIAGENTE/    # Prompt agenti specializzati
│   ├── PSYCHE.md                  # Psicologia e motivazioni
│   ├── PERSONA.md                 # Aspetto fisico e presenza
│   ├── VOX.md                     # Voce e idioletto
│   ├── CONTEXTO.md                # Background socio-culturale
│   ├── NEXUS.md                   # Relazioni e dinamiche
│   ├── MEMORIA.md                 # Persistenza e coerenza
│   └── EVOLUTIO.md                # Arco trasformativo
│
├── Template/                       # Template riutilizzabili
│   ├── Scheda_(Personaggio).md
│   └── Scheda Personaggi e integrazione con Universo Narrativo.md
│
├── Personaggi/                     # Personaggi creati
│
├── Esempi/                         # Esempi di output
│
└── Sistema/                        # File di gestione progetto
    ├── STATO_PROGETTO.md          # Stato sessioni (per continuità)
    └── To_Do.md                   # Idee e miglioramenti
```

## Comandi Principali

| Comando | Azione |
|---------|--------|
| `/nuovo` | Nuovo personaggio |
| `/carica` | Carica stato progetto |
| `/salva` | Salva stato sessione |
| `/stato` | Mostra fase corrente |
| `/sintesi` | Genera scheda completa |

## Persistenza tra Sessioni

Il sistema risolve il problema della memoria LLM:

1. **Inizio sessione**: Condividi `Sistema/STATO_PROGETTO.md`
2. **Durante**: ARACNE mantiene il contesto
3. **Fine sessione**: Usa `/salva` per aggiornare lo stato

## I Sette Agenti

| Agente | Ruolo |
|--------|-------|
| PSYCHE | Architettura psicologica, Enneagramma, traumi, difese |
| PERSONA | Aspetto fisico, presenza, linguaggio corporeo |
| VOX | Voce, idioletto, registri comunicativi |
| CONTEXTO | Epoca, luogo, classe sociale, economia |
| NEXUS | Relazioni, dinamiche di potere, conflitti |
| MEMORIA | Repository, coerenza, persistenza dati |
| EVOLUTIO | Arco trasformativo, want vs need, crescita |

## Principi Fondamentali

1. **Dialettica Creativa** - Sempre 3+ opzioni motivate
2. **Profondità Psicologica** - Modelli validati (Enneagramma, Jung, Attachment)
3. **Autenticità Culturale** - Personaggi radicati in contesti credibili
4. **Evoluzione Narrativa** - Archi che emergono organicamente

## Lingua

Il sistema opera in **italiano**. Tutti i prompt, template e output sono in italiano.

---

*Sistema ARACNE Tessi_PERSONE v3.0*
