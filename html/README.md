# Solar Cargo System

## Projekta apraksts

**Solar Cargo** ir vienkārša tīmekļa lietotne, kas demonstrē kravu konteineru pārvaldības sistēmas saskarni. Sistēma attēlo, kā tiek izsekoti kravas konteineri, kas pārvadā minerālus un resursus starp dažādām bāzēm.


## Funkcionalitāte

Projektā ir šādas lapas:

| Lapa | Fails | Apraksts |
|---|---|---|
| Sākums | `index.html` | Ievadlapa ar informāciju par sistēmu un tās lietotāju lomām (dispečers, noliktavas operators, tirdzniecības pārstāvis). |
| Konteineri | `konteineri.html` | Konteineru saraksts tabulas veidā (ID, minerāls, izcelšanās bāze, galamērķa bāze, statuss) un forma jauna konteinera pievienošanai. |
| Pievienot konteineru | `add-container.html` | Atsevišķa forma jauna konteinera datu ievadei. |
| Statistika | `statistika.html` | Sistēmas kopsavilkuma statistika (konteineru un lietotāju skaits). |

Visās lapās ir navigācijas izvēlne, kas ļauj pārvietoties starp sadaļām, un vienots stils, kas definēts failā `style.css`.

## Kā palaist projektu

1. Lejupielādē vai noklonē repozitoriju:
   ```
   git clone https://github.com/ArtursJeske/Skola-HTML-projekts.git
   ```
2. Atver mapi `html`.
3. Atver failu `index.html` ar pārlūkprogrammu

Lapa ir statiska, tāpēc nav nepieciešami papildus rīki.

## Publicēšanas informācija

Projekta kods tiek glabāts GitHub repozitorijā:

[Github links](https://github.com/ArtursJeske/Skola-HTML-projekts)

[Weblapas paraugs](http://ajeske.mywebcommunity.org)

[Bezmaksas Hostings](http://elatvia.net/)

### Kā publicēt elatvia.net hostingā

1. Izveido bezmaksas kontu [elatvia.net](http://elatvia.net/) mājaslapā un piesakies savā kontā.
2. Kontroles panelī (cPanel) atrodi sadaļu **File Manager** (Failu pārvaldnieks) un atver mapi `public_html` — tā ir saknes mape, no kuras tiek apkalpota mājaslapa.
3. Augšupielādē visus projekta failus (`index.html`, `konteineri.html`, `add-container.html`, `statistika.html`, `style.css`) tieši mapē `public_html`.
4. Pārliecinies, ka galvenā lapa ir nosaukta `index.html` — tā automātiski atvērsies, ievadot domēna adresi pārlūkā.


## Autors

**Artūrs Jeske**

