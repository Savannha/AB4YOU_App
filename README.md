# AB4YOU · Accesso allo SCADA

Prototipo interattivo del flusso di autenticazione allo SCADA dall'app AB4YOU (versione v6.2, 3 novembre 2026).

- **In presenza:** FAB SCADA (o menu → SCADA Authentication) → fotocamera → lettura del QR → password da scrivere a mano.
- **Da remoto:** "Sei da remoto? Incolla il codice" → copia di username e password, snackbar che sparisce dopo 3 s, "Incolla nuovo codice" con loader. Errori dell'incolla: niente da incollare, codice non valido (si sceglie dal pannello).
- **Errori della lettura:** QR non riconosciuto, impianto non autorizzato. L'esito si sceglie dal pannello accanto al telefono.

Un solo file, `index.html`, senza dipendenze da installare. Si pubblica così com'è su Netlify (nessun comando di build, cartella di pubblicazione: la radice).

Design di riferimento: file Figma "ABC-Shermate", pagina "4_WIP Inviti AB".
