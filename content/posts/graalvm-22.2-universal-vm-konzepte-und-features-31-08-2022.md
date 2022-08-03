---
title: "31.08.2022 GraalVM EE 22.2 Feature Update und Verbesserungen beim Native Image"
date: 2022-07-31T03:00:00+01:00
draft: false
featured_image: ""
description: "GraalVM EE 22.2 Feature Update und Verbesserungen beim Native Image"
---

**Die ist einen Präsenzveranstaltung bei Oracle, Details siehe Ablauf**

Die GraalVM ist eine universelle Virtuelle Maschine (VM) für Anwendungen, die in JavaScript, Python, Ruby, R oder mit den JVM-basierten Programmiersprachen Java, Scala, Kotlin, Clojure und LLVM-basierten Sprachen C/C++ geschrieben wurden. Im Juli 2022 wurde die GraalVM 22.2 freigegeben, mit Performance-Verbesserungen und polyglotter Unterstützung für verschiedene Programmiersprachen und sie ermöglicht damit die Interoperabilität in einer gemeinsamen Laufzeitumgebung. 

Die GraalVM JDK-Basisdistribution mit ihrer Größe der Laufzeitumgebung wurde verkleinert und damit die Download-Zeiten verringert. Mit der Version 22.2 ist die GraalVM-JDK-Basis modularer und enthält nicht mehr die JavaScript-Runtime, die LLVM-Runtime oder VisualVM. Diese Komponenten werden mit `gu install` separat installiert, beispielsweise mit `gu install visualvm`, genauso wie die Native Image-, Python-, Ruby- oder andere GraalVM-Komponenten installiert werden. 

Mit GraalVM Ahead-of-Time-Fähigkeit kompilierte Native Images verfügen über eine minimale Startup-Zeit und sie verringern den Memory-Verbrauch von JVM-basierten Applikationen. Durch die Optimierungen der internen Datenstrukturen benötigt das Native Image deutlich weniger Memory beim Build vom Native-Executable. Die GraalVM kann wahlweise als Open Source Community Edition (CE) oder als Enterprise Edition (EE) mit OTN Lizenz innerhalb der Java SE Subscription verwendet werden. 

Im Vortrag wird die GraalVM-Architektur im Java Eco System dargestellt und die Einsatzgebiete werden erläutert, beispielsweise der in Java entwickelte C2 JIT Compiler oder die Verwendung von GraalVM Native Images. GraalVM und OpenJDK können auch für Microservices-Frameworks verwendet werden.

_Wolfgang Weigend arbeitet als Master Principal Solution Engineer bei der ORACLE Global Services Germany GmbH im weltweiten Java Team. Er beschäftigt sich mit Java-Technologie, GraalVM und Architektur für unternehmensweite Anwendungsentwicklung._

## Ablauf 

_Bitte meldet euch bei [Nuudle](https://nuudel.digitalcourage.de/BbdVRCKZXuCy2AaD) an._

Es handelt sich um eine Präsenzveranstaltung bei

_ORACLE Deutschland B.V. & Co. KG  
Neue Mainzer Str. 46-50  
60311 Frankfurt am Main_

[Google Maps](https://goo.gl/maps/1BjunjfTts6seo1e6)

Die Besucher werden im Foyer vom Garden Tower von Wolfgang in Empfang genommen und dann gehen wir gemeinsam in kleinen Gruppen über das Treppenhaus in den zweiten Stock in den Raum _Redwood Shores_.