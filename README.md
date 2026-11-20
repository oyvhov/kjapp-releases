# Kjapp – Android-utgåver

Kjapp hjelper trenarar med å planleggje og gjennomføre treningsøkter for barn og ungdom.

[**Last ned Kjapp for Android**](https://github.com/oyvhov/kjapp-releases/releases/latest/download/kjapp.apk) · [Sjå alle utgåver](https://github.com/oyvhov/kjapp-releases/releases)

Last ned APK-fila på telefonen og opne henne for å installere. Installer nye utgåver oppå den eksisterande Kjapp-appen; då blir lokale økter, utstyr og innstillingar bevarte. Ikkje avinstaller først.

Frå versjon 23 kan Kjapp hente oppdateringar her direkte frå **Innst. → Oppdateringar**. Har du versjon 22 eller eldre, installer den nye APK-fila manuelt éin gong for å byte oppdateringskanal. Ingen GitHub-konto er nødvendig.

Dette repoet inneheld berre ferdige Android-utgåver og offentleg bygginformasjon. Kjeldekoden er privat. Utvikling, bygging og signering skjer lokalt. Appen lagrar treningsdata på eininga; ingen treningsdata blir publiserte her.

## Kontroll av utgåver

Kvar stabil utgåve har heiltalstaggen `vN` og desse vedlegga:

- `kjapp.apk` – signert produksjonsbygg for Android med arm64-v8a.
- `SHA256SUMS` – kontrollsum for APK-fila.
- `SOURCE_COMMIT` – identifikator for kjeldecommit.
- `verification.json` – pakkenamn, versjon, filstorleik, kontrollsum og offentleg sertifikatfingeravtrykk.

Pakkenamn: `no.kjapp.trening`.

Alle Kjapp-oppdateringar bruker det eksisterande signeringssertifikatet (SHA-256):

```
81:FE:D4:1A:9A:FC:E2:F1:0F:4E:71:47:3F:2D:29:A3:D3:23:45:B1:86:D8:13:F0:F8:EA:01:AC:84:5C:EC:A6
```