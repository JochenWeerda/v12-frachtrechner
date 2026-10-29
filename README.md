# V12 Greenline Frachtrechner

Eigenständige mobile Web-App zur Kalkulation von V12 Greenline 100 µm und zum Kopieren oder Teilen von Angeboten über WhatsApp. Kein App Store und kein Build-Schritt nötig.

## Nutzung

`index.html` im Browser öffnen oder die veröffentlichte GitHub-Pages-Seite verwenden. Rollendaten, Preis und Rabatt einstellen; anschließend „Text kopieren“ oder „Über WhatsApp teilen“ wählen. Auf dem Handy lässt sich die Seite über das Browsermenü zum Startbildschirm hinzufügen. Ein Offline-Modus ist nicht eingerichtet.

## GitHub Pages

Unter **Settings → Pages → Build and deployment → Source** die Option **GitHub Actions** auswählen. Der Workflow `.github/workflows/pages.yml` veröffentlicht die App bei Änderungen auf `main` und kann unter Actions manuell gestartet werden.

## Herkunft

Die Datei `index.html` wurde unverändert aus [JochenWeerda/VALEO-NeuroERP-3.0](https://github.com/JochenWeerda/VALEO-NeuroERP-3.0/blob/main/tools/v12-frachtrechner/index.html) übernommen. Quell-Blob: `18eded6077b191fd49a6974517d022573bb604bb`.

## Kalkulationshinweise

Alle Preise netto. Die enthaltene Frachtstaffel gilt für PLZ 26. Gewicht, Fracht und Verfügbarkeit sind Richtwerte und bedürfen der Bestätigung; Paletten, Überlängen und Sperrgut können Zuschläge auslösen. Tarife und Angebotsbedingungen vor dem produktiven Einsatz prüfen.

