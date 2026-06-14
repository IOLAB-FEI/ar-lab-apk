# AR‑Lab

> Mobilné virtuálne laboratórium v rozšírenej realite (AR) pre výučbu mechatroniky.
> Mobile augmented‑reality virtual laboratory for teaching mechatronics.

![version](https://img.shields.io/badge/version-2.0-blue)
![platform](https://img.shields.io/badge/platform-Android%207.1%2B-3ddc84)
![engine](https://img.shields.io/badge/engine-Unity%206-000000)
![AR](https://img.shields.io/badge/AR-Google%20ARCore-4285F4)

🌐 **Web:** [iolab.sk/activities/ar-lab](https://iolab.sk/activities/ar-lab)

🇸🇰 [Slovensky](#-slovensky) · 🇬🇧 [English](#-english)

---

## 📦 Buildy · Builds

| Verzia<br>Version | Grafika · Graphics | Unity | Backend · API | Stav · Status | Min. Android | Stiahnuť · Download |
|:---:|---|:---:|:---:|:---:|:---:|:---:|
| **2.0** | Nová grafika pre iolab.sk<br>New graphics for iolab.sk | Unity 6 | `ovl.iolab.sk` | ✅ **Aktuálna · Current** | 7.1 (API 25) | **[⬇️ ARLab2.0.apk](ARLab2.0.apk)** |
| **1.0** | Pôvodná grafika<br>Original graphics | Unity 6 | `ovl.iolab.sk` | ⚠️ **Deprecated** | 7.1 (API 25) | [ARLab1.0.apk](ARLab1.0.apk) |
| **0.0** | Pôvodná práca<br>Original work | Unity 2020.3 LTS<br>`2020.3.24f1` | Pôvodný backend (nahradený)<br>Legacy backend (replaced) | 🗄️ **Archív · Archived** | — | — |

> ✅ **Odporúčaný build · Recommended:** **2.0**
> &nbsp;
> ⚠️ **Verzia 1.0 je deprecated** — pôvodná grafika, ale už migrovaná na nový engine (Unity 6) a pripojená na `ovl.iolab.sk`; nahradená verziou 2.0.
> *Version 1.0 is deprecated — original graphics, but already migrated to the new engine (Unity 6) and connected to `ovl.iolab.sk`; superseded by 2.0.*
> &nbsp;
> 🗄️ **Verzia 0.0** je pôvodná práca (Unity 2020.3 LTS), pôvodne pripojená na iný backend, ktorý už bol nahradený (`ovl.iolab.sk`) — udržiavaná v samostatnom Unity projekte, tu nie je na stiahnutie.
> *Version 0.0 is the original work (Unity 2020.3 LTS), originally connected to a different backend that has since been replaced (by `ovl.iolab.sk`) — kept in a separate Unity project and not distributed here.*
> &nbsp;
> 🔭 *Nové buildy pridávame ako nové riadky navrch tejto tabuľky.*
> *New builds are added as new rows at the top of this table.*

---

## 🇸🇰 Slovensky

### O aplikácii

**AR‑Lab** je mobilná aplikácia, ktorá pomocou **rozšírenej reality (AR)** premieta 3D modely
mechatronických zariadení do reálneho prostredia používateľa. Študent tak môže robiť
„virtuálne experimenty" bez toho, aby fyzicky stál v laboratóriu — z domu, cestou na školu
alebo kedykoľvek inokedy.

Stačí namieriť kameru telefónu na rovnú plochu, na ktorej sa zobrazí 3D model zariadenia
(napr. hydraulický systém, lietajúci stroj a pod.). Zariadenie je možné spustiť ako simuláciu,
meniť jeho riadiace parametre a v reálnom čase pozorovať, ako sa správa — a to z ľubovoľného uhla.

Aplikácia je výstupom aktivity **AR‑Lab** tímu **IOLab** na **FEI STU v Bratislave**
(Ústav automobilovej mechatroniky).

### Hlavné funkcie

- 🧊 **3D vizualizácia v AR** — modely mechatronických zariadení priamo vo vašom okolí
- ▶️ **Interaktívna simulácia** — spustenie behu zariadenia a sledovanie jeho správania naživo
- 🎚️ **Zmena parametrov** — úprava riadiacich veličín a okamžitá vizuálna odozva
- 🔄 **Pohľad z každého uhla** — obíďte model a prezerajte si zariadenie z rôznych strán
- 🌍 **Viacjazyčnosť** — slovenčina, angličtina, španielčina

### Požiadavky

- **Android 7.1** (API 25) alebo novší
- Zariadenie s podporou **Google Play Services for AR (ARCore)** —
  zoznam: [Podporované zariadenia ARCore](https://developers.google.com/ar/devices)
- Procesor **arm64‑v8a** (64‑bit)
- Povolenie prístupu ku **kamere**

### Inštalácia (.apk)

1. Stiahnite si **odporúčaný build (2.0)** — [`ARLab2.0.apk`](ARLab2.0.apk); zoznam všetkých buildov nájdete v tabuľke [Buildy](#-buildy--builds) vyššie.
2. V telefóne povoľte inštaláciu z neznámych zdrojov
   (*Nastavenia → Aplikácie → Inštalovať neznáme aplikácie*).
3. Otvorte stiahnutý `.apk` a potvrďte inštaláciu.
4. Pri prvom spustení udeľte aplikácii prístup ku **kamere**.
   Ak na zariadení chýba **ARCore**, systém vás vyzve na jeho doinštalovanie z Google Play.

> 💡 iOS verzia aplikácie je dostupná cez oficiálnu stránku — pozri [iolab.sk/activities/ar-lab](https://iolab.sk/activities/ar-lab).

### Použitie

1. Spustite aplikáciu a namierte kameru na **dobre osvetlenú rovnú plochu** (stôl, podlaha).
2. Počkajte, kým aplikácia rozpozná plochu, a umiestnite na ňu 3D model.
3. Spustite simuláciu, meňte parametre a pohybom telefónu si zariadenie prezrite zo všetkých strán.

---

## 🇬🇧 English

### About

**AR‑Lab** is a mobile application that uses **augmented reality (AR)** to project 3D models of
mechatronic devices into the user's real environment. Students can run "virtual experiments"
without being physically present in a laboratory — from home, on the way to school, or whenever
it suits them.

Just point your phone's camera at a flat surface and a 3D model of the device appears
(e.g. a hydraulic system, a flying machine, etc.). You can run the device as a simulation, change
its control parameters and observe its behaviour in real time — from any viewing angle.

The app is the output of the **AR‑Lab** activity by the **IOLab** team at **FEI STU in Bratislava**
(Institute of Automotive Mechatronics, Slovak University of Technology).

### Key features

- 🧊 **3D visualization in AR** — models of mechatronic devices placed right in your surroundings
- ▶️ **Interactive simulation** — run the device and watch its behaviour live
- 🎚️ **Parameter control** — adjust control variables and get instant visual feedback
- 🔄 **View from any angle** — walk around the model and inspect it from every side
- 🌍 **Multi‑language** — Slovak, English, Spanish

### Requirements

- **Android 7.1** (API 25) or newer
- A device supporting **Google Play Services for AR (ARCore)** —
  see the [ARCore supported devices list](https://developers.google.com/ar/devices)
- **arm64‑v8a** (64‑bit) CPU
- **Camera** access permission

### Installation (.apk)

1. Download the **recommended build (2.0)** — [`ARLab2.0.apk`](ARLab2.0.apk); see the [Builds](#-buildy--builds) table above for all builds.
2. On your phone, allow installation from unknown sources
   (*Settings → Apps → Install unknown apps*).
3. Open the downloaded `.apk` and confirm the installation.
4. On first launch, grant the app access to the **camera**.
   If **ARCore** is missing, the system will prompt you to install it from Google Play.

> 💡 An iOS version of the app is available via the official page — see [iolab.sk/activities/ar-lab](https://iolab.sk/activities/ar-lab).

### Usage

1. Launch the app and point the camera at a **well‑lit flat surface** (table, floor).
2. Wait for the app to detect the plane, then place the 3D model on it.
3. Start the simulation, change parameters and move your phone to view the device from all sides.

---

## 🛠️ Technické detaily · Technical details

| | |
|---|---|
| **Package** | `sk.fei.stu.ARLab` |
| **Verzia · Version** | 2.0 (current) · 1.0 (deprecated) · 0.0 (archived) |
| **Engine** | Unity 6 — `6000.4.7f1` (IL2CPP) · pôvodne · originally Unity 2020.3 LTS (`2020.3.24f1`) |
| **Backend · API** | `ovl.iolab.sk` (REST API) — verzie · versions 1.0 & 2.0 |
| **AR SDK** | Google ARCore (*AR Required*, Depth API) |
| **Min. Android** | 7.1 — API 25 |
| **Target Android** | API 35 |
| **ABI** | arm64‑v8a |
| **Permissions** | `CAMERA`, `INTERNET` |
| **Jazyky · Languages** | 🇸🇰 sk · 🇬🇧 en · 🇪🇸 es |

> Tento repozitár slúži na distribúciu zostaveného APK (release build).
> This repository is used to distribute the compiled APK (release build).

## 🏆 Ocenenie · Recognition

**Best Education Paper Award** — medzinárodná konferencia **exp.at'23**, Évora, Portugalsko.
*Best Education Paper Award at the **exp.at'23** international conference in Évora, Portugal.*

## 👥 Autori · Credits

**Pôvodná aplikácia · Original application**
AR‑Lab pôvodne vznikol ako **diplomová práca Matúša Pohančenika** na **FEI STU** (2021/2022) — Unity 2020.3 LTS (verzia 0.0).
*Originally created as the **master's thesis by Matúš Pohančenik** at **FEI STU** (2021/2022) — Unity 2020.3 LTS (version 0.0).*

**Migrácia & rebrand · Migration & rebrand**
Migrácia na Unity 6 a redizajn pre **IOLab** · **Ústav automobilovej mechatroniky**, **FEI STU** v Bratislave.
*Migration to Unity 6 and redesign for the **IOLab** team · **Institute of Automotive Mechatronics**, **FEI STU**, Bratislava.*

🔗 [iolab.sk](https://iolab.sk) · [iolab.sk/activities/ar-lab](https://iolab.sk/activities/ar-lab)
