|![BYLICKILABS](https://img.shields.io/badge/Protected%20by-BYLICKILABS-14f1ff?style=for-the-badge) |
|---|

|![protect](https://github.com/user-attachments/assets/a6701c1e-1b3f-4cfc-8508-c90a3964aff3)|
|---|

| ![Platform: Web](https://img.shields.io/badge/platform-Web-blue?style=for-the-badge&logo=html5) | ![Language: JavaScript](https://img.shields.io/badge/JavaScript-Protect-yellow?logo=javascript&logoColor=white&style=for-the-badge) | ![Opera GX Tested](https://img.shields.io/badge/Opera%20GX-Tested-red?logo=opera&logoColor=white&style=for-the-badge) | ![License: All Rights Reserved](https://img.shields.io/badge/license-All%20Rights%20Reserved-important?style=for-the-badge) | ![Client-Side](https://img.shields.io/badge/Client--Side-100%25-success?style=for-the-badge) |
|---|---|---|---|---|

| ![No Open Source](https://img.shields.io/badge/open%20source-no-red?style=for-the-badge) | ![Chrome](https://img.shields.io/badge/Chrome-✔-green?logo=google-chrome&logoColor=white&style=for-the-badge) | ![Firefox](https://img.shields.io/badge/Firefox-✔-orange?logo=firefox-browser&logoColor=white&style=for-the-badge) | ![Edge](https://img.shields.io/badge/Edge-✔-0078d7?logo=microsoft-edge&logoColor=white&style=for-the-badge) |
|---|---|---|---|

---

## Inhaltsverzeichnis

- [DE](#de)
- [EN](#en)

<br>

---

<br>

## DE

# Website Content Protection Scripts

Dieses Repository enthält zwei effektive Schutzmechanismen zur Absicherung Ihrer HTML- oder PHP-Webseiten gegen das unerwünschte Kopieren von Inhalten, 
das Markieren von Text sowie das Auslesen und Manipulieren des Quellcodes durch Browser-Entwicklertools.

## 1. Copy/Paste- und Auswahl-Schutz (Inline Script)

Fügen Sie folgenden Code **direkt unterhalb des `<body>`-Tags** Ihrer `index.html` oder `index.php` ein:

```yarn
<script>
(function(){var _0x1a3b=["\x72\x65\x74\x75\x72\x6E\x20\x66\x61\x6C\x73\x65","\x6F\x6E\x73\x65\x6C\x65\x63\x74\x73\x74\x61\x72\x74","\x6F\x6E\x6D\x6F\x75\x73\x65\x64\x6F\x77\x6E","\x6F\x6E\x63\x6C\x69\x63\x6B","\x73\x69\x64\x65\x62\x61\x72"];
function disableselect(_0x2929x2){return false;}function reEnable(){return true;}document[_0x1a3b[1]]=new Function(_0x1a3b[0]);if(window[_0x1a3b[4]]){document[_0x1a3b[2]]=disableselect;document[_0x1a3b[3]]=reEnable;}document.addEventListener
('contextmenu',function(e){e.preventDefault();});})();
</script>
```

- **Effekt:**  
  - Verhindert das Markieren von Text.
  - Blockiert das Rechtsklick-Kontextmenü.

<br>

---

<br>

## 2. Erweiterter Seitenschutz (`protect.js`)

Um Ihre Seite zusätzlich gegen Entwicklertools, Speichern und Quelltextanzeige zu schützen, binden Sie das mitgelieferte Script wie folgt ein, **am besten vor dem schließenden `</body>`-Tag**:

```yarn
<script src="protect.js"></script>
```

**Schutzfunktionen von `protect.js`:**
- Blockiert die gängigen Tastenkombinationen zur Öffnung von Dev Tools (z.B. F12, Strg+Shift+I/J/C, Strg+U, Strg+S).
- Verhindert das Öffnen des Kontextmenüs.
- Erschwert das Auslesen des Codes via Entwicklertools.

<br>

---

<br>

## Hinweise

- **Kombinieren Sie beide Methoden** für optimalen Schutz Ihrer Webinhalte.
- Diese Mechanismen stellen einen technischen Kopierschutz dar.
- Testen Sie die Funktionen nach der Integration in verschiedenen Browsern.

<br>

---

<br>
Installation

1. Fügen Sie das Inline-Script direkt nach `<body>` in Ihre HTML- oder PHP-Datei ein.
2. Kopieren Sie die Datei `protect.js` in das Projektverzeichnis.
3. Binden Sie `<script src="protect.js"></script>` vor dem schließenden `</body>` ein.

<br>

---

<br>

## EN

# Website Content Protection Scripts

This repository contains two effective protection mechanisms to secure your HTML or PHP websites against unwanted copying of content, text highlighting, and the reading and manipulation of source code by browser developer tools.

## 1. Copy/Paste and Selection Protection (Inline Script)

Insert the following code **directly below the `<body>` tag** of your `index.html` or `index.php`:

```yarn
<script>
(function(){var _0x1a3b=["\x72\x65\x74\x75\x72\x6E\x20\x66\x61\x6C\x73\x65","\x6F\x6E\x73\x65\x6C\x65\x63\x74\x73\x74\x61\x72\x7 4","\x6F\x6E\x6D\x6F\x75\x73\x65\x64\x6F\x77\x6E","\x6F\x6E\x63\x6C\x69\x63\x6B","\x73\x69\x64\x65\x62\x61\x72"];
function disableselect(_0x2929x2){return false;}function reEnable(){return true;}document[_0x1a3b[1]]=new Function(_0x1a3b[0]);if(window[_0x1a3b[4]]){document[_0x1a3b[2]]=disableselect;document[_0x1a3b[3]]=reEnable;}document.addEventListener
('contextmenu',function(e){e.preventDefault();});})();
</script>
```

- **Effect:**
- Prevents text from being selected.
- Blocks the right-click context menu.

<br>

---

<br>

## 2. Advanced Page Protection (`protect.js`)

To further protect your page against developer tools, saving, and source code viewing, include the included script as follows, **preferably before the closing `</body>` tag**:

```yarn
<script src="protect.js"></script>
```

**Protection features of `protect.js`:**
- Blocks common keyboard shortcuts for opening Dev Tools (e.g., F12, Ctrl+Shift+I/J/C, Ctrl+U, Ctrl+S).
- Prevents the context menu from opening.
- Makes it difficult to read the code via developer tools.

<br>

---

<br>

## Notes

- **Combine both methods** for optimal protection of your web content.
- These mechanisms represent technical copy protection.
- Test the functions in different browsers after integration.

<br>

---

<br>

## Installation

1. Insert the inline script directly after `<body>` in your HTML or PHP file.
2. Copy the `protect.js` file to the project directory.
3. Include `<script src="protect.js"></script>` before the closing `</body>`.

---
