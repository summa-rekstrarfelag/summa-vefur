# summa.is

Heimasíða Summu rekstrarfélags hf. Kyrrstæð HTML-síða hýst með GitHub Pages.

## Uppbygging

| Slóð | Efni |
|---|---|
| `index.html` | Forsíða (íslenska) |
| `um-summu/`, `radgjof/`, `sjodir/`, `skilmalar/` | Íslenskar síður |
| `en/`, `en/about/`, `en/services/`, `en/investment-funds/`, `en/licenses/` | Enskar síður |
| `upplysingar/`, `en/heim-english/` | Framvísanir frá gömlum slóðum |
| `skjol/` | Stefnuskjöl (PDF) með föstum heitum, t.d. `skjol/personuverndarstefna.pdf`. Ný útgáfa: skipta skránni út undir sama heiti, svo tenglar haldist |
| `assets/` | Útlit (CSS), letur, myndir |

## Breytingar

- **HTML-skrárnar eru frumgögnin.** Fyrsta útgáfan var smíðuð með skriftu sem er ekki í geymslunni. Héðan í frá er breytt beint í HTML-skránum. Haus, valmynd og fótur eru endurtekin í hverri skrá, svo breyting á þeim fer í allar síður.
- Allt sem fer á grein `main` birtist á summa.is innan fárra mínútna. Yfirfara breytingar áður en þær eru vistaðar.
- Allur texti er beint í HTML-skránum. Lítil textabreyting: opna skrána á github.com → blýantur (Edit) → *Commit changes*. Síðan uppfærist sjálfkrafa eftir 1–2 mínútur.
- Íslensk og ensk útgáfa eru aðskildar skrár. Muna að breyta báðum.
- Starfsmannamyndir: `assets/img/starfsfolk/`, 600×800 px, svarthvítar.

## Letur

Jost (SIL Open Font License 1.1, sjá `assets/fonts/OFL-Jost.txt`). Futura er ekki notuð þar sem ekkert vefleyfi liggur fyrir.

## Hýsing

Örugg afritun ehf. hýsir síðuna á summa.is. Vefþjónninn sækir nýjustu útgáfuna sjálfkrafa úr þessari geymslu (grein `main`), svo breytingar sem gerðar eru hér birtast á summa.is án aðkomu hýsingaraðila. DNS fyrir summa.is er hjá 1984 og vísar á vefþjón Öruggrar afritunar.

## Áður en síðan fer á summa.is

- [x] PDF-skjöl í `skjol/` (sömu útgáfur og á gamla vefnum, júní 2024 – staðfesta að þær séu gildandi).
- [x] Starfsmannatextar og myndir, forsíðutexti.
- [x] Forskoðunarstilling fjarlægð. Allar síður vísa á summa.is sem rétta slóð (canonical).
- [ ] Örugg afritun tengir vefþjóninn við geymsluna og lokar WordPress.
- [ ] Slökkva á GitHub Pages-forskoðun eftir opnun (*Settings → Pages*).
