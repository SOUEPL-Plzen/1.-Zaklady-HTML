# Webové technologie - HTML
Pro lepší pochopení HTML tagu a syntaxe doporučuji si stahnout repozitář a stránky s prohlédnout a spusit. V headu najdete i tag pro style, ten prosím neměňte a nevšímejte si ho, slouží pro vizualizaci stránky a lepší pochopení html tagu apod.

## V čem programujeme?

# Práce s Visual Studio Code (VSC)

## Co je Visual Studio Code?
**Visual Studio Code (VSC)** je populární editor kódu, který je zdarma a podporuje různé programovací jazyky, včetně HTML, CSS, JavaScriptu a dalších. Poskytuje funkce jako integrovaný terminál, rozšíření pro různé nástroje a snadné použití.

---

## Jak nainstalovat Visual Studio Code:
1. Navštivte oficiální webové stránky [Visual Studio Code](https://code.visualstudio.com/).
2. Klikněte na tlačítko **Download** a vyberte verzi pro váš operační systém (Windows, macOS, Linux).
3. Stáhněte instalační soubor a spusťte instalaci podle pokynů na obrazovce.
4. Po dokončení instalace spusťte Visual Studio Code.

---

## Kde co je ve Visual Studio Code
Po otevření Visual Studio Code se zobrazí následující hlavní části:
- **Postranní panel**: Obsahuje ikony pro otevírání souborů, rozšíření a dalších funkcí.
- **Editor**: Zobrazuje aktuálně otevřené soubory.
- **Status bar**: Zobrazuje informace o otevřeném souboru (jazyk, kódování).
- **Terminál**: Spodní část, kde můžete spouštět příkazy.

---

## Jak otevřít složku:
1. Klikněte na **File** (Soubor) v horním menu.
2. Vyberte **Open Folder...** (Otevřít složku).
3. Zvolte složku s vaším projektem a klikněte na **Select Folder**.
4. Soubory ve složce se zobrazí v postranním panelu (Explorer).

---

## Jak vytvořit nový HTML dokument:
1. Klikněte na **File** (Soubor) > **New File** (Nový soubor).
2. Pro uložení klikněte na **File** > **Save As** a zadejte název souboru s příponou `.html` (např. `index.html`).
3. Nyní můžete psát kód HTML.

## Jak otevřít terminál:
Visual Studio Code obsahuje integrovaný terminál, který můžete použít ke spouštění příkazů přímo z editoru.

1. Klikněte na **Terminal** v horním menu.
2. Vyberte možnost **New Terminal** (Nový terminál).
3. Terminál se zobrazí v dolní části okna. Můžete v něm spouštět různé příkazy, například Git, Node.js nebo příkazy operačního systému.

---

## Jak otevřít nové okno:
Pro práci na více projektech současně je možné otevřít nové okno ve Visual Studio Code.

1. Klikněte na **File** > **New Window** (Nové okno).
2. Otevře se nové prázdné okno, kde můžete otevřít další projekt.

---

## Jak nastavit Visual Studio Code do češtiny:
Visual Studio Code podporuje různé jazykové balíčky, včetně češtiny.

1. Klikněte na ikonu **Extensions** (Rozšíření) na levém postranním panelu.
2. Do vyhledávacího pole zadejte **Czech Language Pack**.
3. Klikněte na tlačítko **Install** u balíčku **Czech Language Pack for Visual Studio Code**.
4. Po instalaci změňte jazyk v **File** > **Preferences** > **Settings** > **Locale** a vyberte češtinu.

---

## Instalace rozšíření Live Server:

**Live Server** umožňuje zobrazit změny v HTML a CSS v reálném čase.

### Jak nainstalovat Live Server:
1. Klikněte na **Extensions** (Rozšíření) na levém panelu nebo stiskněte `Ctrl+Shift+X`.
2. Do vyhledávacího pole napište **Live Server**.
3. Vyberte rozšíření **Live Server** od Ritwick Dey a klikněte na **Install**.

### Jak používat Live Server:
1. Otevřete soubor HTML, který chcete zobrazit.
2. Klikněte pravým tlačítkem myši na soubor a zvolte **Open with Live Server**.
3. Váš soubor se otevře v prohlížeči, kde uvidíte změny při každém uložení souboru.

---

## Kde hledat a instalovat další rozšíření:
Visual Studio Code nabízí širokou škálu rozšíření, která rozšiřují funkce editoru. Následující kroky vám ukážou, jak najít a nainstalovat nové rozšíření.

1. Klikněte na ikonu **Extensions** (Rozšíření) na levém panelu.
2. Do vyhledávacího pole napište název požadovaného rozšíření nebo klíčové slovo (např. „HTML“, „CSS“, „Python“).
3. Klikněte na tlačítko **Install** vedle rozšíření, které chcete nainstalovat.

Po instalaci se rozšíření automaticky aktivuje a přidá nové funkce do vašeho editoru.

## Co je HTML?
HTML (HyperText Markup Language) je značkovací jazyk, který slouží ke strukturování obsahu webových stránek. Umožňuje nám definovat, jak se mají jednotlivé prvky (texty, obrázky, odkazy, formuláře) zobrazovat v prohlížeči.

## Kde se mohu ještě učit? 
Pokud se chcete dozvědět více o HTML, doporučuji následující zdroje:

- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/default.asp): Jednoduchý a přehledný návod pro začátečníky.
- [YouTube - HTML Course](https://www.youtube.com/watch?v=kbLBBI5hEK4&list=PLQ8x_VWW6AkvCiDzMEI5K9jW_1rsV9PTf): Video kurz o základech HTML.
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML): Komplexní dokumentace a referenční příručka pro HTML.



## Párový a Nepárový Tag
- **Párový tag**: Tento tag má otevírací a uzavírací část, např. `<p></p>`, kde první část definuje začátek elementu a druhá jeho konec.
- **Nepárový tag**: Tento tag má pouze otevírací část a automaticky se uzavírá. Například `<img>` nebo `<input>`.

## Struktura HTML Dokumentu
HTML dokument se skládá ze tří základních částí:
1. **`<!DOCTYPE html>`**: Deklarace dokumentu, která říká prohlížeči, že se jedná o HTML5 dokument.
2. **`<html>`**: Kořenový element obsahující všechny další elementy.
3. **`<head>` a `<body>`**: Část `<head>` obsahuje metadata, zatímco `<body>` obsahuje hlavní obsah stránky.

### Příklad základní HTML struktury:
```html
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Název stránky</title>
</head>
<body>
  <h1>Nadpis stránky</h1>
  <p>Obsah stránky.</p>
</body>
</html>
```

## Syntaktická pravidla HTML
- HTML je tvořeno tagy (značkami), které jsou uzavřené v ostrých závorkách, např. `<p>Text</p>`.
- **Otevírací tag** definuje začátek elementu, např. `<h1>`.
- **Uzavírací tag** obsahuje lomítko a uzavírá element, např. `</h1>`.
- **Nepárové tagy** se samy uzavírají a nevyžadují uzavírací tag, např. `<img />`.

## Atributy
- Atributy přidávají tagům další informace, např. vzhled nebo funkčnost.
- **`class`**: Slouží k definování skupiny prvků se stejným stylem nebo chováním.
- **`id`**: Unikátní identifikátor pro jednotlivé prvky na stránce.

## Použité HTML Tagy
Nyní si ukážeme tagy, které jsou v repozitáři

### Párové tagy
- `<html>`: Kořenový element HTML dokumentu.
- `<head>`: Sekce obsahující metadata.
- `<body>`: Hlavní část obsahující obsah stránky.
- `<header>`: Hlavička stránky nebo sekce.
- `<main>`: Hlavní obsah stránky.
- `<footer>`: Patička stránky.
- `<section>`: Logický oddíl stránky.
- `<article>`: Samostatný obsah (např. článek).
- `<aside>`: Vedlejší obsah (např. boční panel).
- `<figure>`: Skupina obsahu (např. obrázek).
- `<figcaption>`: Popisek obrázku v rámci `<figure>`.
- `<details>`: Skládací obsah.
- `<summary>`: Nadpis skládacího obsahu v `<details>`.
- `<h1>` až `<h5>`: Nadpisy různých úrovní.
- `<p>`: Odstavec.
- `<nav>`: Navigační menu stránky.
- `<a>`: Hypertextový odkaz.

### Nepárové tagy
- `<img>`: Obrázek.
- `<input>`: Interaktivní prvek formuláře.

#### Input tagy
`<input>` má různé typy, které určují, jaký druh vstupu uživatel poskytne:
- `text`: Textové pole.
- `password`: Pole pro heslo.
- `checkbox`: Zaškrtávací políčko.
- `radio`: Radiobutton (výběr jedné možnosti).
- `submit`: Tlačítko pro odeslání formuláře.
- `reset`: Tlačítko pro reset formuláře.
- `email`: Pole pro emailovou adresu.
- `file`: Výběr souboru.
- `date`: Výběr data.
- `color`: Výběr barvy.


## Semantická Struktura HTML

Semantická HTML struktura je založena na používání značek, které jasně definují význam obsahu. Tyto značky nejenže usnadňují čtení a správu kódu, ale také zlepšují SEO a přístupnost. Mezi hlavní semantické tagy patří:

- `<header>`: Hlavička stránky nebo sekce.
- `<main>`: Hlavní obsah stránky.
- `<footer>`: Patička stránky.
- `<article>`: Samostatný obsah jako blogový příspěvek.
- `<section>`: Logický oddíl stránky.

Používání těchto tagů přispívá ke srozumitelnější struktuře webu pro uživatele i vyhledávače.

```html
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Semantická Struktura</title>
</head>
<body>

  <!-- Hlavička stránky obsahuje nadpis a navigaci -->
  <header>
    <h1>Moje Webová Stránka</h1>
    <nav>
      <ul>
        <li><a href="#home">Domů</a></li>
        <li><a href="#about">O nás</a></li>
        <li><a href="#contact">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hlavní obsah stránky -->
  <main>
    <article>
      <h2>Článek o HTML</h2>
      <p>Tento článek vysvětluje, jak používat semantické tagy v HTML.</p>
    </article>

    <section>
      <h3>Výhody Semantických Tagů</h3>
      <p>Semantické tagy zlepšují SEO a přístupnost stránek.</p>
    </section>
  </main>

  <!-- Patička stránky -->
  <footer>
    <p>&copy; 2024 Moje Webová Stránka</p>
  </footer>

</body>
</html>
```


## Proč si komentovat kód?
Komentování kódu je důležité pro lepší čitelnost a údržbu. Komentáře vám nebo ostatním programátorům pomáhají pochopit, co určitá část kódu dělá. Umožňují snadno porozumět účelu jednotlivých částí, což usnadňuje další vývoj.

### Jak psát komentáře v HTML:

```html
<!-- Toto je komentář v HTML -->
```


