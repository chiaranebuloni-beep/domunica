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

## Regola sui testi: "se non è vero non lo mettiamo" (decisione dell'utente, 5 novembre 2026)

I rapporti Certimac pubblicati su domunica.it (SQM_122, 123, 124 del 2026, prodotto PSC 250T) non sostengono le promesse sull'isolamento:
- conducibilità 0,084 W/mK, emissività 0,90, riflettanza solare 0,89 (SRI 102);
- la dispersione del muro cala del 3,36% su una parete anni '60-'70 e dello 0,55% su una moderna;
- il rapporto dice che le proprietà radiative non cambiano lo scambio termico.

**Non rimettere senza misure o documenti del cliente:**
- "isola come un cappotto", "piccoli specchi", caldo d'inverno e fresco d'estate, meno consumi: smentiti o non sostenuti dai rapporti;
- elimina muro freddo, condensa e muffa: nessuna prova;
- "completamente green" e sicuro per bambini e animali: servono documenti;
- inodore: serve conferma.

Confermati dal cliente secondo l'utente (5 novembre 2026, senza documenti visti): "durata minima 25 anni", "ignifugo", "atossico", "traspirante", "senza VOC". Sono scritti senza "dichiarato". Da farsi dare comunque per iscritto: garanzia, certificato antincendio, scheda di sicurezza. Loghi "Si fidano di noi": aggiunti su richiesta dell'utente; restano da confermare che siano clienti di DomUnica e che ci sia il permesso di usarli. Il sito del cliente scrive invece "durata stimata superiore ai 25 anni". I rapporti non vanno citati o riprodotti senza il permesso scritto di Certimac. Gli elenchi in "Contenuti forniti dall'utente" qui sopra vanno letti alla luce di questa regola.

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

1. Prima versione "template" con foto stock. Attenzione: il 5 novembre 2026 l'utente ha scelto la versione online, che ha schede con icone, fila di numeri ed etichette maiuscole ma usa le sue immagini.
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
- `img/apertura-finestra.webp` (1122×1402): donna sul divano con la tazza, neve fuori dalla finestra, zoom sulle microsfere. Immagine dell'utente, usata in apertura.
- `img/parete-2mm-microsfere.webp` (1080×1350): sezione della parete con lo zoom sulle microsfere. Immagine dell'utente, al momento non usata.
- `img/applicazione-trattamento.jpg` (1080×890): tecnico in tuta verde che applica a rullo, famiglia e cane sullo sfondo. Immagine dell'utente, ritagliata per togliere il watermark.
- `img/sopralluogo.webp` (1672×941): tecnico in tuta verde con una coppia e un tablet. Immagine dell'utente.
- `.claude/launch.json` + `.claude/serve.js`: piccolo server Node per l'anteprima locale su **http://localhost:5174** (avvialo con `preview_start` e nome `landing`).
- `.vercelignore`: esclude dal sito pubblicato `.claude`, `.gitignore` e questo file.

## Struttura attuale della pagina (versione scelta dall'utente il 5 novembre 2026)

`index.html` parte dal commit `5027dad`, la versione online su https://domunica.vercel.app. L'utente ha detto che deve essere così, quindi questa è la base di lavoro. Poi, su richiesta dell'utente: sezioni del cantiere unite, testi riscritti secondo la regola qui sopra, fila di numeri e riquadri "2 mm" tolti, "separa" unico grassetto del titolo, form su Web3Forms.

1. **Barra superiore** verde (telefono, email, "Si riceve su appuntamento") e **header** con logo, menu (Il trattamento, Colori, Cantiere pulito, Domande frequenti) e pulsante "Sopralluogo gratuito".
2. **Apertura su sfondo chiaro**: etichetta, "2 mm." in verde, la frase, testo, pulsanti "Prenota il sopralluogo gratuito" e "Chiama", 3 etichette con spunta, a fianco l'immagine `apertura-finestra.webp` con l'etichetta "Microsfere ceramiche" in basso a sinistra, per non coprire lo zoom.
3. **Due modi per conoscere la tua casa**: due schede, sopralluogo (gratuito) e analisi con termocamera con la **termografia interattiva**.
4. **Uno strato sottile, tre vantaggi concreti**: immagine del tecnico e 3 vantaggi (niente pannelli, già la finitura, un solo cantiere).
5. **Il trattamento è già la finitura**: 8 bollini colore e la nota sulle tinte chiare.
6. **Un solo cantiere** (sfondo blu): 4 tappe numerate. Sopralluogo (gratuito), analisi termica (su richiesta), lavori e trattamento, pulizia e consegna.
7. **Domande frequenti**: 7 domande a righe compatte in un unico riquadro, tutte chiuse all'inizio, una sola aperta alla volta, con apertura animata. "Cos'altro fa il prodotto?" è stata tolta dall'utente; "ignifugo" e "traspirante" stanno nella risposta su "È un prodotto tossico?". Il cantiere si anima in sequenza e i loghi compaiono uno dopo l'altro.
8. **Si fidano di noi**: fascia con 8 loghi in `img/loghi/`, presi dal sito del cliente (Heineken, Opel, Chevron, Veolia, Linde, Orlen, MOL, Agrofert). Sta prima dei contatti per scelta dell'utente, non sotto l'apertura.
9. **Contatti**: dati e form, che **invia la richiesta via email con Web3Forms**. WhatsApp resta solo nel pulsante flottante. Poi footer.

**Per attivare il form:** incollare la chiave dell'account Web3Forms nell'attributo `data-key` di `#lead-form`. Finché è vuoto il form non invia e mostra il telefono.

Differenze rispetto alle regole qui sopra, accettate perché l'utente ha scelto questa versione: etichette in maiuscolo, schede e icone, animazioni di comparsa, frecce nei pulsanti. Non toglierle né aggiungerne altre senza chiedere.

## Redesign accantonato (commit `cefb062`, non è più nella pagina)

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
- **Vercel**: https://domunica.vercel.app (progetto `domunica`, account `info-14619257`, deploy con `npx vercel@latest deploy --prod --yes`). Online e su `main` c'è la versione con le modifiche del 5 novembre 2026, pubblicata su richiesta dell'utente. **Il form online non invia finché non si inserisce la chiave Web3Forms**: mostra il telefono.
- **Collegamento automatico Vercel ↔ GitHub: non riuscito.** Errore: "You need admin or write access to the repository". L'utente deve dare all'app Vercel l'accesso al repo `chiaranebuloni-beep/domunica`:
  - da Vercel: progetto → Settings → Git;
  - oppure da GitHub: Settings → Applications → Vercel → Repository access.

  Poi si rilancia `npx vercel@latest git connect https://github.com/chiaranebuloni-beep/domunica.git --yes`. Da quel momento ogni push su `main` va online: non fare push senza chiedere.

## Prossimi step

1. **Foto per l'apertura** (valeva per il redesign, sospeso finché l'utente non la richiede): l'utente deve mandare la sua immagine "donna alla finestra con la neve fuori" **senza scritte, logo e barra verde**.
   - Formato: orizzontale 16:9, almeno 2400×1350, con spazio libero a sinistra per il testo. Se possibile anche una versione verticale 4:5 (1080×1350) per il telefono.
   - Poi va sostituita in `.hero-photo`; la parete con le microsfere resta solo nella sezione "Dentro quei 2 millimetri".
2. **Approvazione del resto della pagina** da parte dell'utente: dopo l'apertura, le sezioni sotto non sono ancora state commentate.
3. **Logo vettoriale (SVG)** dal cliente, al posto del PNG piccolo.
4. **Testi da far confermare al cliente**:
   - pulizia post cantiere a loro carico;
   - "atossico a base acqua";
   - "Su 100 m² recuperi fino a 4 m²";
   - cappotto tradizionale "circa 12 cm".
5. **Privacy e form**: chiave Web3Forms dall'utente; collegare la casella del consenso all'informativa del cliente, che deve citare anche Web3Forms. Il form non è ancora stato provato con un invio reale.
6. **Immagine di anteprima per la condivisione** (1200×630) e i meta tag Open Graph.
7. **Collegare Vercel a GitHub** (vedi sopra), poi, **solo su richiesta dell'utente**, fare commit e push del redesign o un nuovo deploy su Vercel.
8. Eventuale **dominio**: da aggiungere su Vercel in Settings → Domains (es. una pagina su domunica.it).

## Come lavorare con l'utente

- L'utente scrive in italiano, in modo diretto e veloce. Mostra le modifiche nell'anteprima locale e verifica sempre desktop e mobile (375 px) prima di dire che è fatto.
- Quando una scelta è di gusto (titoli, impaginazione dell'apertura), proponi 2–3 opzioni con un'anteprima invece di andare a tentativi.
- L'utente crea da sé le immagini mancanti: quando serve una foto, descrivi esattamente soggetto, formato e risoluzione.
