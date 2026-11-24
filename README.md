# 3D-Druck-Auto für Elektroantrieb

Die Wanne hat zwei seitliche Motorfächer am Heck, einen Bereich für den Akku und Platz für Steuerung oder Empfänger. Die Hinterräder sitzen jeweils auf einer kurzen Motorwelle. Die Karosserie wird von oben aufgesetzt und von unten mit vier M3-Schrauben befestigt.

## Druckteile

| Druckteil | Anzahl | Maße oder Funktion |
| --- | ---: | --- |
| [Wanne](stl/wanne.stl) | 1 | 190 × 104 × 40 mm am Wannenrand, 136,8 mm breit an den Schraublaschen |
| [Karosserie am Stück](stl/karosserie.stl) | 1 | 233 × 164 × 92 mm |
| [Karosserie vorne](stl/karosserie_vorne.stl) und [hinten](stl/karosserie_hinten.stl) | je 1 | Alternative zur einteiligen Karosserie, jede Hälfte hat zwei Schraubpunkte |
| [Vorderrad](stl/rad_vorne.stl) | 2 | Ø 65 × 24 mm, Ø 3,6 mm Achsbohrung |
| [Hinterrad](stl/rad_hinten.stl) | 2 | Ø 65 × 24 mm, doppelt abgeflachte Aufnahme 3,8 × 5,5 mm |
| [Distanzring](stl/distanzring_1_5mm.stl) | bei Bedarf 2 | 1,5 mm dick, für die Vorderachse |

## Platz für die Technik

Die Koordinaten beziehen sich auf die Wanne. X läuft von hinten nach vorn, Y von der Mittellinie nach außen und Z ab der Unterseite nach oben. Die Maße beschreiben kollisionsfrei geprüfte rechteckige Bereiche im Modell.

| Bauteil | Geprüfter Raum (L × B × H) | Position in der Wanne |
| --- | --- | --- |
| Akku | 80 × 35 × 35 mm | X 72–152 mm, Y −20,5 bis +14,5 mm, auf dem Wannenboden bei Z ≈ 3 mm |
| Steuerung oder Empfänger | 45 × 48 × 25 mm | X 22–67 mm, Y −24 bis +24 mm, ab Z 5 mm über den Bodenstegen |
| Motor oder Getriebe | 58 × 18 × 27 mm je Seite | X 9,8–67,8 mm, zwischen 30,75 und 48,75 mm von der Mittellinie, ab Z ≈ 3 mm |

Die beiden Motorwellenschlitze sind nach oben offen und jeweils 7,5 mm breit. Die vorgesehene Wellenachse liegt bei X 15,5 mm und Z 14,25 mm. Die Durchgänge sind für zwei kurze Wellen ausgelegt. Prüfe bei der Motorauswahl Wellenprofil, Wellenposition, freie Wellenlänge und den Platz für Stecker und Kabel. Die geprüften Quader enthalten keine zusätzliche Montage- oder Kabelreserve. Motoren und Akku müssen zur endgültigen Montage in der Wanne befestigt werden.

## Drucken und montieren

1. STL-Dateien in Millimetern importieren. Die Wanne und Distanzringe mit der Unterseite und die Räder mit der flachen Außenseite auf das Druckbett legen. Bei der Karosserie im Slicer Stützen unter den inneren Schraubauflagen und bei Bedarf unter den übrigen Überhängen vorsehen. Die einteilige und die geteilte Karosserie sind alternative Drucksätze.
2. Die Motoren in die Seitenfächer einsetzen, die Wellen durch die offenen Schlitze führen und die Motoren befestigen. Die Hinterräder auf die passenden Wellen setzen. Rund 1,5 mm Abstand zwischen Rad und Wanne wurden digital geprüft. Das nötige Spiel hängt von der tatsächlichen Welle und dem Druck ab.
3. Vorn eine 3-mm-Achse einsetzen, die Räder mit etwas seitlichem Spiel montieren und gegen Abrutschen sichern. Die Distanzringe halten die Vorderräder von der Wanne fern. Beide Vorderräder sollen sich von Hand frei drehen.
4. Technik befestigen und Leitungen aus den Rad- und Achsbereichen führen. Vier M3-Sechskantmuttern von oben in die Taschen der Karosserie einsetzen. Die Karosserie aufsetzen und mit vier M3 × 12 mm Schrauben von unten befestigen. Bei der geteilten Variante beträgt die Fuge im Modell 0,28 mm.

Alle sieben STL-Dateien wurden auf geschlossene Netze und geschlossene Schnittkonturen in 0,2-mm-Abständen geprüft. Der Zusammenbau, die Radfreigängigkeit und die angegebenen Bauraumquader wurden digital geprüft. Drucktoleranzen und der Sitz der tatsächlichen Komponenten lassen sich an einem physischen Probedruck beurteilen.
