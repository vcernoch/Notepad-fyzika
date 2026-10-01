# Fyzikální sešit

Jednoduchý poznámkový blok pro fyzikální vzorce, značky veličin, vektory a jednotky.
Běží na **https://vcernoch.github.io/Notepad-fyzika/** (po zapnutí GitHub Pages), nebo stačí otevřít `index.html` v prohlížeči.

## Zkratky při psaní

| Napíšeš | Dostaneš |
|---|---|
| `x^2`, `10^-11` | x², 10⁻¹¹ |
| `v_0`, `F_max` | v₀, Fₘₐₓ |
| Alt+V | šipka nad písmenem před kurzorem, F⃗ |
| `a*b` | a·b |
| `->`, `<=`, `>=`, `!=`, `~=`, `+-` | →, ≤, ≥, ≠, ≈, ± |
| `alfa`, `síla`, `newton` + Tab | α, F / F⃗, N (našeptávač) |
| `Wel`, `Fmax`, `v0` + Tab | Wₑₗ, Fₘₐₓ, v₀ |
| `absolutní hodnota` / `abs` + Tab | \|…\| s kurzorem uprostřed, Tab skočí za čáru |
| `s/` + Tab, `3/` + výběr | s/(…), (…)/(…), ³⁄₄, ¾ |
| `s-1`, `m·s-2`, `m3` + Tab | s⁻¹, m·s⁻², m³ |
| `x` + Tab | × (šipkou ↓ i ·) |
| `Fd`, `ad` + Tab | F_d, a_d (v náhledu Papír jako dolní index) |
| Alt+↑ / Alt+↓ | režim horního / dolního indexu |
| Alt+B | tučný vektor 𝐅 |

V pravém panelu jsou řecká písmena, operátory, indexy, vektory, jednotky, konstanty a hotové vzorce.

Přepínač **Psaní / Obojí / Papír** nahoře ukáže text tak, jak by se psal na papír: zlomky `a/b` a `(a+b)/(c-d)` pod sebou se zlomkovou čarou, odmocniny `√(…)` s čarou nad výrazem. Znaménko krát (× nebo ·) drží výraz pohromadě i s mezerami, takže `X / Y × 3` se vykreslí jako X nad Y × 3. Plus a minus zlomek ukončí (`X / Y + 3`), stejně jako závorka: `F/(m) × 3` je F nad m a za zlomkem × 3. Klepnutím na znak v náhledu se kurzor v textu postaví přesně na něj, klepnutím na prázdný rámeček do čitatele nebo jmenovatele.

## Ukládání poznámek

Poznámky se průběžně ukládají v prohlížeči. Tlačítko **Záloha** nahoře nabízí:

- **Export** všech poznámek do souboru `.json` nebo aktuální poznámky do `.txt`
- **Import** zálohy `.json` (sloučí se, novější verze poznámky vyhrává) nebo textového souboru jako nové poznámky
- **GitHub**: s přístupovým tokenem (fine-grained, Contents: Read and write) se poznámky samy ukládají do souboru `poznamky/poznamky.json` v repozitáři a načítají se na všech zařízeních. Funguje ze stránky na GitHub Pages, ne z okna claude.ai.

Tento repozitář je veřejný. Pro soukromé poznámky zadej v nastavení vlastní soukromý repozitář.

### Zapnutí GitHub Pages

Settings → Pages → Build and deployment → Source: *Deploy from a branch*, Branch: `main`, složka `/ (root)` → Save.
