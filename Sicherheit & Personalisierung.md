Sicherheit mit Gruppenrichtlinien:
Biometrische Authentifizierung mit Windows Hello:

Erstelle eine GPO, um Windows Hello (biometrische Authentifizierung) zu aktivieren.
Gehe zu Computerkonfiguration > Administrative Vorlagen > Windows-Komponenten > Windows Hello für Business.
Aktiviere die Richtlinie „Windows Hello für Business aktivieren“.
Logon-Rechte administrieren:

Erstelle eine GPO, um Benutzerrechte für die Anmeldung zu verwalten.
Navigiere zu Computerkonfiguration > Windows-Einstellungen > Sicherheitseinstellungen > Lokale Richtlinien > Zuweisen von Benutzerrechten.
Wähle die Richtlinie „Anmelden als Dienst verweigern“ und füge Benutzer oder Gruppen hinzu, die sich nicht lokal anmelden dürfen.
Windows Defender Antivirus:

Erstelle eine GPO, um Microsoft Defender Antivirus zu aktivieren oder deaktivieren.
Gehe zu Computerkonfiguration > Administrative Vorlagen > Windows-Komponenten > Windows Defender Antivirus.
Setze „Microsoft Defender Antivirus deaktivieren“ auf „Aktiviert“, um es zu deaktivieren.
Benutzerkontensteuerung (User Account Control) deaktivieren und anpassen:

Gehe zu Computerkonfiguration > Administrative Vorlagen > Windows-Komponenten > Benutzerschnittstelle für Anmeldeinformation.
Deaktiviere „Benutzerschnittstelle für Anmeldeinformation: Bei Ausführung mit erhöhten Rechten Administratorkonten deaktivieren“.
Systemprozess Svchost.exe überwachen:

Erstelle eine GPO, um den Schutz von Svchost.exe sicherzustellen.
Navigiere zu Computerkonfiguration > Windows-Einstellungen > Sicherheitseinstellungen > Erweiterte > Überwachungsrichtlinien > Detaillierte Überwachung
Aktiviere 2 Prozessüberwachung-Richtlinien und stelle sicher, dass der Svchost-Prozess überwacht wird.
Konten:

Verwende Gruppenrichtlinien, um Konten zu verwalten (z.B. Kontosperrung, Passwortkomplexität).
Gehe zu Computerkonfiguration > Windows-Einstellungen > Sicherheitseinstellungen > Kontorichtlinien > Passwortrichtlinien.
Setze eine komplexe Passwortanforderung und eine Mindestpasswortlänge.

Programme mit Applocker sperren:

Erstelle eine GPO zur Konfiguration von Applocker.
Gehe zu Computerkonfiguration > Windows-Einstellungen > Sicherheitseinstellungen > Applocker.
Erstelle Regeln, um unerwünschte Anwendungen zu blockieren (z.B. exe-Dateien).
Arbeitsstationen mit DeviceGuard schützen:

Gehe zu Computerkonfiguration > Administrative Vorlagen > Windows-Komponenten > Device Guard.
Aktiviere „Device Guard aktivieren“, um die Sicherheitsrichtlinie zu implementieren.
Credential Guard verwalten:

Gehe zu Computerkonfiguration > Administrative Vorlagen > Windows-Komponenten > Microsoft Defender Antivirus > Exploit Guard > Netzwerkschutz.
Aktiviere „Benutzer- und App-Zugriff“ für die zusätzliche Sicherheit bei der Verwaltung von Anmeldedaten.
