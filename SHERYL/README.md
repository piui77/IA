# SHERYL — Automobili d’eccezione dal 1940

Sito statico di una casa automobilistica immaginaria che realizza esemplari unici di lusso. L’archivio 1940–1959 comprende venti modelli, quattro dei quali sono concept car.

## Contenuti

- Venti schede tecniche, con prezzo immaginario in lire e conversione nominale in euro.
- Sessanta immagini: carrozzeria, interni e motore per ogni modello.
- Logo e monogramma SHERYL in SVG.
- Gallerie ingrandibili, selezione per decennio, filtri per le concept e tabella comparativa.

## File

- `index.html`: pagina iniziale.
- `style.css`: grafica e adattamento agli schermi.
- `app.js`: gallerie, schede e filtri.
- `cars.json`: dati dei modelli.
- `assets/`: immagini e loghi.

## Utilizzo

Non servono Node.js o compilazione. Copiare l’intera cartella su un server web statico, mantenendo la struttura dei file. Per un’anteprima locale, dalla cartella SHERYL eseguire `python -m http.server 8000` e aprire http://localhost:8000. Il caricamento di cars.json richiede un server web: l’apertura diretta di index.html come file locale può essere bloccata dal browser.

## Sito pubblicato

https://sheryl-automobili.halepeony4.chatgpt.site

L’accesso al sito Sites è privato. Questo repository contiene una copia del progetto; le modifiche su GitHub non vengono pubblicate automaticamente su Sites.

Marchio, storia, automobili e specifiche sono immaginari. Le immagini sono generate con IA. Gli importi in euro sono conversioni nominali delle lire, senza rivalutazione per inflazione.
