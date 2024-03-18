# CSS-Struktur

CSS: Eine Einführung für Neueinsteiger

CSS (Cascading Style Sheets) ist eine Stylesheet-Sprache, die verwendet wird, um das Aussehen und die Formatierung von HTML-Elementen auf einer Webseite zu definieren. In dieser README.md werden wir uns detailliert mit CSS befassen und erklären, wie es für die Gestaltung von Webseiten genutzt wird.
Was ist CSS?

CSS ist eine Sprache, die die Präsentation eines HTML-Dokuments beschreibt. Mit CSS können verschiedene Aspekte eines HTML-Elements gestaltet werden, wie z.B. Farben, Schriften, Abstände und Positionen.
Wie wird CSS verwendet?

    Externe CSS-Datei: Die bevorzugte Methode, um CSS zu verwenden, ist das Erstellen einer externen CSS-Datei und deren Verknüpfung mit dem HTML-Dokument über das <link>-Element im <head>-Bereich.

    Beispiel:

    html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Webseite</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Hier kommt dein Inhalt -->
</body>
</html>

Inline CSS: CSS-Stile können auch direkt innerhalb eines HTML-Elements mithilfe des style-Attributs definiert werden.

Beispiel:

html

<h1 style="color: blue; font-size: 24px;">Überschrift</h1>

Verwendung von Selektoren: Selektoren werden verwendet, um HTML-Elemente auszuwählen und ihnen bestimmte Stile zuzuweisen.

Beispiel:

css

    /* Einzelner Selektor */
    h1 {
        color: blue;
    }

    /* Klassen-Selektor */
    .box {
        background-color: yellow;
    }

    /* ID-Selektor */
    #header {
        font-size: 20px;
    }

Weiterführende Ressourcen

Um mehr über CSS zu lernen und fortgeschrittene Konzepte zu verstehen, empfehlen wir folgende Ressourcen:

    W3Schools CSS Tutorial: Ein umfassendes Tutorial, das CSS von Grund auf erklärt und verschiedene Stileigenschaften vorstellt.

Das war eine grundlegende Einführung in CSS für Neueinsteiger. Mit diesen Kenntnissen kannst du bereits das Aussehen deiner Webseiten anpassen. Viel Spaß beim Lernen und Experimentieren!
