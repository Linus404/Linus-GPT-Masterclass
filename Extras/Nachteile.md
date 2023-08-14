# Pitfalls of LLMs

**Falsche Interpretation**
- Es kann vorkommen, dass LLMs die Absicht Ihrer Aufforderung nicht ganz verstehen und allgemeine oder sichere Antworten geben. Um dies abzuschwächen, sollten Sie Ihre Aufforderungen expliziter formulieren oder das Modell bitten, Schritt für Schritt zu denken, bevor es eine endgültige Antwort gibt.

**Empfindlichkeit gegenüber Aufforderungsformulierungen**
- LLMs können empfindlich auf die Formulierung Ihrer Aufforderungen reagieren, was zu völlig unterschiedlichen oder widersprüchlichen Antworten führen kann. Stellen Sie sicher, dass Ihre Aufforderungen gut formuliert und klar sind, um Verwirrung zu vermeiden.

**Plausible aber falsche Antworten**
- In einigen Fällen können LLMs Antworten generieren, die plausibel klingen, aber in Wirklichkeit falsch sind. Eine Möglichkeit, damit umzugehen, besteht darin, einen Schritt hinzuzufügen, mit dem das Modell die Richtigkeit seiner Antwort überprüfen kann, oder das Modell aufzufordern, Beweise oder eine Quelle für die gegebenen Informationen anzugeben.

**Wortreiche oder übermäßig technische Antworten**
- LLMs, insbesondere größere, können Antworten erzeugen, die unnötig langatmig oder zu technisch sind. Um dies zu vermeiden, sollten Sie das Modell ausdrücklich anleiten, indem Sie Ihre Aufforderung spezifischer formulieren, um eine einfachere Antwort bitten oder ein bestimmtes Format vorgeben.

**LLMs fragen nicht nach einer Erklärung**
- Wenn sie mit einer mehrdeutigen Aufforderung konfrontiert werden, könnten die LLMs versuchen, sie zu beantworten, ohne nach einer Klärung zu fragen. Um das Modell zu ermutigen, sich um eine Klärung zu bemühen, können Sie Ihrer Aufforderung den Satz voranstellen: "Wenn die Frage unklar ist, bitten Sie um Klärung".
- Lösung: **Clarification questions** = true

**Modellversagen bei der Durchführung mehrteiliger Aufgaben**
- Es kann vorkommen, dass LLMs nicht alle Teile einer mehrteiligen Aufgabe erledigen oder sich nur auf einen Aspekt der Aufgabe konzentrieren. Um dies zu vermeiden, sollten Sie die Aufgabe in kleinere, besser zu bewältigende Teilaufgaben aufteilen oder sicherstellen, dass jeder Teil der Aufgabe in der Aufforderung klar gekennzeichnet ist.

**Vorurteile (Bias)**
- LLMs sind oft geneigt, stereotype Antworten zu geben. Selbst mit Sicherheitsvorkehrungen werden sie manchmal sexistische/rassistische/homophobe Dinge sagen. Seien Sie vorsichtig, wenn Sie LLMs in verbraucherorientierten Anwendungen verwenden, und seien Sie auch vorsichtig, wenn Sie sie in der Forschung einsetzen (sie können verzerrte Ergebnisse liefern).