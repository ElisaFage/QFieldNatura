# QFieldNatura – Acquisition de données naturalistes sur le terrain avec QField 🌍

QFieldNatura est un projet QGIS, conçu pour faciliter l’acquisition de données naturalistes sur le terrain via l’application mobile QField. 

💡 Dans la continuité du Kit Bota d’Augustin Soulard et des projets QFaune et QFlore de Félix Hinckel, __ce projet propose une solution unifiée pour la prise de données faune, flore, habitats et zones humides au sein d’un même environnement__.

🔗 Téléchargez la dernière version stable de QFieldNatura : [QFieldNatura](https://github.com/ElisaFage/QFieldNatura/archive/refs/heads/main.zip)

## 🛠️ Fonctionnalités principales

### ✅ Gestion des statuts des espèces
* À partir de la couche "Projet", définissant une région, les statuts associés sont automatiquement attribués aux espèces observées.

### ✅ Acquisition de données 
* Incrémentation automatique des numéros associés aux couches :
        - Relevés végétaux
        - Sondage pédologique
        - Pose de matériel (par type de matériel).
* Interactions dynamiques entre les couches "Relevés", "Points d’écoute" et leurs couches "Observations" associées.
* Nombreuses fonctionnalités d’acquisition de données par point géoréférencé disponibles.

### ✅ Exportation des données sous différents formats
* Tableau croisé dynamique des coefficients de Braun-Blanquet selon les relevés floristiques et espèces observées.
* Tableau des statuts des espèces observées.
* Format officiel DepoBio SINP (avec les colonnes dans l’ordre requis).
* Format officiel SINP AuRA adapté aux exigences régionales.

### ✅ Mise à jour automatique des statuts et noms d’espèces
* Grâce au plugin AutoUpdateTAXREF, QFieldNatura intègre les dernières mises à jour du TAXREF et des stauts de l’INPN

📌 Découvrir AutoUpdateTAXREF :


 
## 🔍 QFieldNatura tri les espèces selon les catégories TAXREF suivantes : 

### 🌿 Flore
* GROUP1_INPN : _Algues, Bryophytes, Trachéophytes_

### 🐦 Faune
* Oiseaux : Classe _Aves_
* Amphibiens : Classe _Amphibia_
* Reptiles : GROUP2_INPN 
* Mammifères (terrestres, aquatiques, semi-aquatiques et volants) : Classe _Mammalia_

### 🦋 Insectes
* Odonates : Ordre _Odonata_
* Orthoptères : Familles : _Acrididae, Gryllidae, Gryllotalpidae, Mogoplistidae, Myrmecophilidae, Pamphagidae, Phalangopsidae, Pyrgomorphidae, Rhaphidophoridae, Tetrigidae, Tettigoniidae, Tridactylidae, Trigonidiidae_
* Lépidoptères : Familles : _Papilionidae, Pieridae, Nymphalidae, Satyrinae, Lycaenidae, Hesperiidae, Zygaenidae_
* Coléoptères : Familles :  _Carabidae, Hydrophilidae, Sphaeritidae, Histeridae, Ptiliidae, Agyrtidae, Leiodidae, Staphylinidae, Lucanidae, Trogidae, Scarabaeidae, Eucinetidae, Clambidae, Scirtidae, Buprestidae, Elmidae, Dryopidae, Cerophytidae, Eucnemidae, Throscidae, Elateridae, Lycidae, Cantharidae, Derodontidae, Nosodendridae, Dermestidae, Endecatomidae, Bostrichidae, Ptinidae, Lymexylidae, Phloiophilidae, Trogossitidae, Thanerocleridae, Cleridae, Acanthocnemidae, Melyridae, Malachiidae, Sphindidae, Nitidulidae, Monotomidae, Phloeostichidae, Silvanidae, Cucujidae, Laemophloeidae, Cryptophagidae, Erotylidae, Biphyllidae, Bothrideridae, Cerylonidae, Alexiidae, Endomychidae, Corylophidae, Latridiidae, Mycetophagidae, Ciidae, Tetratomidae, Melandryidae, Zopheridae, Mordellidae, Tenebrionidae, Prostomidae, Oedemeridae, Pythidae, Pyrochroidae, Salpingidae, Aderidae, Scraptiidae, Cerambycidae, Chrysomelidae, Anthribidae, Brentidae, Dryophthoridae, Curculionidae_
