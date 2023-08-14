- **Klare und spezifische Aufforderungen:** Entwerfen Sie klare und spezifische Aufforderungen, die den notwendigen Kontext für die mathematische Aufgabe liefern. Geben Sie den Problemtyp, das erwartete Eingabeformat und das gewünschte Ausgabeformat an. Vermeiden Sie zweideutige oder vage Anweisungen, die den LM verwirren könnten.

- **Formatierungshinweise:** Fügen Sie Formatierungshinweise in die Aufforderungen ein, um den LM anzuleiten, wie er mathematische Ausdrücke interpretieren und generieren soll. Verwenden Sie zum Beispiel LaTeX-Formatierung oder explizite Notationen für mathematische Symbole, Gleichungen oder Variablen. (https://de.wikipedia.org/wiki/Liste_mathematischer_Symbole)

- **Beispielbasierte Aufforderungen:** Geben Sie beispielbasierte Aufforderungen, die das gewünschte Eingabe-Ausgabe-Verhalten demonstrieren. Zeigen Sie dem Modell korrekte Lösungen für verschiedene Problemtypen, damit es die erwarteten Muster und Formate versteht.

- **Schritt-für-Schritt-Anweisungen (CoT):** Zerlegen Sie komplexe mathematische Probleme in Schritt-für-Schritt-Anweisungen. Geben Sie explizite Anweisungen, wie das Modell das Problem angehen soll, z. B. die Definition von Variablen, die Anwendung bestimmter Regeln oder Formeln oder die Befolgung einer bestimmten Abfolge von Operationen.

- **Fehlerbehandlung:** Antizipieren Sie potenzielle Fehler oder Missverständnisse, die dem LM unterlaufen könnten, und weisen Sie es ausdrücklich an, wie es mit solchen Fällen umgehen soll. Geben Sie Hinweise zu häufigen Fehlern und bieten Sie korrigierendes Feedback, damit das Modell aus seinen Fehlern lernt.

- **Feedback-Schleife:** Bewerten Sie kontinuierlich die Antworten des Modells und überarbeiten Sie die Eingabeaufforderungen auf der Grundlage des Benutzerfeedbacks. Identifizieren Sie Bereiche, in denen das LM immer wieder Fehler macht oder Schwierigkeiten hat, und ändern Sie die Aufforderungen, um diese spezifischen Herausforderungen anzugehen.

- **Einfügen von Kontext:** Fügen Sie der Aufforderung zusätzlichen Kontext hinzu, um dem Modell zu helfen, das Problem besser zu verstehen. Dies kann relevante Hintergrundinformationen, spezifische Problemeinschränkungen oder Hinweise beinhalten, die den LM zur richtigen Lösung führen.

- **Progressive Offenlegung (LtM):** Geben Sie dem LM nach und nach Informationen oder Teilaufgaben preis, anstatt das gesamte Problem auf einmal zu lösen. Dies kann dem Modell helfen, sich auf kleinere Teilprobleme zu konzentrieren und die kognitive Belastung zu verringern, was zu zuverlässigeren Ergebnissen führt.

- **Unbedenklichkeitsprüfungen:** Fügen Sie in die Eingabeaufforderung Unbedenklichkeitsprüfungen ein, um die Angemessenheit der Ausgabe des Modells zu überprüfen. Sie können das Modell zum Beispiel auffordern, Zwischenschritte anzuzeigen oder die Lösung anhand bekannter mathematischer Eigenschaften zu überprüfen.

- **Feinabstimmung und Experimentieren:** Führen Sie eine Feinabstimmung des LLM anhand eines Datensatzes durch, der speziell auf mathematische Aufgaben ausgerichtet ist. Experimentieren Sie mit verschiedenen Prompt-Engineering-Techniken und bewerten Sie die Auswirkungen auf die Zuverlässigkeit des Modells. Iterieren Sie den Feinabstimmungsprozess auf der Grundlage der erzielten Ergebnisse.