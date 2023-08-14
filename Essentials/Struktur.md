## Strukturarten & Präzessionen:
**Textart**
- z.B. Essay, Kommentar oder Gedichtinterpretation

**Zielgruppe**
- Anrede
- Textverständnis

**Schreibstil**
- Genauer beschreibende Adjektive
	- z.B. umgangssprachlich, locker, dramatisch, wütend, sarkastisch, vulgär, diplomatisch...
- Vermeidungen und andere besondere Angaben
	- z.B. *Vermeide passive Verbformen und Nominalstil*, *Verwende einfache Sätze ohne viele Nebensätze* oder *Nutze eine Metapher in der Einleitung* 
- Schreibstil von jemandem / etwas übernehmen
	- z.B. Schreibstil: Donald Trump

**Struktur und Aufbau**
- Gliederung 
	- z.B. Einleitung, Hauptteil, Fazit
- Framework
	- z.B. PAS oder AIDA
- Zwischenüberschriften
	- z.B. alle 200 Wörter
- Länge
	- z.B. verwende ungefähr 300 Wörter

**Ziel**
- z.B. Leser zum Kauf anregen, neugierig machen oder Leser unterhalten...

**Beispiel**
- z.B. *Das ist eine Produktbeschreibung für XYZ: (...)  Schreibe eine Produktbeschreibung für ABC. Benutze die obenstehende Produktbeschreibung als Referenz. Formuliere den Text einzigartig und kopiere nicht 1:1 den Aufbau der obenstehenden Beschreibung.*

**Formatierung**
- Tabelle
	- Spalten:
	- Zeilen:
- Liste
- CSV, JSON, etc.

## Fortgeschrittene Techniken
**Tree of Thought / Chain of Thought (CoT)**
- Definieren Sie zunächst eine klare Ausgangsfrage oder ein Problem, das als Ausgangspunkt für die Kette dienen soll.
- Entwerfen Sie eine Aufforderung, die das Modell nicht nur auffordert, eine Antwort auf die Ausgangsfrage zu geben, sondern es auch auffordert, seine Argumentation Schritt für Schritt zu erklären.
- Ermutigen Sie das Modell, Zwischenschritte, mögliche Alternativen oder Verbindungen zwischen Ideen in seiner Antwort ausdrücklich zu berücksichtigen.

**Zero Shot, One Shot und Few Shot Prompting**
- **Anzahl der Beispiele:** Ein "few-shot"-Setting umfasst in der Regel 2-10 Beispiele (kann aber variieren), je nach Klarheit und Komplexität der Aufgabe.
- **Kontext und Relevanz:** Die Beispiele sollten für die gewünschte Aufgabe relevant sein und eine angemessene Grundlage für die Gestaltung des Modelloutputs bieten.
- **Ausgewogenheit:** Streben Sie ein Gleichgewicht zwischen zu wenigen Beispielen (Unterspezifizierung) und zu vielen Beispielen (Wiederholung und Überspezifizierung) an.

**Least to Most Prompting**
- Das Least to Most Prompting geht einen Schritt weiter als das Chain of Thought (CoT) Prompting, indem ein Problem zunächst in Teilprobleme zerlegt und dann jedes einzelne gelöst wird.
- Wie beim CoT Prompting wird das zu lösende Problem in eine Reihe von Teilproblemen zerlegt, die aufeinander aufbauen. In einem zweiten Schritt werden diese Teilprobleme eines nach dem anderen gelöst. Im Gegensatz zur chain of thought, wird die Lösung der vorherigen Teilprobleme in den Prompt eingespeist, mit dem versucht wird, das nächste Problem zu lösen.
- Erwähnen Sie z.B.: *Welche Teilprobleme müssen vor der Beantwortung der Frage / Aufgabe gelöst werden?*
	- Danach: *Gehe Schritt für Schritt.*

**Dual Prompt Approach**
- Beim Dual Prompting geben Sie mehrere Anweisung, welche aufeinander basieren.
- Beispiel: *I am writing a guide about SEO. Give me 10 key topics that I should cover in this guide.*
	- Danach: *Write me a detailed guide about each of the points you gave above.*
- Auch machbar in einem Prompt: *I am writing a guide about SEO. Take the 10 key topics about SEO and write a detailed introduction to each.*