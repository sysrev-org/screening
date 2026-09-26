# Pagina di screening

Pagina web per lo screening (titolo e abstract, full text) e per l'estrazione dei dati delle
systematic review di `sysrev-org`.

**Indirizzo**: `https://sysrev-org.github.io/screening/?repo=sysrev-org/NOME-DELLA-REVIEW`
(chi coordina manda il link completo ai revisori).

## Cosa contiene

Solo la pagina (`index.html`): **nessun dato**. Record, decisioni e protocolli restano nei repository
privati delle review. La pagina li legge e li scrive direttamente dal browser, con il token GitHub di
chi la usa: il token resta nel browser e viene inviato soltanto a `api.github.com`.

Le istruzioni per i revisori sono nel file `guida-revisori.md` del repository di ciascuna review.

## Aggiornamenti

Questo repository viene aggiornato automaticamente dal repository del motore `sysrev`
(cartella `web/screening/`): non modificare i file qui, le modifiche verrebbero sovrascritte.
