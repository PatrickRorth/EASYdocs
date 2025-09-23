# Markdown Guide

---

## Overskrifter
```md
# H1 (stort kapitel)
## H2 (sektion)
### H3 (undersektion)
#### H4 (sjældent brugt)
```

# H1 eksempel
## H2 eksempel
### H3 eksempel
#### H4 eksempel
---

## Tekstformatering
```md
**Fed tekst**
*Kursiv tekst*
~~Gennemstreget~~
`Inline kode`
> Citat / note
```

**Fed tekst**  
*Kursiv tekst*  
~~Gennemstreget~~  
`Inline kode`

> Dette er et eksempel på et citat.

---

## Lister
```md
- Punkt 1
- Punkt 2
  - Underpunkt

1. Første
2. Anden
   1. Underpunkt

- [x] Done
- [ ] Ikke færdig
```

- Punkt 1
- Punkt 2
  - Underpunkt

1. Første
2. Anden
   1. Underpunkt

- [x] Done
- [ ] Ikke færdig

---

## Links og billeder
```md
[Et link](https://blackside.dk)
![Et billede](./screenshot.png)
```

[Et link](https://blackside.dk)  
![Et billede](https://placekitten.com/300/150)

---

## Kodeblokke
```md
```js
function hello() {
  console.log("Hej fra Blackside Docs");
}
```

```csharp
public class Game {
    public void Start() { }
}
```

```powershell
Write-Host "Hello World"
```
```

```js
function hello() {
  console.log("Hej fra Blackside Docs");
}
```

```csharp
public class Game {
    public void Start() { }
}
```

```powershell
Write-Host "Hello World"
```

---

## Tabeller
```md
| Feature        | Status   | Note          |
|----------------|----------|---------------|
| Multiplayer    | Planned  | Prototype WIP |
| Controller     | Yes      | Full support  |
| Pay2Win        | ❌       | Never!        |
```

| Feature     | Status  | Note          |
|-------------|---------|---------------|
| Multiplayer | Planned | Prototype WIP |
| Controller  | Yes     | Full support  |
| Pay2Win     | ❌      | Never!        |

---

## Horisontal linje
```md
---
```

---

---

## Interne links
```md
## Installation
Læs mere i [Konfiguration](#konfiguration)

## Konfiguration
Her starter konfigurations-sektionen
```

---

## Advarsler / noter
```md
> ⚠️ **Advarsel:** Eksperimentel feature.
> ℹ️ **Info:** Husk at commit'e dine ændringer.
```

> ⚠️ **Advarsel:** Eksperimentel feature.  
> ℹ️ **Info:** Husk at commit'e dine ændringer.

---

## Kombineret eksempel
```md
# Getting Started

Velkommen til **BLACKSIDE Docs** 🎮

---

## Installation
1. Klon repoet
2. Kør `npm install`
3. Start dev-serveren
```
```bash
npm run dev
```

---

## Features
- [x] Singleplayer
- [ ] Multiplayer
- [ ] DLC

| Modul   | Status  |
|---------|---------|
| Core    | ✅      |
| Combat  | 🔄      |
| UI      | 🛠️      |