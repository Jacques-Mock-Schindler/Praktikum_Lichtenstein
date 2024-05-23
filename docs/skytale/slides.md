---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: *fff
author: Jacques Mock Schindler

---
<style>
    section { justify-content: start; }
</style>

<style scoped>
  h1 {color: white;
      background-color: rgba(0, 0, 0, 0.35);
      border-radius: 4px;
      }
section {
  background-image: url('./titelbild.jpg'); /* Pfad zum Hintergrundbild */
  background-size: cover; /* Stellt sicher, dass das Bild die ganze Folie bedeckt */
  background-position: center; /* Zentriert das Bild */
}
</style>
# Verschlüsselungsmethode SKYTALE

---



## Historische Situierung von SKYTALE
   
   SKYTALE wurde bereits vor CAESAR durch die Spartaner verwendet. Der
   Name dieses Verschlüsselungsverfahrens leitet sich vom altgriechischen
   Wort für Stab ($\sigma \kappa \upsilon \tau \alpha \lambda \eta$) ab.
   Der römische Geschichtsschreiber Cornelius Nepos beschreibt das
   Verschlüsselungsverfahren in seiner [Biographie](https://www.gottwein.de/Lat/nepos/paus01.php#:~:text=id%20postquam%20Lacedaemonii%20rescierunt%2C%20legatos%20cum%20clava%20ad%20eum%20miserunt%2C%20in%20qua%20more%20illorum%20erat%20scriptum%3A%20nisi%20domum%20reverteretur%2C%20se%20capitis%20eum%20damnaturos.) des spartanischen Heerführers Pausanias. Pausanias war einer der beiden Heerkönige
   Spartas in den Perserkriegen (fünftes vorchristliches Jahrhundert).

---


## Demonstration von SKYTALE
   
![bit.ly/230523_skytale](image.png)

---

## Simulation von SKYTALE
   
Wie kann SKYTALE ohne Stab simuliert werden?

* SKYTALE kann als Tabelle dargestellt werden. Dabei ergibt die Anzahl
  Umwicklungen die Anzahl Spalten der Tabelle und die Anzahl der Flächen
  des Stabes (oder auf den Stab geschriebenen Zeilen) die Anzahl der
  Zeilen der Tabelle.

---

## Anwendungsübung SKYTALE
   
Was muss der "Lauscher" wissen, damit er den Code knacken kann?

* Grundsätzlich reicht es, wenn die Anzahl Textzeilen bekannt sind.

Wie sieht eine systematische Vorgehensweise für die Entschlüsselung ohne
dieses Wissen aus? 

* Der Text wird in Tabellen "abgefüllt" bei denen bei jedem Versuch die
  Anzahl Zeilen um eins erhöht wird. 

---

## Beurteilung von SKYTALE
   
Wie viele Möglichkeiten für die Verschlüsselung gibt es?

* Grundsätzlich ist die Anzahl Verschlüsselung von der Anzahl Zeilen und
  Spalten der Tabelle abhängig. Ergänzend kann noch die Leserichtung
  verändert werden. 

Wie könnte SKYTALE "verbessert" werden?

* Es wäre beispielsweise möglich, mehrere Durchläufe zu machen. 
