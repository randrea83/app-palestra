# Scheda Palestra

App web statica (HTML + JS, nessuna dipendenza) per gestire la scheda di allenamento in palestra.

## Funzionalità

- Esercizi divisi per gruppo muscolare: Corsa, Spalle, Schiena, Braccia, Addome, Petto, Gambe, Ultima corsa
- Aggiunta e rimozione di esercizi (pulsante "+" per gruppo, modulo in fondo, "Rimuovi esercizio" nel dettaglio)
- Nome esercizio modificabile
- Check di completamento per ogni esercizio
- Campi modificabili per serie, ripetizioni, peso/velocità
- Campo note per altezza macchina / regolazioni
- Timer della sessione (avvio/pausa/reset)
- Barra di progresso e conteggio per sezione
- Storico delle ultime sessioni (data, durata, esercizi completati)
- Tema chiaro/scuro
- Dati salvati nel browser (localStorage), nessun server richiesto

## Utilizzo

Basta aprire `index.html` in un browser. Per pubblicarlo online si può usare GitHub Pages:

1. Impostazioni del repository → Pages
2. Source: `Deploy from a branch`, branch `main`, cartella `/ (root)`
3. L'app sarà raggiungibile su `https://<tuo-utente>.github.io/<nome-repo>/`

## Licenza

Uso personale.
