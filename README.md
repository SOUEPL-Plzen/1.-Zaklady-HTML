# HTML Struktura a Syntaxe

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
