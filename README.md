<p align="center">
  <img src="https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/logo.png" width="96" height="96" alt="JF-Manager Logo">
</p>

<h1 align="center">JF-Manager – Open-Source-Software für die Jugendfeuerwehr</h1>

<p align="center">
  <strong>Mitgliederverwaltung, Dienstbuch, Anwesenheit, Ausbildungsplanung und Inventar in einer Web-App.</strong><br>
  Kostenlos, quelloffen (AGPL-3.0) und selbst gehostet, damit eure Daten bei euch bleiben.
</p>

<p align="center">
  <a href="https://github.com/Jugendfeuerwehr-Manager/JF-Manager"><strong>Zum Code-Repository</strong></a> ·
  <a href="https://github.com/Jugendfeuerwehr-Manager/JF-Manager/releases">Releases</a> ·
  <a href="https://jugendfeuerwehr-manager.github.io/JF-Manager/index.html">Benutzerhandbuch</a> ·
  <a href="https://github.com/Jugendfeuerwehr-Manager/JF-Manager/blob/main/CONTRIBUTING.md">Mitmachen</a>
</p>

---

**JF-Manager** ist eine Verwaltungssoftware für **Jugendfeuerwehren** und ihre Jugendwarte, Betreuerinnen und Betreuer. Sie bündelt alles, was im Alltag einer Jugendgruppe anfällt: **Mitglieder und Elternkontakte**, **Dienste und Anwesenheiten**, **Übungs- und Ausbildungsplanung**, **Qualifikationen**, **Kleiderkammer und Ausrüstung** sowie die **Kommunikation mit Eltern**. Statt Excel-Listen, Papier-Dienstbuch und verstreuten E-Mails habt ihr einen zentralen Ort, im Browser und auf dem Smartphone.

Die Software eignet sich auch für Feuerwehren mit mehreren Abteilungen, Kinderfeuerwehren, Jugendrotkreuz, THW-Jugend und andere Jugendorganisationen. Die Bezeichnungen der Module lassen sich anpassen.

![JF-Manager Dashboard mit nächsten Diensten, ablaufenden Qualifikationen, offenen Bestellungen und Schnellzugriff](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/dashboard.png)

## Key Features

| | Funktion | Das steckt drin |
| --- | --- | --- |
| 👥 | **Mitgliederverwaltung** | Stammdaten, Elternkontakte, Gruppen, Notizen, geschützte Anhänge und berechtigte Exporte |
| 📖 | **Digitales Dienstbuch** | Termine, Themen, Übungsleitung, Vorkommnisse und Anwesenheit für Teilnehmende und Team |
| 📊 | **Anwesenheitsauswertung** | Teilnahmequote, Stunden, Monatsverlauf und Hinweise auf Handlungsbedarf |
| 🗓️ | **Ausbildungs- und Übungsplanung** | Kalender, Bausteinbibliothek, Stationen mit Rotation, Serien, Vorlagen und Ressourcenwarnungen |
| 📱 | **Mobile Durchführung** | Stationsansicht für Ausbilder, Handouts mit Materialliste und Nachbereitung |
| 👨‍👩‍👧 | **Eltern- und Mitgliederportal** | Termine einsehen, an- und abmelden, Änderungen beantragen, Positionen und Warteliste |
| 🧰 | **Inventar und Kleiderkammer** | Artikel mit Varianten, Lager, Bestände, Ausleihen, Einkleidung und Bestellungen |
| 🎓 | **Qualifikationen** | Nachweise, Gültigkeiten, Ablaufwarnungen und Sonderaufgaben |
| ✉️ | **Kommunikation** | E-Mails mit Empfängerauswahl, Vorlagen und Versandhistorie, Push-Mitteilungen aufs Handy |
| 🔐 | **Rollen und Rechte** | Mehrere Abteilungen, 16 Standardrollen, Wirkungsvorschau, MFA, Passkeys, LDAP und OIDC-SSO |

## Screenshots

> Alle Screenshots stammen aus einer Demo-Installation mit ausschließlich fiktiven Daten.

### Übungen planen: Stationsausbildung mit Gruppenrotation

Baut einen Übungsabend aus Bausteinen zusammen, verteilt Stationen per Drag-and-drop auf die Gruppen und lasst euch Konflikte bei Zeit, Personal und Material anzeigen.

![Übungsplaner im JF-Manager: Stationsausbildung mit drei Gruppen, Rotation und Planungswarnungen](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/planner.png)

<details>
<summary>Animation: Bausteine per Drag-and-drop verschieben</summary>

![Animation: Übungsbausteine im Planer per Drag-and-drop verschieben](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/planner-drag.gif)

</details>

### Dienstbuch und Anwesenheit

Anwesenheit direkt im Dienst erfassen: anwesend, entschuldigt oder fehlend, mit einem Klick pro Person. Mehrere Betreuer können gleichzeitig erfassen, jede Eingabe wird sofort gespeichert.

![Digitales Dienstbuch: Anwesenheitserfassung für einen Dienst der Jugendfeuerwehr](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/attendance.png)

### Anwesenheitsauswertung

Teilnahmequote, Dienststunden und Monatsverlauf für Mitglieder und Team. Wer länger nicht da war, wird hervorgehoben.

![Anwesenheitsauswertung mit Teilnahmequote, Monatsverlauf und Mitgliederliste](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/report.png)

### An- und Abmeldungen für Dienste

Für Wachen, Ausflüge oder Zeltlager: Plätze und Positionen festlegen, Voraussetzungen wie Mindestalter prüfen, Warteliste und Mindestbesetzung im Blick behalten.

![Teilnahmeverwaltung mit Anmeldungen, Warteliste und Voraussetzungen](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/participation-registrations.png)

### Auf dem Smartphone: Elternportal und Übungsdurchführung

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/portal-home.png" alt="Elternportal auf dem Smartphone: nächste Dienste, An- und Abmeldung für Kinder">
      <p><strong>Elternportal:</strong> Eltern sehen die nächsten Dienste ihrer Kinder und melden sie selbst an oder ab.</p>
    </td>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/execution-mobile.png" alt="Mobile Übungsdurchführung: aktuelle Runde und Stationen auf dem Smartphone">
      <p><strong>Übung durchführen:</strong> Ausbilder sehen auf dem Handy die aktuelle Runde, ihre Station und welche Gruppe als Nächstes kommt.</p>
    </td>
  </tr>
</table>

Die Web-App lässt sich als App auf dem Startbildschirm installieren (PWA) und verschickt auf Wunsch Push-Mitteilungen.

### Rollen und Rechte mit Wirkungsvorschau

Rechte werden pro Abteilung vergeben. Vor dem Speichern zeigt JF-Manager, welche Rechte eine Person dazubekommt oder verliert.

![Rollen und Rechte: Zuweisung einer Rolle mit Vorschau der hinzukommenden Rechte](https://raw.githubusercontent.com/Jugendfeuerwehr-Manager/.github/main/profile/images/roles.png)

## Warum JF-Manager?

- **Für die Jugendfeuerwehr gemacht:** Dienstbuch, Stationsausbildung, Wachen, Kleiderkammer und Elternkontakte sind Kernfunktionen, keine Zusatzmodule.
- **Open Source:** Der gesamte Quellcode ist unter der [GNU AGPL-3.0](https://github.com/Jugendfeuerwehr-Manager/JF-Manager/blob/main/backend/LICENSE) frei verfügbar. Keine Lizenzkosten, kein Vendor-Lock-in.
- **Selbst gehostet und datenschutzfreundlich:** Ihr betreibt die Software auf eurem eigenen Server. Personenbezogene Daten von Kindern und Eltern verlassen nicht eure Infrastruktur.
- **Mehrere Abteilungen:** Eine Installation für mehrere Jugendfeuerwehren oder Ortsteile, mit Rechten je Abteilung.
- **Sicher:** Zwei-Faktor-Authentifizierung, Passkeys, Cookie-Sitzungen mit CSRF-Schutz und Rechteprüfung für jede Aktion.

## Benutzerhandbuch

Das bebilderte **[JF-Manager Benutzerhandbuch](https://jugendfeuerwehr-manager.github.io/JF-Manager/index.html)** erklärt Schritt für Schritt alle Funktionen, mit eigener Suche und Druckansicht:

- **Jugendleitung und Betreuer:** Mitglieder, Dienstbuch, Übungsplanung, Material und Kommunikation
- **Administratoren:** Organisation, Konten, Rollen, Einstellungen und Integrationen
- **Server und Betrieb:** Installation, Regelbetrieb, Sicherung und Notfälle

📘 [Zum Handbuch: jugendfeuerwehr-manager.github.io/JF-Manager](https://jugendfeuerwehr-manager.github.io/JF-Manager/index.html)

## Installation

JF-Manager läuft mit **Docker Compose** oder **nativ auf Debian 13** (auch im Proxmox-LXC). Ein Installationsassistent (`jfctl`) richtet alles ein, inklusive HTTPS, Backups und Updates.

👉 [Installationsanleitung](https://github.com/Jugendfeuerwehr-Manager/JF-Manager/blob/main/docs/operations/ops-install.md) · [Aktuelles Release herunterladen](https://github.com/Jugendfeuerwehr-Manager/JF-Manager/releases) · [Lokal mit Demo-Daten ausprobieren](https://github.com/Jugendfeuerwehr-Manager/JF-Manager#lokal-mit-fiktiven-daten-ausprobieren)

## Technik

| Bereich | Technologie |
| --- | --- |
| Backend | Python, Django 5.2, Django REST Framework |
| Frontend | Vue 3, TypeScript, Pinia, PrimeVue |
| Datenbank | PostgreSQL 17, Redis |
| Betrieb | Docker Compose oder Debian 13, Caddy für HTTPS |
| Anmeldung | MFA, Passkeys, LDAP, OpenID Connect (SSO) |

## Mitmachen

JF-Manager ist ein Gemeinschaftsprojekt. Jede Hilfe ist willkommen: Fehler melden, Ideen einbringen, Dokumentation verbessern oder Code beitragen.

- ⭐ Gebt dem [Repository](https://github.com/Jugendfeuerwehr-Manager/JF-Manager) einen Stern, damit mehr Jugendfeuerwehren das Projekt finden.
- 🐛 [Fehler melden oder Funktion vorschlagen](https://github.com/Jugendfeuerwehr-Manager/JF-Manager/issues)
- 🛠️ [Beitragsrichtlinien lesen](https://github.com/Jugendfeuerwehr-Manager/JF-Manager/blob/main/CONTRIBUTING.md)

<p align="center">
  <a href="https://github.com/Jugendfeuerwehr-Manager/JF-Manager"><strong>→ github.com/Jugendfeuerwehr-Manager/JF-Manager</strong></a>
</p>

<sub>Stichworte: Jugendfeuerwehr Software, Jugendfeuerwehr Verwaltung, Mitgliederverwaltung Feuerwehr, digitales Dienstbuch, Anwesenheitsliste Jugendfeuerwehr, Ausbildungsplanung Feuerwehr, Übungsplanung, Kleiderkammer Verwaltung, Elternportal, Open Source Feuerwehr Software, Jugendwart Tool, Kinderfeuerwehr</sub>
