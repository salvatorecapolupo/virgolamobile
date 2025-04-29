# IEEE 754 Converter (32-bit)

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Bootstrap](https://img.shields.io/badge/framework-Bootstrap%205-brightgreen.svg)

Un tool web responsive per convertire numeri decimali in IEEE 754 a 32 bit, completo di passaggi di calcolo dettagliati e arrotondamento “round-to-nearest-even”.

---

## 📖 Descrizione

Questo progetto offre una pagina HTML/JavaScript basata su Bootstrap 5 che replica (e migliora) la funzionalità del converter di h-schmidt.net:

- Input singolo per numeri decimali (positivi, negativi, zero)  
- Calcolo di **segno**, **esponente** (con bias 127) e **mantissa** (23 bit)  
- Gestione del **round-to-nearest-even** (guard e sticky bit)  
- Overflow della mantissa con incremento automatico dell’esponente  
- Visualizzazione in tempo reale dei passaggi algoritmici  
- UI responsive con schede “Risultato” e “Procedimento”  

---

## 🚀 Caratteristiche

- **Zero handling**: zero → tutti bit a 0  
- **Padding sicuro**: esponente a 8 bit, mantissa a 23 bit  
- **Raggruppamento**: output IEEE 754 diviso in ottetti da 8 bit  
- **Tab responsive**: separazione chiara tra risultato e dettaglio calcoli  
- **No dipendenze server**: tutto in HTML/CSS/JS client-side  

---

## 📂 Struttura del repository

