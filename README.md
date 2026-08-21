# Project - Verkkosivusto

Verkkosivusto, joka on rakennettu **Jekyll**-alustalla ja käyttöönottua **GitHub Pages**:issa.

## 🚀 Ominaisuudet

- Automatisoitu rakentaminen ja käyttöönotto GitHub Actions:lla
- Yksinkertainen rakenne - muokkaa vain Markdown-tiedostoja
- Responsive design
- SEO-optimoitu

---

## 💻 Koodauksesta

### Mitä on koodaus?

Koodaus on ohjeita antamista tietokoneelle siitä, mitä sen tulee tehdä. Se on kuin resepti, joka kertoo vaihe vaiheelta, kuinka tehdään jotakin.

![Koodaus](https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&h=400&fit=crop)

### Koodauksen perusteet

**Koodaus sisältää:**
- 📝 Muuttuujat - tiedon säilytys
- 🔄 Silmukat - toistaminen
- ❓ Ehdot - päätöksenteko
- 🔧 Funktiot - uudelleenkäytettävät koodin pätkät

### Jekyll ja Markdown

Tämä sivusto käyttää **Markdown**-kielistä sisällön kirjoittamiseen:

```markdown
# Otsikko
## Alaotsikko
**Lihavointi**
*Kursivointi*
- Lista
- Kohta
```

### HTML ja CSS

Jekyll muuntaa Markdown-tiedostot HTML:ksi, jota selaimet voivat näyttää:

```html
<h1>Otsikko</h1>
<p><strong>Lihavointi</strong></p>
```

```css
h1 {
  color: #333;
  font-size: 2em;
}
```

---

## 🛠️ Asennus

### Paikallinen kehitys

```bash
git clone https://github.com/kseniia679-png/project.git
cd project
bundle install
bundle exec jekyll serve
```

Sivusto on nyt käytettävissä osoitteessa: `http://localhost:4000`

### Verkossa

Sivusto otetaan automaattisesti käyttöön kun pushaat `main` branchiin.

**Sivusto:** [https://kseniia679-png.github.io/project](https://kseniia679-png.github.io/project)

---

## ✏️ Sisällön muokkaaminen

- Muokkaa `index.md` pääsivua
- Luo uusia sivuja juurihakemistoon `.md` tiedostoina
- Lisää blogipostaukset `_posts/` kansioon

### Esimerkki uudesta sivusta

```markdown
---
layout: page
title: Minusta
permalink: /about/
---

# Tietoja minusta

Kirjoita tähän mitä haluat!
```

---

## 🎨 Teeman muuttaminen

Muokkaa `_config.yml`:ää vaihtaaksesi teemaa:

```yaml
theme: minima  # Kokeile: jekyll-theme-cayman, jekyll-theme-slate
```

---

## 📝 Lisenssi

MIT

---

**Aloita koodaamista nyt!** 🚀 Muokkaa tiedostoja, pushaa muutokset ja katso sivuston päivittyvän automaattisesti.
