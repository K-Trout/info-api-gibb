# info-api-gibb

Spicks und ähnliche Unterlagen gesammelt während der Lehre Informatiker API Way-up an der gibb

---

## Inhalte

- [M100](#M100)
- [M104](#M104)
- [M114](#M114)
- [M117](#M117)
- [M123](#M123)
- [M153](#M153)
- [M403](#M403)
- [M404](#M404)
- [M431](#M431)


---

## M100

[spick_100_1.pdf](M100/spick_100_1.pdf)

## M104

[spick_104_1.pdf](M104/spick_104_1.pdf)

## M114

[spick_114_1.pdf](M114/spick_114_1.pdf)

[spick_114_2.pdf](M114/spick_114_2.pdf)

Hilfreich zum Verständnis von kryptografischen Verfahren kann die folgende [Playlist](https://www.youtube.com/watch?v=6xDGSalpPXk&list=PL5KkMZvBpo5CdoOxa3dqll2n6KsXqerYO) von Eddie Woo sein.
Im Speziellen die Videos zu RSA.
Falls auch noch weiteres Interesse an dem Thema der Kryptografie herrscht, kann ich das Buch [*A very short Introduction to Cryptography*](https://www.veryshortintroductions.com/view/10.1093/actrade/9780192803153.001.0001/actrade-9780192803153) von Fred Piper und Sean Murphy, erschienen bei der Oxford University Press, empfehlen.

## M117

[spick_117_1.pdf](M114/spick_117_1.pdf)

[spick_117_2.pdf](M114/spick_117_2.pdf)

## M123

[spick_123_2.pdf](M114/spick_123_2.pdf)

Das Modul 123 bietet eine Einführung in die Grundlagen des Aufbaus eines Netzwerkes mit Windows-Servern. Während die Anleitung gegeben in den Modulunterlagen (Stand Januar 2020) durchaus brauchbar ist, gibt es mehrere Stellen, an welchen ohne Vorwissen des Gebietes Verwirrungen und Mehraufwand sich präsentieren können:

1. Die Unterlagen sind eine Anleitung, keine Erklärung. Während man sicher etwas dabei lernt, auch theoretisches Wissen ist dabei, ist es mehr oder weniger ein "Tutorial". Jedoch sind jeweils in den Ordnern "Anleitung" auch theoretische Hintergründe zu finden. Ich halte dazu an, zum eigenen Wohle vielleicht mal eine theoretische Erklärung der erwähnten Serverrollen und Funktionen zu lesen. Auch Wikipedia ist da nicht schlecht dafür. Am wichtigsten jedoch:
2. **_Konfiguriert AD DS vor DNS und DHCP. Dies sind die Best-Practices gegeben durch Microsoft.** Die Unterlagen tun dies nicht. Dies, da die AD auch Teile von DNS und DHCP konfiguriert. Jedoch führt eine "falsche" Reihenfolge praktisch unweigerlich zu Problemen wegen Inkonsistenzen.
Die Unterlagen haben eine falsche Reihenfolge aus didaktischen Gründen, um die Funktionen besser zu zeigen. Diese lernen sich aber besser mit Erklärungen lesen und Lehrer und Arbeitskollegen fragen, als mit neu beginnen zu müssen und Flüchen gegen den Server, der plötzlich nicht mehr starten will, auszusprechen.

## M153

[spick_153_1.pdf](M114/spick_153_1.pdf)

## M403

Objektorientiertes Programmieren. Die Unterlagen (Stand Winter 2019) erklären zwar nie richtig, was das genau ist, aber man lernt doch was. In der ersten LB kommen kleinliche Fragen zu C#. Datentypen und Syntax.
In der zweiten gilt es während der Prüfung eine kleine Konsolenanwendung zu schreiben. Während in der Aufgabenstellung schon eine Logik vorgegeben ist, sollte es nicht zu viel Abzug geben, wenn man eine eigene (funktionierende!) mit gleichem Output implementiert. Dazu will ich jedoch keine absolute Garantie geben, bei mir war es jedenfalls so.

## M404

Spicks habe ich keine, in der ersten LB geht es um Datentypen, das Erkennen von Fehlern und erweiterten von vorgegebenem Quellcode. Das zweite ist ein Projekt, in welchem Mal zum Beispiel ein Spiel (in meinem war es Snake) programmieren muss. Dabei sind Spiel und gewisse Spielmechanismen gefordert. Ein Template o.Ä. wird nicht zur Verfügung gestellt.

## M431

Das Ziel im Modul 431 ist unter anderem, eine Webseite zu bauen. Während ich hierzu keinen Spick oder ähnliche Materialien bieten und auch die Webseite schon Geschichte ist, kann eine Archiv-Version [hier](https://flueck.weebly.com/431.html) gefunden werden.
