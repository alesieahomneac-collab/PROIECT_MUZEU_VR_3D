# Virtual Art Museum - Interactive VR Experience

Acesta este un proiect de realitate virtuală (VR) dezvoltat pentru web, utilizând framework-ul **A-Frame**. Proiectul constă într-o galerie de artă digitală cu 25 de exponate interactive, axate pe teme precum natura, fauna și peisajele urbane.

## 🚀 Demo
Proiectul poate fi vizualizat direct în browser (compatibil cu desktop și dispozitive VR).
*Link către GitHub Pages: https://github.com/alesieahomneac-collab/PROIECT_MUZEU_VR_3D.git*

---

## ✨ Caracteristici principale

* **Mediu Imersiv 3D**: O galerie spațioasă cu 4 pereți expoziționali.
* **25 de Exponate**: Imagini de înaltă calitate organizate tematic.
* **Ghid Audio (English Audio Guide)**: La click pe orice tablou, sistemul utilizează *Web Speech API* pentru a citi descrierea operei în limba engleză.
* **Interactivitate Vizuală**:
    * **Zoom la Hover**: Tablourile se măresc și se apropie de vizitator când acesta privește spre ele.
    * **Descrieri Text**: Afișarea temporară a detaliilor despre operă (titlu, tematică).
* **Sistem de Navigare**: Utilizatorul se poate deplasa folosind tastele `WASD` și poate privi în jur cu mouse-ul.

---

## 🛠️ Tehnologii Utilizate

* **HTML5 & CSS3**
* **A-Frame (v1.4.0)** - Framework pentru VR bazat pe Three.js.
* **JavaScript (ES6)** - Pentru logica de interacțiune și integrarea Audio Guide.
* **Web Speech API** - Pentru sinteza vocală (Text-to-Speech).

---

## 📂 Structura Proiectului

```text
.
├── index.html          # Codul sursă principal al aplicației
├── README.md           # Documentația proiectului
├── assets/             # Folderul ce conține resursele vizuale
│   ├── tablou1.jpg
│   ├── ...
│   └── tablou25.jpg
└── Documentatie_ITRMV.pdf  # Documentația formală pentru susținere
