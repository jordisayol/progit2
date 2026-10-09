# Traducció de Pro Git (2a edició)

Les traduccions es gestionen de manera descentralitzada. Cada equip de traducció manté el seu propi projecte. Cada traducció es troba en el seu propi repositori; l'equip de Pro Git simplement incorpora els canvis i els integra al lloc web https://git-scm.com quan estan a punt.

## Orientacions generals per traduir Pro Git

Pro Git és un llibre sobre una eina tècnica; per tant, traduir-lo és més complex que fer una traducció no tècnica.

A continuació, trobareu algunes pautes per ajudar-vos en el procés:
* Abans de començar, llegiu tot el llibre Pro Git en anglès per conèixer-ne el contingut i familiaritzar-vos amb l'estil utilitzat.
* Assegureu-vos de tenir un bon coneixement pràctic de Git per poder explicar els termes tècnics adequadament.
* Manteniu un estil i un format coherents en la traducció.
* Assegureu-vos de llegir i entendre els conceptes bàsics del format [Asciidoc](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/). No seguir la sintaxi d'Asciidoc pot provocar problemes en la generació o compilació dels fitxers PDF, EPUB i HTML necessaris per al llibre.

## Traducció del llibre a un altre idioma

### Col·laborar en un projecte existent

* Comproveu si ja existeix un projecte a la taula següent.
* Aneu a la pàgina del projecte a GitHub.
* Obriu una incidència (*issue*), presenteu-vos i pregunteu en què podeu ajudar.

| Idioma     | Pàgina de GitHub     |
| :------------- | :------------- |
| Àrab | [progit2-ar/progit2](https://github.com/progit2-ar/progit2) |
| Bielorús  | [progit/progit2-be](https://github.com/progit/progit2-be) |
| Búlgar | [progit/progit2-bg](https://github.com/progit/progit2-bg) |
| Txec    | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs) |
| Anglès | [progit/progit2](https://github.com/progit/progit2) |
| Espanyol | [progit/progit2-es](https://github.com/progit/progit2-es) |
| فارسی | [progit2-fa/progit2](https://github.com/progit2-fa/progit2) |
| Francès | [progit/progit2-fr](https://github.com/progit/progit2-fr) ​​|
| Alemany | [progit/progit2-de](https://github.com/progit/progit2-de) |
| Ελληνικά | [progit2-gr/progit2](https://github.com/progit2-gr/progit2) |
| indonesi | [progit/progit2-id](https://github.com/progit/progit2-id) |
| Italià | [progit/progit2-it](https://github.com/progit/progit2-it) |
| 日本語 | [progit/progit2-ja](https://github.com/progit/progit2-ja) |
| 한국어 | [progit/progit2-ko](https://github.com/progit/progit2-ko) |
| Македонски | [progit2-mk/progit2](https://github.com/progit2-mk/progit2) |
| Bahasa Melayu| [progit2-ms/progit2](https://github.com/progit2-ms/progit2) |
| Holanda | [progit/progit2-nl](https://github.com/progit/progit2-nl) |
| Polski | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl) |
| Português (Brasil) | [progit/progit2-pt-br](https://github.com/progit/progit2-pt-br) |
| Русский | [progit/progit2-ru](https://github.com/progit/progit2-ru) |
| Eslovenščina | [progit/progit2-sl](https://github.com/progit/progit2-sl) |
| Српски | [progit/progit2-sr](https://github.com/progit/progit2-sr) |
| Svenska | [progit2-sv/progit2](https://github.com/progit2-sv/progit2) |
| Tagalog | [progit2-tl/progit2](https://github.com/progit2-tl/progit2) |
| Türkçe | [progit/progit2-tr](https://github.com/progit/progit2-tr) |
| Українська| [progit/progit2-uk](https://github.com/progit/progit2-uk) |
| Ўзбекча | [progit/progit2-uz](https://github.com/progit/progit2-uz) |
| 简体中文 | [progit/progit2-zh](https://github.com/progit/progit2-zh) |
| 正體中文 | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw) |

### Començar una nova traducció

Si no hi ha cap projecte per al teu idioma, pots començar la teva pròpia traducció.

Basat en la segona edició del llibre, disponible [aquí](https://github.com/progit/progit2). Per fer-ho:
1. Tria el [codi ISO 639](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) correcte per al teu idioma. 
1. Crea una [organització de GitHub](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch), per exemple: `progit2-[el_teu_codi]`, a GitHub. 
1. Crea un projecte anomenat `progit2`. 
1. Copia l'estructura de progit/progit2 (aquest projecte) al teu projecte i comença a traduir.

### Actualitzar l'estat de la traducció

A https://git-scm.com, les traduccions es divideixen en tres categories. Un cop hagis assolit un d'aquests nivells, contacta amb els responsables de https://git-scm.com/ perquè puguin incorporar els canvis.

| Categoria | Estat de finalització |
| :------------- | :------------- |
| Traducció iniciada per a | Introducció traduïda; poca cosa més. |
| Traduccions parcials disponibles a | s'ha traduït fins al capítol 6. |
| Traducció completa disponible a | el llibre està (gairebé) traduït completament. |

## Integració contínua amb GitHub Actions

GitHub Actions és un servei d'[integració contínua](https://en.wikipedia.org/wiki/Continuous_integration) que s'integra amb GitHub. GitHub Actions s'utilitza per a garantir que una sol·licitud d'integració (*pull request*) no trenqui la compilació. GitHub Actions també pot proporcionar versions compilades del llibre.

La configuració de GitHub Actions es troba al directori `.github/workflows`; si incorpores la branca `main` del repositori principal, ja disposaràs d'aquesta funcionalitat automàticament.
Tanmateix, si has creat el repositori de la traducció fent un *fork* del repositori principal, cal fer un pas addicional (si no has fet un *fork*, pots saltar-te aquesta part).
GitHub parteix de la base que els *forks* s'utilitzaran per contribuir al repositori d'origen; per tant, hauràs d'anar a la pestanya "Actions" del teu repositori derivat i fer clic al botó "I understand my workflows" per permetre l'execució de les accions.

## Configuració d'una cadena de publicació per a llibres electrònics

Aquesta és una tasca tècnica; contacta amb @jnavila per començar amb la publicació en format EPUB.

## Més enllà de Pro Git

Traduir el llibre és el primer pas. Un cop acabat, pots plantejar-te traduir la interfície d'usuari del mateix Git.

Aquesta tasca requereix coneixements tècnics de l'eina més avançats que els necessaris per al llibre. És d'esperar que, després d'haver traduït tot el contingut del llibre, entenguis els termes que utilitza l'aplicació. Si et veus capacitat tècnicament per assumir la tasca, trobaràs el repositori [aquí](https://github.com/git-l10n/git-po) i només caldrà que segueixis la [guia](https://github.com/git-l10n/git-po/blob/master/po/README.md).

Tingues en compte, però, que:

* hauràs d'utilitzar eines més específiques per gestionar els fitxers de localització `.po` (com ara editar-los amb [poedit](https://poedit.net/)) i per fusionar-los. És possible que hagis de compilar el Git per verificar la teva feina. 
* calen coneixements bàsics sobre com es tradueixen les aplicacions, un procés força diferent de la traducció de llibres. El projecte principal de Git utilitza [procediments](https://github.com/git-l10n/git-po/blob/master/Documentation/SubmittingPatches) més estrictes per acceptar contribucions; assegura't de complir-los.
