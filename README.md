# NAS Connect

Menüleisten-App für macOS, die die Freigaben eines Synology-NAS automatisch verbindet – zu Hause über das Heimnetz, unterwegs über Tailscale oder WebDAV.

Dieses Repository enthält nur die fertigen Versionen zum Herunterladen, keinen Quellcode.

## Installieren

1. Unter [Releases](../../releases/latest) die Datei `NAS-Connect.pkg` laden und doppelklicken.
2. Meldet macOS, dass das Paket nicht geprüft werden kann: *Systemeinstellungen → Datenschutz & Sicherheit → Dennoch öffnen*.
3. Im Installer „Installieren“ wählen. Die App startet danach von selbst, ein Assistent hilft beim Einrichten.

Benötigt macOS 13 (Ventura) oder neuer, Intel oder Apple Silicon.

## Updates

Installierte Apps suchen einmal am Tag nach einer neuen Version und bieten sie in der Menüleiste zum Installieren an. Grundlage ist die Datei `update.json` im jeweils neuesten Release.
