XA3 MOBILE · CLONE FEDELE DEL PORTALE (15 NOV 2026)

La base è il file index(20261115-113106).html del portale, senza sostituire la sua grafica o il suo motore delle sfere.

Interfaccia: solo SFERE XRPL e AREA XA3. L'area XA3 conserva jar/saldo, grafico GeckoTerminal, account Xaman.
Il codice delle altre aree rimane nel bundle come dipendenza originale; le pagine sono nascoste. Questo non è ancora un estratto indipendente e completamente ottimizzato.

Connessione Xaman: usa ESATTAMENTE l'SDK originale (xaman.app/assets/cdn/xumm.min.js) e la chiave API pubblica già presente nel portale. Non sono memorizzate seed né chiavi private. Il dominio HTTPS dove viene pubblicata l'app può dover essere registrato/consentito nella dashboard Xaman. La presenza del codice NON garantisce l'esito OAuth; testare su Android e iOS.

INSTALLAZIONE: pubblicare il contenuto della cartella su HTTPS. Android: Chrome > Installa app. iOS: Safari > Condividi > Aggiungi alla schermata Home.

NOTA: i dati XRPL e GeckoTerminal richiedono internet. La PWA non è un pacchetto Android APK o iOS IPA. Non testata con account Xaman reale né su dispositivi reali.
