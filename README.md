## Video vs. Beitrag (Artikel)

<video width="100%" height="100%" controls>
  <source src="https://cdn.freshclip.tv/docs/q-create-article-from-video-2020-04-20.mov" type="video/mp4">
</video>

## Login

[Production (https://q.freshclip.tv/)](https://q.freshclip.tv/)

[Staging (https://stage-q.freshclip.tv/)](https://stage-q.freshclip.tv/)

Benutze die gleichen Zugangsdaten wie im CMS. Ggf. die Funktion _Passwort vergessen?_ benutzen, um Passwort auf *beiden* Plattformen zu ändern.

## Beiträge

Im neuen Q gibt es nur noch Beiträge. Videos sind nur noch Komponenten eines Beitrags (siehe unten). Die meisten der Beiträge sind Artikel. Aber auch Personen, Themen & Redakteure sind Beiträge:

![image](https://user-images.githubusercontent.com/141123/77955761-0a043280-72d1-11ea-89e3-6ff60c5a8b21.png)

### Übersicht

Die Übersicht lässt sich nach mehreren Kriterien filter. Je nach Kontext können dies

- Typ
- Website
- Kategorie
- Gelöscht
- Mit abgelaufenem/gelöschtem Video
- Ohne SEO-Text
- Ohne Profilbild

sein.

Über die Spaltenköpfe lassen sich die gefilterter Beiträge sortieren, wie hier nach dem Veröffentlichungsdatum:

![image](https://user-images.githubusercontent.com/141123/77956774-c4486980-72d2-11ea-8ace-5f7d89dfba26.png)

Durch Klick auf eine Zeile gelangst du zur Seite des Beitrags:

### Stammdaten

Beispiel: https://stage-q.freshclip.tv/websites/1/items/das-coronavirus-die-risikogruppen-diese-stars-sind-besonders-gefaehrdet/edit

![image](https://user-images.githubusercontent.com/141123/77957274-89930100-72d3-11ea-8dcb-6b7b09be701f.png)

Hier können die wichtigsten Daten zum Beitrag bearbeitet werden:

![image](https://user-images.githubusercontent.com/141123/77957347-a596a280-72d3-11ea-8fa0-d06ed5bb6428.png)

Anders als im alten CMS lassen sich hier auch mehrere Redakteure einem Artikel zuordnen (Text + Video):

![image](https://user-images.githubusercontent.com/141123/77957766-48e7b780-72d4-11ea-87e4-7f812a1dd3d2.png)

Für Artikel und Redakteure gibt es die Möglichkeit eine Veröffentlichung vorzunehmen. Artikel können zudem auch zeitlos sein:

![image](https://user-images.githubusercontent.com/141123/77957905-85b3ae80-72d4-11ea-898e-f84f6e343f64.png)

### Komponenten

Jeder Beitrag kann beliebig viele Komponenten haben. Momentan sind diese Komponenten möglich:

![image](https://user-images.githubusercontent.com/141123/77955877-3b7cfe00-72d1-11ea-8bec-726ad67cd96a.png)

Über das Tab _Komponenten_ lassen sich die Inhalte des Beitrags editieren:

![image](https://user-images.githubusercontent.com/141123/77958204-f78bf800-72d4-11ea-80b9-0721fd92eff6.png)

#### Video

![image](https://user-images.githubusercontent.com/141123/77958348-35891c00-72d5-11ea-9abb-0aaabfec1c2b.png)

Auf der rechten Seite findet sich eine Liste, die immer die letzten erstellten Videos aus dem alten CMS zeigt. Durch Klick kann ein Videos aus der Liste direkt mit der Komponente verlinkt werden:

![image](https://user-images.githubusercontent.com/141123/77958502-69fcd800-72d5-11ea-9e57-b99144bcbebc.png)

Sollte in der Liste nicht das gewünscht Video zu sehen sein, dann kann auch mit der Suchbox unterhalb des Videos direkt gesucht werden:

![image](https://user-images.githubusercontent.com/141123/77958665-a7f9fc00-72d5-11ea-9bdf-e4729e2357f3.png)

Mit dem Löschen Button kann eine Komponente aus dem Beitrag entfernt werden:

![image](https://user-images.githubusercontent.com/141123/77958933-1d65cc80-72d6-11ea-98ce-807847a8d6cb.png)

Mit dem Pfeiltasten kann die Reihenfolge der Komponenten geändert werden:

![image](https://user-images.githubusercontent.com/141123/77959003-38384100-72d6-11ea-8f9d-99ad434eae10.png)

#### Text

Mit der Text-Komponente lassen sich einfache Texte schreiben, wie man unschwer erraten kann:

![image](https://user-images.githubusercontent.com/141123/77959090-57cf6980-72d6-11ea-905d-f64f968e5020.png)

### Bilder und Getty-Bilder

Momentan unterscheiden wir noch zwischen Bildern (die im alten CMS hochgeladen werden) und Getty-Bildern (die wir früher mal über die Getty-API geladen haben).

Das Auswählen des Bilder geschieht ähnlich wie bei den Videos: Rechts erscheint eine Liste der letzten Bilder, die direkt ausgewählt werden können. Über die Suche kann auch nach bestimmten Bildern gesucht werden:

![image](https://user-images.githubusercontent.com/141123/77959557-0d022180-72d7-11ea-9022-9d61bf6d9a71.png)

Nach Bedarf werden wir weitere Komponenten entwickeln.

## Beitragslisten

Wie der Name sagt, handelt sich sich um [geordnete Listen von Beiträgen](https://stage-q.freshclip.tv/item_lists) wie etwa diese:

![image](https://user-images.githubusercontent.com/141123/77960007-db3d8a80-72d7-11ea-8c2b-2c78b2e41b2e.png)

Wie man an den Beispielen sehen kann, werden die Beitragslisten einierseits für die Navigationselemente der Website benutzt wie etwas das Hauptmenü (siehe unten). Oder aber um die Liste der Redakteure einer Website zu definieren. Im letzten Fall kann dann die Liste der Redakteure als Komponente in einen Beitrag eingebaut werden.

[Beispiel "Fein gekocht Redaktion"](https://stage-q.freshclip.tv/websites/2/item_lists/4/edit)

![image](https://user-images.githubusercontent.com/141123/77960352-7171b080-72d8-11ea-909e-5a7082342e69.png)

https://stage-q.freshclip.tv/websites/2/items/redaktion/edit#components

![image](https://user-images.githubusercontent.com/141123/77960414-8c442500-72d8-11ea-86aa-1c72e84f0307.png)

[Auf der Website sieht das dann so aus](https://stage.fein-gekocht.de/redaktion):

![image](https://user-images.githubusercontent.com/141123/77960504-b4cc1f00-72d8-11ea-9d61-0597a1f28f75.png)

Mit einem Klick auf den Teaser des Redakteurs kommt man dann zur [Seite des Redakteurs](https://stage.fein-gekocht.de/redaktion/janina-ninchen-koetz):

Unten sind dann die letzten Artikel des Redakteurs aufgelistet:

![image](https://user-images.githubusercontent.com/141123/77960607-e644ea80-72d8-11ea-9f99-6f42c307826a.png)

## Websites

Hier kannst du das Verhalten von unseren Web-Portalen konfigurieren:

![image](https://user-images.githubusercontent.com/141123/77925541-44f07100-72a5-11ea-99af-5f307a04d090.png)

### Domains

Die Domains haben momentan noch keine weitere Bedeutung. Später werden sie jedoch dem AdManagement helfen.

![image](https://user-images.githubusercontent.com/141123/77925746-88e37600-72a5-11ea-978d-b8494bb03933.png)

### Navigation

Jede Website enthält mehrere Navigationen. Bei it's in TV und Fein gekocht sind das aktuell die Hauptnavigation und die Navigation im Footer. Im Bereich Website-Navigation kannst eine Beitragsliste hinterlegen:

![image](https://user-images.githubusercontent.com/141123/77925813-9f89cd00-72a5-11ea-9446-6f1860df6ab3.png)

## Globale Suche

In Q gibt es eine globale Suche mit der ohne weitere Klicks alle Arten von Beiträgen finden kannst:

![image](https://user-images.githubusercontent.com/141123/77925335-0a86d400-72a5-11ea-9c8b-20a6e61e4fa7.png)
