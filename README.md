# PrintStudio - distribuzione binaria

Repository pubblico dei pacchetti compilati. I sorgenti sono conservati separatamente.

Versione corrente: **0.3.11** (Windows 64 bit).

Scarica [PrintStudioSetup.exe](https://github.com/CARLOBINI/PrintStudioBinaries/releases/download/setup-v0.3.11.0/PrintStudioSetup.exe), eseguilo e scegli la versione da installare. Non servono Git, Qt o Visual Studio sul computer destinatario.

Il setup scarica i componenti completi, crea i collegamenti e conserva separati impostazioni, report e driver installati. Permette di scegliere anche versioni precedenti consentite. PrintStudio usa lo stesso catalogo dal menu File > Verifica aggiornamenti.

Il servizio di verifica del supporto non e ancora collegato: e predisposta l importazione di autorizzazioni firmate. Il catalogo e i pacchetti sono verificati tramite firma RSA e checksum SHA-256. La firma del catalogo non e una firma Authenticode dell eseguibile Windows.

Le release sono pubbliche: il controllo della licenza nel setup non impedisce il download manuale degli allegati GitHub.

Versioni e metadati: cartella versions. Le release precedenti restano disponibili.

Setup aggiornato: **0.3.11.0**. Versione applicativa invariata.
