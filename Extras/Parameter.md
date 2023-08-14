Sie müssen im Prompt erwähnen, dass ChatGPT die Parameter nutzen soll. Das machen Sie entweder indirekt (z.B. "*Bitte erzeuge eine Antwort mit einer niedrigeren Temperatur für eine gezieltere Ausgabe.*") oder direkt (z.B. *Aufgabe: Erkläre mir die Anwendungen von KI unter Berücksichtigung folgender Parameter:
 -Temperature: 1.0 
 -Top-p : 0.8*).

1. **Temperature:** Niedrigere Temperaturen (z. B. 0,2) erzeugen nicht nur konzentrierte und konservative Ausgaben, sondern erhöhen auch die Wahrscheinlichkeit, dass das Modell häufig verwendete Phrasen oder vorhersehbare Antworten generiert. Höhere Temperaturen (z. B. 1,0 oder höher) können tatsächlich zu kreativeren und weniger vorhersehbaren Ausgaben führen. (0,0 - unendlich)

2. **Top-p (nucleus) sampling:** Legt einen Schwellenwert für die kumulative Wahrscheinlichkeitsverteilung fest, der die Vielfalt des generierten Textes bestimmt. Niedrigere Werte (z. B. 0,8) machen die Ausgabe konzentrierter, während höhere Werte (z. B. 0,9) die Zufälligkeit erhöhen. (0,0 - 1,0)

3. **Max tokens:** Dieser Parameter begrenzt die maximale Länge der generierten Antwort, aber es ist wichtig zu beachten, dass zu niedrige Werte die Antwort möglicherweise abschneiden und sie unvollständig machen können. Es ist empfehlenswert, eine ausreichend große Anzahl von Tokens zuzulassen, um sicherzustellen, dass die Antwort vollständig ist. (ganze Zahl)

4. **Presence penalty:** Steuert die Abneigung gegen die Wiederholung desselben Wortes oder Satzes. Höhere Werte (z. B. 0,6) verringern die Wiederholung der Ausgabe, während niedrigere Werte (z. B. 0,2) die Wahrscheinlichkeit der Wortwiederholung erhöhen. (0,0 - 1,0)

5. **Frequency penalty:** Passt die Strafe für die Verwendung seltener Wörter oder Token im generierten Text an. Höhere Werte (z. B. 0,6) ermutigen das Modell, häufigere Wörter zu verwenden, während niedrigere Werte (z. B. 0,2) eine größere Vielfalt und die Einbeziehung seltener Wörter ermöglichen. (0,0 - 1,0)

6. **Best of:** Gibt die Anzahl der alternativen Vervollständigungen an, die bei der Generierung der Antwort berücksichtigt werden sollen. Sie können diesen Wert auf eine ganze Zahl setzen (z. B. 1), um nur die bestplatzierte Vervollständigung zu berücksichtigen, oder ihn für vielfältigere Antworten erhöhen. (ganze Zahl)

7. **Max time:** Legt ein maximales Zeitlimit für die Erstellung einer Antwort durch das Modell fest. Dies ist hilfreich, um langwierige Vervollständigungen zu verhindern und eine Zeit Beschränkung zu erzwingen. (ganze Zahl in ms)

8. **Timeout penalty:** Passt die Strafe für das Überschreiten der maximalen Zeitgrenze an. Höhere Werte (z. B. 0,6) ermutigen das Modell, schnell fertig zu werden, was möglicherweise zu Lasten der Vollständigkeit geht, während niedrigere Werte (z. B. 0,2) der Erzeugung einer umfassenderen Antwort Vorrang einräumen. (0,0 - 1,0)

9. **Return Prompt**: Legt fest, ob die ursprüngliche Aufforderung in die Antwort aufgenommen werden soll. Die Einstellung `false` kann zu einer saubereren Ausgabe führen, ohne die Eingabe zu wiederholen. (bool)

**GPT-4 only:**

10. **N-Gramm-Blocking:** Definiert eine Liste von n-Grammen oder Phrasen, die im generierten Text nicht vorkommen sollen. Das Modell wird angewiesen, keine der angegebenen N-Gramme zu erzeugen, was nützlich sein kann, um bestimmte Phrasen oder Inhalte zu verhindern.

11. **Contextual filtering:** Ermöglicht das Filtern oder Ändern der Ausgabe des Modells auf der Grundlage eines bestimmten Kontexts oder bestimmter Bedingungen. Dieser Parameter ermöglicht eine bedingte Generierung, bei der die Reaktion des Modells von bestimmten Kriterien oder Anforderungen geleitet werden kann.

12. **Tuning weight:** Stellt das Gleichgewicht zwischen der eigenen Kreativität des Modells und der Befolgung der vorgegebenen Aufforderung ein. Höhere Werte (z. B. 0,8) geben der Aufforderung den Vorrang und sorgen dafür, dass sich das Modell stärker an sie hält, während niedrigere Werte (z. B. 0,2) dem Modell mehr kreative Freiheit lassen.