# Portfolio

**Wir werden eine "Portfolio" Seite programmieren am ende sieht diese etwa so aus**

![WebSite](https://craftingcloud.de/45/portfolio.png)

---
## Extensions Installieren

Zuerst werden wir eine Extension installieren damit du deinen Code auch als Website sehen kannst.

Dafür klickst du links auf Extensions

![Extensions](https://craftingcloud.de/45/extensionss.PNG)

Dann suchst du nach "Live preview" und installierst dieses Extension.

![Extensions](https://craftingcloud.de/45/live.PNG)

---
## Los gehts!

Erstelle eine neue Datei und nenne sie *DeinName.html*

In Visual Studio Code kannst du indem du ein ! schreibst und dann Enter drückst ganz einfach anfangen.

Dann solltest du deisen Code haben
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
---
### CSS Verlinken
Zusätzlich müssen wir noch unsere CSS Datei verlinken, das machst du indem du **link** eingibst und dann Enter drückst. Danach musst noch den **href** auf **style.css** ändern und die *style.css* Datei von **Teams Kanal Mi > Dateien**
herunterladen
``` html
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
--> <link rel="stylesheet" href="style.css">
    <title>Document</title>
```
---
## Preview Öffnen

Du kannst den Preview mit dem Symbol oben rechts *(Das Buch mit der Lupe)*

---

Begib dich nun in den **Body** Tag

Als nächstes fügst du einen div Tag hinzu, da dieser eine Klasse hat kannst du einfach **div.container** schreiben und dann Enter drücken.
``` html
<body>
    <div class="container">

    </div>
</body>
```
---
Dann fügst du einen **nav** tag hinzu in diesen fügst du dann einen div mit der Klasse **logo** ein.
``` html
<body>
    <div class="container">
--->    <nav>
--->        <div class="logo">

--->        </div>
--->    </nav>
    </div>
</body>
```
---
Dann einen div mit der Klasse **content** und darunter einen div mit der Klasse **link**.
``` html
<body>
    <div class="container">
        <nav>
            <div class="logo">

            </div>
        </nav>

--->    <div class="content">

--->    </div>
--->    <div class="link">

--->    </div>
    </div>
</body>

```
---
Füge jetzt im div **Logo** einen **a** tag hinzu.
``` html
<body>
    <div class="container">
        <nav>
            <div class="logo">
--->            <a href="#">Port<span>folio</span></a>
            </div>
        </nav>

        <div class="content">

        </div>
        <div class="link">

        </div>
    </div>
</body>
```
---
Füge jetzt im **content** div folgendes ein.
``` html
<body>
    <div class="container">
        <nav>
            <div class="logo">
                <a href="#">Port<span>folio</span></a>
            </div>
        </nav>

        <div class="content">
--->        <h2>Line 1<br>Line 2</h2>
--->        <p>Line 1<br>Line 2</p>
        </div>
        <div class="link">

        </div>
    </div>
</body>
```
---
Füge jetzt im **link** div einen **a** tag hinzu mit der Klasse **hire**
``` html
<body>
    <div class="container">
        <nav>
            <div class="logo">
                <a href="#">Port<span>folio</span></a>
            </div>
        </nav>

        <div class="content">
            <h2>Line 1<br>Line 2</h2>
            <p>Line 1<br>Line 2</p>
        </div>
        <div class="link">
--->        <a href="#" class="hire">Button</a>
        </div>
    </div>
</body>
```
---
## Überprüfe jetzt bitte ob dein Code genau so aussieht
Falls nicht überarbeite ihn jetzt. Wenn du fertig bist kannst du die Farbe noch ändern im div mit der Klasse **container** fügst du einfach *-blue* oder *-red* hinzu.
Beispiel:
```html
<body>
    <div class="container-red"> <!--Roter Hintergrund
```
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeinName</title>
</head>
<body>
    <div class="container">
        <nav>
            <div class="logo">
                <a href="#">Port<span>folio</span></a>
            </div>
        </nav>

        <div class="content">
            <h2>Line 1<br>Line 2</h2>
            <p>Line 1<br>Line 2</p>
        </div>
        <div class="link">
            <a href="#" class="hire">Button</a>
        </div>
    </div>
</body>
</html>
```
---
