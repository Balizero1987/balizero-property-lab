# Bali Zero Property Lab

## Ciao Krisna!

Questo repo è il tuo spazio per creare tools e prototipi per la sezione **Real Estate** di balizero.com.

## Obiettivo

Creare strumenti interattivi che aiutano gli stranieri a capire il mercato immobiliare di Bali:
- Come possono comprare casa/terreno legalmente
- Quali zone sono migliori per investimento
- Calcolare ROI e rental yield
- Confrontare le opzioni (leasehold vs freehold vs PT PMA)

## Idee per tools

### 1. 🧮 ROI Calculator
Calcola il ritorno sull'investimento:
- Prezzo acquisto
- Costi ristrutturazione
- Affitto mensile stimato
- Spese (maintenance, tasse, etc)
- → Mostra: Yield %, Break-even years

### 2. 🗺️ Area Matcher Quiz
Quiz interattivo: "Quale zona di Bali fa per te?"
- Budget
- Lifestyle (surf, yoga, nightlife, quiet)
- Scopo (investment, living, holiday home)
- → Suggerisce: Canggu / Ubud / Seminyak / Sanur / Uluwatu

### 3. 📊 Property Options Explainer
Flowchart interattivo su come stranieri possono comprare:
- Hak Pakai (leasehold)
- PT PMA (company ownership)
- Nominee (rischi!)
- → Pros/cons di ogni opzione

### 4. 💰 Investment Simulator
Simula 5-10 anni di investimento:
- Appreciation % annuo
- Rental income
- Inflazione
- → Grafico valore nel tempo

## Come iniziare

1. Apri Claude Code in questo folder
2. Scegli un tool da creare
3. Chiedi: *"Crea un [tool] per [scopo]"*

## Struttura suggerita

```
src/
├── calculator.html     # ROI Calculator
├── quiz.html          # Area Matcher
├── explainer.html     # Property Options
└── simulator.html     # Investment Simulator
data/
├── areas.json         # Dati zone Bali
├── prices.json        # Prezzi medi per zona
└── legal-options.json # Opzioni acquisto
public/
└── images/            # Immagini zone
```

## Dati utili

Prezzi medi per zona (2024-2025):
- Canggu: $150-300k (villa)
- Ubud: $100-200k (villa)
- Seminyak: $200-400k (villa)
- Sanur: $120-250k (villa)

Rental yield medio: 8-12% lordo

## Domande per Claude Code

- "Crea un calcolatore ROI per investimenti immobiliari a Bali"
- "Crea un quiz interattivo che suggerisce la zona di Bali ideale"
- "Crea un flowchart interattivo sulle opzioni di acquisto per stranieri"
- "Crea un simulatore di investimento con grafici"

Divertiti! 🏠🚀
