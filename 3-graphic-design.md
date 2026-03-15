# Echoes Of Sin: Confusion
# Kapitola 3: Grafické zpracování (Graphic Design)

Ukázky naleznete zde: https://store.steampowered.com/app/4426280/Echoes_of_Sin_Confusion/

### 3.1 Pravidla grafického zpracování

* **Prostor:** Koncept hry je výhradně **3D**. Využíváme dynamické osvětelní k budování strachu a atmosféry.
* **Vizuální styl:** Cílem je dosáhnout **realistického a temného vizuálu**
* **Optimalizace:** Veškeré 3D modely procházejí striktní optimalizací. Pečlive kontrolujeme polygonové a voxelová data modelů, které naši grafici optimalizují.
* **Světlo a materiály:** Dynamické nasvícení řešíme systémem **Lumen** (Global Illumination). V závislosti na prostředí vyvíjíme vlastní **materiálové Blueprinty**, které umožňují texturám dynamicky reagovat na změny v herním světě.

---

### 3.2 Softwarové a hardwarové vybavení
Unreal Engine je velice komplexní nástroj a samotný v sobě nabízí spousty sytémů, právě i pro práci s texturami, stíný, světly, 3D modely. Můžeme tak říci že je to soubor spousty dalších programů, které využíváme v naší hře.

| Typ nástroje | Konkrétní software | Účel využití |
| :--- | :--- | :--- |
| **Herní Engine** | Unreal Engine 5 | Integrace assetů, fyzika, Lumen a finální rendering. |
| **3D Modelování** | Blender | Modelování prostředí, úprava licencovaných modelů a rigging. |
| **2D / Textury** | Photoshop / Affinity | Tvorba UI prvků, post-produkce textur a marketing. |

---

### 3.3 Skutečné grafické assety

#### **3D Modely**
V projektu pracujeme se 500+ assetů, které tvoří unikátní atmoséfru hry. Kombinujeme stovky licencovaných prvků s autorskými modely vytvořenými týmem  **RedCoris**.

* **Prostředí:** Detailní modely nemocničního vybavení (lehátka, přístroje, nábytek).
* **Postavy:** Modely pro hororové sekvence, cutscény a vizuální zobrazení anomálií.
* **Exteriéry:** Specifická flóra pro venkovní úrovně, doplňující celkový lore hry.

#### **2D a Texturování**
Grafici mimo 2D obrázků vytvářejí také komplexní vrstvené materiály. Tyto textury jsou následně procesovány přímo v **Unreal Enginu** pomocí nodového systému.

* **Dynamika:** Materiály reagují na okolí (např. světlo, okolní objekty).
* **Adaptace:** Textury se dokáží automaticky napojovat na ostatní modely pro přirozený vzhled scény.

