Informieren Sie sich für diese Aufgabe zuerst, was Single Page Anwendungen sind, wo die
Vor-/Nachteile liegen und leiten Sie ab, wann es sinnvoll ist eine solche Webseite zu erstellen?

Single page Anwendung (SPA) ist eine Webanwendung oder eine Website, die mit dem Benutzer interagiert,
indem sie die aktuelle Seite dynamisch neu schreibt, anstatt ganze neue Seiten von einem Server zu laden.

Vorteile: 
+SPA ist schnell, da die meisten Ressourcen (HTML + CSS + Skripte) nur einmal während der gesamten Lebensdauer der Anwendung geladen werden.
Nur Daten werden hin und her übertragen.
+Die Entwicklung ist einfach. (Es ist nicht erforderlich, Code zum Rendern von Seiten auf dem Server zu schreiben.)
+Es ist einfacher, eine mobile Anwendung zu erstellen, da der Entwickler denselben Back-End-Code für die Webanwendung
und die native mobile Anwendung wiederverwenden kann.
+SPA kann jeden lokalen Speicher effektiv zwischenspeichern. Eine Anwendung sendet nur eine Anfrage,
speichert alle Daten, dann kann sie diese Daten verwenden und funktioniert sogar offline.
+bessere Benutzererfahrung.

Nachteile: 
-Der Download ist langsam, da umfangreiche Client-Frameworks auf den Client geladen werden müssen.
-Es erfordert, dass JavaScript vorhanden und aktiviert ist. Wenn ein Benutzer JavaScript in seinem Browser deaktiviert, 
ist es nicht möglich, die Anwendung und ihre Aktionen korrekt darzustellen.
-Im Vergleich zur "traditionellen" Anwendung ist SPA weniger sicher.
-"Memory leak" in JavaScript kann sogar dazu führen, dass ein leistungsstarkes System langsamer wird
-Die Navigation ist auch besser auf Multi-Pagern

Wann ist SPA keine gute Idee:
SPAs eignen sich nicht gut für Foren, Blogs, Nachrichtenseiten, öffentliche Inhaltszusammenstellungs - / - kurationsdienste -> 
Es wird nicht erwartet, dass Benutzer die Website durchsuchen, nachdem sie auf die von ihnen angeforderten Inhalte zugegriffen haben.