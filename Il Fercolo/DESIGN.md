---
name: Annunziata 413

# ==========================================
# PALETTE COLORI (Impostazioni di base)
# Questi sono i colori che verranno usati nel sito. 
# Ad esempio, 'primary' diventerà 'bg-primary' o 'text-primary' nel codice HTML.
# ==========================================
colors:
  surface: '#fbf9f5' # Sfondo generale chiaro
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff' # Bianco puro, usato per riquadri
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a' # Colore del testo scuro sugli sfondi chiari
  on-surface-variant: '#43474f' # Testo secondario (grigio scuro)
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#737780' # Colore per linee e bordi generici
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40' # BLU MARIANO - Colore principale del sito
  on-primary: '#ffffff' # Colore del testo (bianco) che va sopra il Blu Mariano
  primary-container: '#003366' # Blu Mariano leggermente più chiaro (es. bottoni)
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#775a19' # ORO - Colore per accenti e dettagli
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#221e0d'
  on-tertiary: '#ffffff'
  tertiary-container: '#383321'
  on-tertiary-container: '#a29b83'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ebe2c8'
  tertiary-fixed-dim: '#cec6ad'
  on-tertiary-fixed: '#1f1c0b'
  on-tertiary-fixed-variant: '#4c4733'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
  pergamena: '#F4EBD0'
  avorio: '#FDFBF7'
  oro: '#C5A059'

# ==========================================
# TIPOGRAFIA E FONT
# Qui definiamo le dimensioni e i caratteri.
# ==========================================
typography:
  display-lg: # Titolo gigante (es. nella foto di apertura)
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile: # Titolo gigante adattato per cellulare
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md: # Titoli delle sezioni principali
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm: # Titoli più piccoli
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg: # Testo descrittivo in evidenza
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md: # Testo normale (paragrafi base)
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps: # Testino piccolo tutto in maiuscolo
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em

# ==========================================
# SMUSSATURA DEGLI ANGOLI (Bordi arrotondati)
# Definisce quanto sono curvi i box, le immagini e i pulsanti.
# ==========================================
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem # Valore standard (circa 4px) per un look squadrato ma morbido
  md: 0.375rem
  lg: 0.5rem # Usato per i bordi delle immagini grandi
  xl: 0.75rem
  full: 9999px # Usato per cerchi perfetti (es. pallini della timeline)

# ==========================================
# SPAZIATURE (Margini e Padding)
# Definisce le distanze tra gli elementi per dare un aspetto ordinato.
# ==========================================
spacing:
  base: 8px
  section-gap-desktop: 120px # Spazio verticale enorme tra le sezioni su PC
  section-gap-mobile: 64px # Spazio verticale ridotto su smartphone
  grid-margin: 24px # Margini laterali di sicurezza
  grid-gutter: 24px # Spazio tra una colonna e l'altra
---

<!-- ==========================================
     MANUALE DI STILE (IL PROGETTO DEL SITO)
     ========================================== -->

## Brand e Stile

Il design system è ancorato all'intersezione tra solennità storica e accessibilità contemporanea. È stato creato per la 413° edizione di una tradizione sacra e richiede un linguaggio visivo che appaia al tempo stesso antico e vitale[cite: 10].

La direzione estetica è un **Editoriale Sofisticato**[cite: 10]. Utilizza una combinazione di caratteri tipografici con grazie ad alto contrasto e una palette di colori limitata e regale, per evocare un senso di "prestigio sacro"[cite: 10]. L'interfaccia si ispira ai classici layout degli archivi italiani (ampi spazi bianchi, allineamenti meticolosi, dettagli in oro) mantenendo al contempo la chiarezza funzionale del web moderno[cite: 10]. La risposta emotiva suscitata deve essere di devozione, orgoglio cittadino e continuità storica[cite: 10].

## Colori

La palette affonda le radici nell'iconografia mariana e nella tradizione liturgica[cite: 10].

*   **Primario (Blu Mariano - #003366):** Utilizzato per la navigazione principale, i titoli e gli elementi chiave del brand[cite: 10]. Rappresenta il manto della Vergine e offre un contrasto profondo e autorevole[cite: 10].
*   **Secondario (Oro - #C5A059):** Un oro satinato e tenue, usato per accenti, bordi e stati interattivi (pulsanti)[cite: 10]. Va usato con parsimonia per mantenerne il valore percepito[cite: 10].
*   **Sfondi:** 
    *   **Avorio (#FDFBF7):** Lo sfondo predefinito per le pagine testuali standard, riduce l'affaticamento visivo[cite: 10].
    *   **Pergamena (#F4EBD0):** Riservato alle sezioni storiche, alle linee del tempo (timeline) e ai componenti di "archivio" per conferire un effetto tattile, simile alla carta[cite: 10].
    *   **Bianco (#FFFFFF):** Utilizzato per le utilità dinamiche, i moduli o i dati ad alta densità[cite: 10].

## Tipografia

Il design utilizza un accoppiamento tipografico ad alto contrasto per unire visivamente il 1611 ai giorni nostri[cite: 10].

**Titoli (Playfair Display):** Devono essere impostati con una spaziatura tra le lettere (letter-spacing) ridotta[cite: 10]. Per la menzione "413°" e i titoli principali, usare il peso "Display-LG" per creare il punto focale. Utilizzare gli stili in corsivo (italic) per citazioni o specifiche frasi latine della liturgia[cite: 10].

**Corpo del testo (Inter):** Scelto per la sua eccezionale leggibilità sui dispositivi mobili[cite: 10]. Usare il peso Medio (500) per i paragrafi introduttivi e il Regolare (400) per i testi storici lunghi[cite: 10].

**Etichette Maiuscole (Label-Caps):** Da utilizzare per i sovratitoli (testi piccoli sopra le intestazioni) per categorizzare i contenuti (es. "TRADIZIONE", "LITURGIA")[cite: 10].

## Layout e Spaziatura

Il layout segue una filosofia a **Griglia Fissa** su computer desktop (12 colonne, larghezza massima 1200px) per imitare la struttura ordinata di un manoscritto o di un programma formale[cite: 10].

*   **Ritmo:** Usa un'unità di base di 8px[cite: 10]. Tutti i margini e i riempimenti (padding) devono essere multipli di 8[cite: 10].
*   **Spazio Negativo:** Utilizzare una spaziatura verticale molto ampia (120px e oltre) tra le sezioni principali, per far "respirare" immagini e testo sottolineando la solennità dei contenuti[cite: 10].
*   **Adattabilità Mobile:** Sugli smartphone, i margini si riducono a 24px e la griglia collassa su una singola colonna[cite: 10]. Lo scorrimento orizzontale (swipe) è consentito per le linee del tempo storiche e per l'anteprima della galleria foto[cite: 10].

## Elevazione e Profondità

La percezione di "profondità" viene data attraverso la **Sovrapposizione di Tonalità** (Tonal Layering) e **Contorni Sottili**, evitando ombre pesanti e sgradevoli[cite: 10].

*   **Superfici:** Usare il colore Pergamena (#F4EBD0) per indicare i contenuti "in risalto" rispetto allo sfondo neutro Avorio (#FDFBF7)[cite: 10].
*   **Bordi:** Impiegare bordi molto sottili (1px) in Oro (#C5A059) o in un Blu Mariano a bassissima opacità (10%) per definire i contenitori e i riquadri[cite: 10].
*   **Ombre:** Quando è necessaria interattività (es. passaggio del mouse sopra una card), usare un'ombra "Ambientale" molto morbida: `0px 12px 32px rgba(0, 51, 102, 0.05)`[cite: 10]. Dà un senso di sollevamento leggero senza apparire "tecnologico"[cite: 10].
*   **Effetto Vetro (Glassmorphism):** Utilizzare una sfocatura leggera (8px) con un Bianco semi-trasparente (80%) per la barra di navigazione fissa, permettendo all'utente di intravedere cosa c'è dietro[cite: 10].

## Forme

Il linguaggio delle forme è conservatore e architettonico[cite: 10]. 

*   **Angoli:** Gli elementi dell'interfaccia usano angoli "Morbidi" (4px)[cite: 10]. Questo evita la durezza dei bordi affilati ma mantiene un aspetto formale, più strutturato rispetto agli angoli completamente arrotondati[cite: 10].
*   **Elementi Interattivi:** Anche i pulsanti e i campi di testo mantengono questo raggio di curvatura di 4px[cite: 10].
*   **Elementi Decorativi:** Si devono usare linee verticali per separare i contenuti, sormontate da un quadrato d'oro di 4px all'inizio o alla fine per simulare i tradizionali ornamenti tipografici[cite: 10].

## Componenti

*   **Hero Banners (Intestazioni a tutto schermo):** Usare fotografie ad alta risoluzione del "Simulacro" o della Basilica di Pedara a tutta larghezza[cite: 10]. Applicare un velo sfumato (da Blu Mariano a Trasparente) per garantire la leggibilità dei titoli in Playfair Display posizionati sopra la foto[cite: 10].
*   **Pulsanti (Buttons):** 
    *   *Principale:* Sfondo pieno in Blu Mariano, testo bianco con font Inter (Tutto Maiuscolo), angoli arrotondati di 4px[cite: 10]. 
    *   *Secondario:* Sfondo trasparente, bordo di 1px colore Oro, testo in Oro[cite: 10]. 
    *   *Effetto Passaggio Mouse (Hover):* Sostituire l'Oro con il Blu Mariano; aggiungere un impercettibile sollevamento verso l'alto di 2px[cite: 10].
*   **Card Storiche:** Sfondo Avorio con un bordo inferiore di 1px color Oro[cite: 10]. Devono utilizzare il font "Headline-SM" per i titoli[cite: 10].
*   **Linee del Tempo Verticali (Timelines):** Un asse centrale Oro di 2px[cite: 10]. Le pietre miliari storiche sono segnate da cerchietti Blu Mariano[cite: 10]. Usare lo sfondo Pergamena per l'intero componente, per segnalare visivamente all'utente il passaggio in un'epoca passata[cite: 10].
*   **Campi di Testo (Inputs):** Stile minimalista[cite: 10]. Nessuno sfondo (trasparente), solo un bordo inferiore di 1px Blu Mariano, accompagnato dalle etichette testuali in "Label-Caps" che galleggiano sopra la riga[cite: 10].
*   **Elenchi Liturgici:** Utilizzare piccole icone color Oro (croci o petali stilizzati) al posto dei classici "pallini neri" come punti elenco[cite: 10].