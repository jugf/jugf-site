---
title: "29.06.2022 Automatisierte Architekturtests und statische Codeanalyse mit ArchUnit"
date: 2022-05-22T03:00:00+01:00
draft: false
featured_image: ""
description: "Automatisierte Architekturtests und statische Codeanalyse mit ArchUnit"
---

Im Architektur-Entwurf treffen wir viele Architekturentscheidungen, im besten Fall explizit, dokumentiert und verstanden. Dieser Prozess ist aufwändig und mühsam, mit der Folge, dass viele Entscheidungen meist nur implizit getroffen werden und dann in Vergessenheit geraten.Eine automatisierte Überprüfung solcher Architekturentscheidungen hilft hier weiter:

Manche Entscheidungen wie Namenskonventionen lassen sich schon lange über altbekannte Tools wie Checkstyle leicht abtesten. Komplexere Entscheidungen aber lassen sich nicht immer einfach checken - oder sie erfordern ein komplexes Metamodell, das aufwändig zu erstellen und zu pflegen ist.Hier kommt ArchUnit ins Spiel.

In unserem Talk stellen wir anhand konkreter Fragestellungen vor, wie man mit ArchUnit automatisiert Architekturentscheidungenin einen Standard-Testzyklus einbinden kann. Dazu bringt ArchUnit von Haus aus eine ganze Reihe von Standard-Hilfsmitteln mit. Besser noch:
Eigene Architekturregeln lassen sich leicht in Form von Tests definieren und so im automatisiertem Build überprüfen. Beispiele: - Sind Abhängigkeiten zwischen Komponenten richtig definiert?- Sind Strukturen innerhalb einer Komponente richtig modelliert, z.B. als Onion-Architektur?
Dieselbe API von ArchUnit kann man aber auch für statische Codeanalyse einsetzen, dessen Output nicht in einem Test, sondern als Input in weitere Tools eingeht. Damit lassen sich einfach kleine Helferlein schreiben, um gezielt Handlungsbedarfe identifizieren und analysieren zu können. Beispiel: In einem System werden Daten versioniert zwischen Services ausgetauscht. Finde alle Services, die direkt oder transitiv von inkompatiblen Änderungen an diesem Datenmodell betroffen und daher anzupassen sind.

ArchUnit lässt sich demnach für kleine, mittlere und komplexe Fragestellungen einsetzen. Das skaliert gut und ermöglicht eine leichtgewichtige und automatisierte Absicherung von Architekturentscheidungen.

_Martin Lehmann, Kristine Schaal_

## Ablauf 

_Bitte meldet euch bei [Nuudle]() an._

Dies ist eine Präsenzveranstaltung bei Accso: Rahmhofstraße 2 (2 Fussminuten von der Hauptwache, bei der Börse), siehe https://accso.de/kontakt/#unsere-standorte

Wir wollen die Möglichkeit haben, alle Anwesenden zu kontaktieren, deshalb meldet euch bitte direkt an, damit keine Erfassung vor Ort notwendig ist.

### Corona-Regelungen

* Maximal 30 Personen
* Keine gesetzliche Verpflichtung zur 3G-Regel
* Keine Maskenpflicht, aber Empfehlung zum Tragen einer Maske

### Verpflegung

Accso stellt Getränke und Snacks (Finger-Food), deshalb nutzt bitte die Anmeldung, damit die Menge abgeschätzt werden kann.