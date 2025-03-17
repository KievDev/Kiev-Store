<h1 align="center"><a href="https://kiev-store.onrender.com">KIEVSTORE</a></h1>

<br/>

![Demo App](/frontend/public/demo-app.png)
<br/>
<h1>Das Projekt</h1>
<p>Der Hauptgrund für das Projekt war, die Verwendung verschiedener moderner Technologien in einer Full-Stack-Anwendung zu demonstrieren, wobei der Schwerpunkt auf dem PERN-Stack lag.

Insgesamt gibt es 13 Themen, aus denen der Benutzer wählen und seine Erfahrungen nach Belieben anpassen kann.

Wir können ein Produkt mit Namen, Preis und Foto in die Datenbank aufnehmen, jedes dieser Elemente bearbeiten und die gleichen Produkte auch wieder löschen.

Wir haben eine „Refresh“-Funktion, so dass wir die neuesten Daten aus der Datenbank abrufen können.

Sauber strukturierte Codes und Ordner, um einfach zu pflegen und skalierbar zu sein.</p>
<br/>
![Product Demo](/frontend/public/demo-product.png)
<br/>
<h1>Themen</h1>
<p>Wie bereits erwähnt, gibt es 13 verschiedene Themen zur Auswahl.

Hier sind einige Beispiele neben dem bereits gezeigten.</p>
<div align="center" display="flex" flex-direction="row" justify-content="center">
  
![Theme Demo 1](/frontend/public/theme1.png)![Theme Demo 2](/frontend/public/theme2.png)
</div>
<br/>
<h1>Tech Stack</h1>
<ul>
  <br/>
  <li>Frontend</li>
    <ul>
      <br/>
      <li>React.js – Die zentrale Frontend-Bibliothek, die interaktive Benutzeroberflächen mit wiederverwendbaren Komponenten erstellt. Sie hilft, dynamische Daten und Zustände effizient zu verwalten.</li>
      <li>Tailwind CSS – Ein CSS-Framework, das das Styling beschleunigt, ohne dass man eigenes CSS schreiben muss. Ideal für responsive Designs.</li>
      <li>DaisyUI – Eine auf Tailwind basierende UI-Komponentenbibliothek, die vorgestylte Komponenten bereitstellt und so die Entwicklungszeit verkürzt.</li>
      <li>Lucide Icons – Ein sauberes und anpassbares Icon-Set zur Verbesserung des UI-Designs. Nützlich für Schaltflächen, Navigation und Warnungen.</li>
      <li>Hot Toast – Eine leichtgewichtige Toast-Benachrichtigungsbibliothek zur Anzeige von Warnungen, Fehlern und Erfolgsmeldungen in Ihrer Anwendung.</li>
      <li>Zustand – Eine Zustandsverwaltungsbibliothek für React, die einfacher und schlanker ist als Redux. Nützlich für die globale Zustandsverwaltung.</li>
      <li>Vite – Ein schnelles Frontend-Build-Tool und Entwicklungsserver, der Webpack für bessere Leistung und schnelleres Hot Module Reloading (HMR) ersetzt.</li>
      <br/>
    </ul>
  <li>Backend</li>
    <ul>
      <br/>
      <li>Node.js – Die Laufzeitumgebung, die die Ausführung von JavaScript auf der Serverseite ermöglicht und Backend-Logik und API-Anfragen verarbeitet.</li>
      <li>Express.js – Ein leichtgewichtiges Node.js-Framework für die Erstellung von APIs. Es verwaltet Routen, Middleware und Serverlogik auf eine saubere Art und Weise.</li>
      <li>PostgreSQL – Eine leistungsstarke relationale Datenbank, in der strukturierte Daten für Ihre Anwendung gespeichert werden, auf die über SQL-Abfragen zugegriffen wird.</li>
      <br/>
    </ul>
  <li>Tools & Cloud</li>
    <ul>
      <br/>
      <li>Neon Tech – Ein cloud-nativer, serverloser PostgreSQL-Dienst. Er bietet eine verwaltete Datenbanklösung mit automatischer Skalierung, die die Bereitstellung erleichtert.</li>
      <li>Arcjet – Ein Bereitstellungs- und Hosting-Service, der wahrscheinlich verwendet wird, um Ihr Backend und Ihre Datenbank mit minimaler Einrichtung bereitzustellen.</li>
      <li>Postman – Ein API-Testtool, mit dem Sie Anfragen an Ihr Backend senden, APIs debuggen und Endpunkte einfach testen können.</li>
      <br/>
    </ul>
</ul>

### Einrichten der .env-Datei

```js
PORT=3000

PGUSER=...
PGPASSWORD=...
PGHOST=...
PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

### Ausführen der API

```shell
npm run dev
```

### Starten Sie das Frontend

```shell
cd frontend
npm run dev
```
<br/>
<p>...und nicht zuletzt ist sie zu 100 % reaktionsschnell!</p>
