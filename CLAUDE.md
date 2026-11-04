# Landing DomUnica — recap del progetto

Leggi tutto questo file prima di rispondere a qualsiasi richiesta su questo progetto. Rispondi sempre in italiano.

## Cos'è

Landing page per **DomUnica** (Roma), azienda di isolamento termico nanotecnologico: un rasante con microsfere ceramiche cave che si applica sulle pareti in **2 mm**.

**Obiettivo della landing, da tenere sempre al centro di testi e sezioni: Ristrutturazione e trattamento interno.**

Offerta:
- **Sopralluogo gratuito**
- **Analisi termica con termocamera**: è a pagamento, ma **non scrivere mai "a pagamento"** (l'utente l'ha fatto togliere). Al massimo "su richiesta".

Sito di riferimento per lo stile: https://domunica.it

## Dati del cliente (veri, da usare così)

- Telefono: **327 3019773** (WhatsApp: `https://wa.me/393273019773`)
- Sede legale: **Via XX Settembre 118, 00187 Roma**
- **Si riceve su appuntamento**
- Email (dal loro sito): info@domunica.it
- Logo: `https://domunica.it/wp-content/uploads/2023/07/Logo___Domunica.png` (piccolo, 296 px: serve l'SVG dal cliente)

Contenuti forniti dall'utente:
- Il prodotto finale è già la finitura: **sopra non si può posare niente**. Si fa in **qualsiasi colore**, consigliati i **colori chiari**.
- Puntare sulla **pulizia post cantiere**.
- Durata minima **25 anni**. Atossico, completamente **green**.
- Oltre a riflettere il calore: elimina il muro freddo (quindi condensa e muffa), è **ignifugo** e **altamente traspirante**.

## Regole fisse dell'utente (rispettale sempre)

- **Font: solo Exo** (Google Fonts). Niente altri font.
- **Niente foto stock** (Unsplash, Pexels…): le trova orrende o sgranate. Si usano **solo le immagini create dall'utente** (immagini AI in stile brand: tecnico in **tuta verde**, luce calda, case luminose), salvate in `img/`. Se hanno loghi o scritte impresse, ritagliarle.
- Le immagini devono essere **nitide**: mai mostrarle più grandi della loro risoluzione reale.
- **Colori del prodotto: solo bollini piccoli e piatti** (circa 52 px, senza riflessi né ombre), niente foto di stanze, niente etichette "Consigliato".
- **Termografia interattiva**: muovendo il cursore si leggono la temperatura e lo stato del muro. Va tenuta.
- Non ripetere "riflette il calore" più volte nei testi.
- Header sempre visibile, ombre leggere.
- **Lavorare in locale.** Pubblicare su Vercel o fare push su GitHub **solo quando l'utente lo chiede esplicitamente**.
- Il design non deve sembrare un template ("uguale ad altre mille"). Da evitare:
  - etichette in MAIUSCOLO sopra i titoli;
  - file di numeri grandi tipo statistiche;
  - schede tutte uguali con la stessa ombra;
  - animazioni di comparsa su ogni sezione;
  - frecce "→" nei pulsanti;
  - sfondi crema o pesca.

## Cosa è stato bocciato (non riproporre)

1. Prima versione "template": foto stock, schede con icone, fila di numeri, etichette maiuscole.
2. Titoli bocciati:
   - "Rinnova casa e isola le pareti in soli 2 mm"
   - "Addio muri freddi e muffa, nello spessore di una moneta"
   - "Ristrutturi casa? Falla anche calda, sana e senza muffa"
3. Galleria di foto per i colori, e bollini grandi con effetto lucido 3D ("orrendi").
4. Foto prima/dopo, "Ambienti protetti" e "Trattamento" nella sezione del cantiere.
5. **Apertura divisa fuori/dentro** (metà blu con 3 °C, metà calda con 21 °C, linea verde al centro): "non mi piace per niente".

## Titolo scelto dall'utente (non cambiarlo)

**"2 mm. È tutto ciò che separa il freddo fuori dal caldo dentro."**, con "separa" in grassetto, come nella grafica social dell'utente.

## File

- `index.html`: tutta la landing (HTML + CSS + JS in un unico file).
- `img/parete-2mm-microsfere.webp` (1080×1350): sezione della parete con lo zoom sulle microsfere. Immagine dell'utente.
- `img/applicazione-trattamento.jpg` (1080×890): tecnico in tuta verde che applica a rullo, famiglia e cane sullo sfondo. Immagine dell'utente, ritagliata per togliere il watermark.
- `img/sopralluogo.webp` (1672×941): tecnico in tuta verde con una coppia e un tablet. Immagine dell'utente.
- `.claude/launch.json` + `.claude/serve.js`: piccolo server Node per l'anteprima locale su **http://localhost:5173** (avvialo con `preview_start` e nome `landing`).
- `.vercelignore`: esclude dal sito pubblicato `.claude`, `.gitignore` e questo file.

## Struttura attuale della pagina (in locale)

1. **Header** fisso: logo, menu (Come funziona, Sopralluogo, Colori, Il cantiere, Domande), telefono, pulsante "Prenota il sopralluogo".
2. **Apertura come il post social dell'utente**:
   - foto a tutto schermo con una riga piccola "Ristrutturazione e trattamento termico interno a Roma", poi "2 mm" enorme in bianco e la frase;
   - sotto, una **barra verde** (verde scuro `#04A527`) con il telefono nel cerchio bianco, la nota "Sopralluogo gratuito, si riceve su appuntamento" e il pulsante bianco "Prenota il sopralluogo gratuito";
   - il pulsante WhatsApp flottante si nasconde finché la barra verde è visibile;
   - ⚠️ la foto attuale è un **segnaposto** (la parete con le microsfere).
3. **Dentro quei 2 millimetri**: l'immagine della parete, la spiegazione delle microsfere e un **confronto disegnato in scala** (barra del cappotto in pannelli da circa 12 cm contro la lineetta verde da 2 mm). Riporta anche "Su 100 m² recuperi fino a 4 m²", dato preso dal sito del cliente.
4. **Si comincia da casa tua**: due righe alternate.
   - Sopralluogo: foto, testo, pulsante. È "Gratuito".
   - Analisi con termocamera: testo e **termografia interattiva**. È disegnata su canvas da una mappa di temperature: cursore → °C + stato (muro freddo / dispersione / comfort / fonte di calore). Quando nessuno la usa, il mirino gira da solo.
5. **Cosa cambia nella tua casa** (sfondo `#EEF2F7`): immagine del tecnico e 5 vantaggi in elenco semplice, senza icone.
6. **Il trattamento è già la finitura**: 8 bollini colore (bianco caldo, sabbia, grigio perla, vaniglia, azzurro polvere, verde salvia, rosa cipria, "qualsiasi altro colore") e la nota sui colori chiari.
7. **Un solo cantiere** (sfondo blu): percorso in 4 tappe collegate da una linea verde.
   - Sopralluogo, gratuito;
   - Analisi termica, su richiesta;
   - Lavori e trattamento;
   - Pulizia e consegna.
8. **Domande frequenti** (accordion a righe): le 5 domande dell'utente più "Posso pitturare o mettere qualcosa sopra?".
9. **Contatti** (sfondo `#EEF2F7`): dati e form. Il form non ha server: **apre WhatsApp con il messaggio già compilato**.
10. **Footer** blu scuro.

Palette: verde `#06C12E` / `#04A527`, blu del logo `#1B2760`, blu scuro `#121A46`, bianco, grigio-azzurro `#EEF2F7`, testo `#1F1F25`.

## Stato di pubblicazione

- **GitHub**: https://github.com/chiaranebuloni-beep/domunica, ramo `main`. Redesign e questo file sono committati e pushati (4 novembre 2026). L'autore è configurato come "Giulia Carra" / giulia.carra@reddoak.com. Il nome è stato ricavato dall'email: l'utente può cambiarlo.
- **Vercel**: https://domunica.vercel.app (progetto `domunica`, account `info-14619257`, deploy con `npx vercel@latest deploy --prod --yes`). **Online c'è ancora la PRIMA versione** (quella bocciata), non il redesign.
- **Collegamento automatico Vercel ↔ GitHub: non riuscito.** Errore: "You need admin or write access to the repository". L'utente deve dare all'app Vercel l'accesso al repo `chiaranebuloni-beep/domunica`:
  - da Vercel: progetto → Settings → Git;
  - oppure da GitHub: Settings → Applications → Vercel → Repository access.

  Poi si rilancia `npx vercel@latest git connect https://github.com/chiaranebuloni-beep/domunica.git --yes`. Da quel momento ogni push su `main` va online: non fare push senza chiedere.

## Prossimi step

1. **Foto per l'apertura** (priorità): l'utente deve mandare la sua immagine "donna alla finestra con la neve fuori" **senza scritte, logo e barra verde**.
   - Formato: orizzontale 16:9, almeno 2400×1350, con spazio libero a sinistra per il testo. Se possibile anche una versione verticale 4:5 (1080×1350) per il telefono.
   - Poi va sostituita in `.hero-photo`; la parete con le microsfere resta solo nella sezione "Dentro quei 2 millimetri".
2. **Approvazione del resto della pagina** da parte dell'utente: dopo l'apertura, le sezioni sotto non sono ancora state commentate.
3. **Logo vettoriale (SVG)** dal cliente, al posto del PNG piccolo.
4. **Testi da far confermare al cliente**:
   - pulizia post cantiere a loro carico;
   - "atossico a base acqua";
   - "Su 100 m² recuperi fino a 4 m²";
   - cappotto tradizionale "circa 12 cm".
5. **Privacy**: collegare la casella del consenso nel form all'informativa del cliente.
6. **Immagine di anteprima per la condivisione** (1200×630) e i meta tag Open Graph.
7. **Collegare Vercel a GitHub** (vedi sopra), poi, **solo su richiesta dell'utente**, fare commit e push del redesign o un nuovo deploy su Vercel.
8. Eventuale **dominio**: da aggiungere su Vercel in Settings → Domains (es. una pagina su domunica.it).

## Come lavorare con l'utente

- L'utente scrive in italiano, in modo diretto e veloce. Mostra le modifiche nell'anteprima locale e verifica sempre desktop e mobile (375 px) prima di dire che è fatto.
- Quando una scelta è di gusto (titoli, impaginazione dell'apertura), proponi 2–3 opzioni con un'anteprima invece di andare a tentativi.
- L'utente crea da sé le immagini mancanti: quando serve una foto, descrivi esattamente soggetto, formato e risoluzione.
