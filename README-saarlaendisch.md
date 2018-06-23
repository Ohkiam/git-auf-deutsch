# Git auf Deutsch (Saarländisch)

Et imma wirrakehrende Gelaba in deitsche Entwicklateams, die `git`
(übersetzt: `Schwachkopf`) benutze, is oft et feinschde Denglish.
_"Kanschde mo bitte pulle"_ orra _"Haschde gepusht"_ sinn nua zwo
von de komisch klingenschde Konschdruktione.

Git off Deitsch (Saarländisch) hiflt da dodebei!

## Vorschläsch

Lo kummen ewei zwo Tabelle mit Vorschläsch fia jere Dach

| Verb        | Aktueller Gebrauch | Vorschlach        |
| ----------- | ------------------ | ----------------- |
| init        | initten            | inrischde         |
| add         | adden              | hinzufije         |
| pull        | pullen             | zije              |
| push        | pushen             | drigge            |
| clone       | clonen             | nomache           |
| fetch       | fetchen            | abholle           |
| branch      | branchen           | abzwaije          |
| commit      | commiten           | iwagen            |
| rebase      | rebasen            | umschreiwe        |
| diff        | diffen             | unnascheire       |
| merge       | mergen             | sesammelee        |
| fork        | forken             | gawelle           |
| stash       | stashen            | vergrawe          |
| tag         | tagen              | makkiere          |
| cherry-pick | cherry-picken      | die rosiene pigge |
| checkout    | checkouten         | holle             |
| log         | log                | nogugge           |

| Substantiv    | Aktueller Gebrauch | Vorschlach        |
| ------------- | ------------------ | ----------------- |
| git           | git                | Dommbeidel        |
| github        | github             | Dommbeidelzentrum |
| gitlab        | gitlab             | Dommbeidellaboa   |
| bitbucket     | bitbucket          | Eifeltee-eemer    |
| repository    | repo               | Laga              |
| branch        | branch             | Aschd             |
| commit        | commit             | Üwagab            |
| pull request  | pull request       | Zihhanfroh        |
| merge request | merge request      | Sesammeleeanfroh  |
| stash         | stash              | Bunga             |
| status        | status             | Unnn              |
| tag           | tag                | Markierung        |
| origin        | origin             | Urschprung        |
| master        | master             | Meischda          |

## Beispiele

    - Kanschde den Aschd den eisch grad umgeschrief han zije un uffet Dommbeidelzentrum drigge?

    - Dofoa han eisch a neijet Laga ingerischd, mach et no un hol da de Entwicklaaschd.

    - Nee, drigg dat zum Meischda im Urschprung, awa flott!

    - Eich hab ewei grad abgezwaid un die Ännerunge nommo aus meinem Bunga rausgehol.

    - Stell e Zihhanfroh, wenn de mittem Sesammelee ferdisch bischd!

    - Am beste picke ma uus die Rosinen aus em Meischdaaschd eraus.

    - Gawell uff em Dommbeidelzentrum!

## Git auf Deutsch (Saarländisch) anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf saarländisch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig`
vor:

```
    git config --global alias.zieh pull
    git config --global alias.drick push
    git config --global alias.aschd branch
    git config --global alias.abzwaije branch
    git config --global alias.iwagen commit
    git config --global alias.umschreiwe rebase
    git config --global alias.sesammelee merge
    git config --global alias.vergrawe stash
    git config --global alias.makkiere tag

    alias dommbeidel=git
```
