# Git auf Schwäbisch

Des tägliche Gschwätz in deitsche Endwigglungsteams, dia mit `git`
(ibersetzt: `Huadsembl` odr `Seggl`) schaffet, isch efdr a mords Denglish.
_"Kannst du bitte pullen"_ odr _"Hast du gepusht"_ send bloß zwoi von deane oft saudomm klengede Konschdruktione.

Git auf Schwäbisch hilft!

## Vorschläg

Do sen zwoi Tabelle mit Vorschläg wia mer schdattdesse schwätze ko.

| Verb        | Gschwätz grade     | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmache              |
| add         | adden              | drzuado               |
| pull        | pullen             | ziage                 |
| push        | pushen             | drigge                |
| clone       | clonen             | kobiere               |
| fetch       | fetchen            | hole                  |
| branch      | branchen           | abzweige              |
| commit      | commiten           | ibergäbe              |
| rebase      | rebasen            | (nei) schdaple        |
| diff        | diffen             | ondrscheide           |
| merge       | mergen             | zammdoe               |
| fork        | forken             | gable                 |
| stash       | stashen            | uffhebe               |
| tag         | taggen             | omole                 |
| cherry-pick | cherry-picken      | Zibebe klaube         |
| checkout    | checkouten         | raushole              |

| Subschdantiv  | Gschwätz grad      | Vorschlag            |
|---------------|--------------------|----------------------|
| git           | git                | Seggl                |
| github        | github             | Segglzendrale        |
| gitlab        | gitlab             | Seggllabor           |
| gitea         | gitea              | Seggltee             |                
| bitbucket     | bitbucket          | Gebissoimr           |
| repository    | repo               | Heia                 |
| branch        | branch             | Äschdle              |
| commit        | commit             | Ibergab              |
| log           | log                | Tagebuach            |
| pull request  | pull request       | Ziah-Ofrog           |
| merge request | merge request      | Zammdoa-Ofrog        |
| stash         | stash              | Bongr                |
| status        | status             | Zuaschtand           |
| tag           | tag                | Pungt                |
| origin        | origin             | Urschbrung           |
| master        | master             | Meischdr             |

## Beispiele

    - Kosch du grad mol des Äschdle, wo i grad omgschriebe hab, ziage ond zur Segglzendrale drigge?

    - Do dafir hab e a neie Heia oglegt, kobier's dr ond nemm dr's Entwigglungsäschdle.

    - Noi, drigg des glei zom Meischdr em Urschbrung!

    - I hab grad abzweigt ond dia Ändronge aus meim Bongr ibrgäbe.

    - Machsch grad a Ziah-Ofrog wenn'd mitm Zammdoe ferdig bisch!

    - Am beschde mir klaubet ons d'Ziabebe ausm Meischder-Äschdle raus.

    - Gabled se en dr Segglzendrale!

## Seggl auf Schwäbisch owende

Wer's konsekwent mache mog, do isch a Olaidung, wia mr Seggl auf Schwäbisch au en dai Konsol neibrengt. Weil bei Seggl koine Omlaud ganget, miase mers halt andersch mache. Schreib des en dei `~/.gitconfig`:

    git config --global alias.uffmache init
    git config --global alias.kobier clone
    git config --global alias.ziag pull
    git config --global alias.duedrzue add
    git config --global alias.drigg push
    git config --global alias.driggfeschdr push --force
    git config --global alias.aeschdle branch
    git config --global alias.ibergib commit
    git config --global alias.schdabel rebase
    git config --global alias.ondrscheid diff
    git config --global alias.duezamm merge
    git config --global alias.bongr stash
    git config --global alias.mol tag
    git config --global alias.holraus checkout
    git config --global alias.tagebuach log
    git config --global alias.zuschdand status

Dann schreib no dia Zeil in deinre `~/.bashrc` (odr was dei Betriebssyschdem halt so härgibt) drzue:

    alias seggl=git
