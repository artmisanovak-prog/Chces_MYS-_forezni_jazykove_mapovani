# 🐁 Chceš myš? – Forenzní jazykova mapa

Offline nástroj pro strukturovanou analýzu výpovědí. Pomáhá vyšetřovatelům, soudcům, advokátům a znalcům vidět v textu to, co lidské oko snadno přehlédne.

---

## 🧭 Menu

- [Co to je a proč to vzniklo](#co-to-je-a-proč-to-vzniklo)
- [Komu je nástroj určen](#komu-je-nástroj-určen)
- [Komu nástroj není určen](#komu-nástroj-není-určen)
- [Jak to funguje](#jak-to-funguje)
- [Co je repo dům](#co-je-repo-dům)
- [Rychlý start](#rychlý-start)
- [Dokumentace a podmínky](#dokumentace-a-podmínky)
- [Ceny a licence](#ceny-a-licence)
- [Kontakt a podpora](#kontakt-a-podpora)

---

## 🧠 Co to je a proč to vzniklo

**Chceš myš? – Forenzní kognitivní mapa** je offline HTML nástroj, který umožňuje:

- definovat **strukturovaný rámec případu** (baseline) – fakta, časová osa, osoby, vztahy, místa, důkazy, motivy,
- vkládat výpovědi svědků, obviněných nebo poškozených,
- automaticky detekovat **12 jazykových signálů** (opakování, přeskoky, fixace, změny času, prázdná slova atd.),
- porovnávat výpovědi s baseline a vypočítat **permutační skóre** – míru strukturální odchylky,
- zobrazit **kognitivní mapu případu** – souhrnný přehled o shodách, neshodách a slepých místech napříč všemi výpověďmi.

Nástroj vznikl z potřeby mít **transparentní, offline a bezpečnou pomůcku**, která nahrává lidskému úsudku, nenahrazuje ho.

---

## 👥 Komu je nástroj určen

- **Vyšetřovatelům** – pro analýzu výslechů, odhalování rozporů, přípravu na další výslech.
- **Soudcům** – pro získání nezávislého, systematického přehledu o výpovědích v případu.
- **Státním zástupcům a advokátům** – pro posouzení konzistence výpovědí, argumentaci u soudu.
- **Soudním znalcům** (psychologům, lingvistům) – jako podklad pro znalecké posudky, objektivizace závěrů.
- **Akademické sféře** – pro výuku, výzkum justičních omylů, forenzní lingvistiky.
- **Novinářům** – pro investigativní práci, analýzu rozhovorů.

---

## 🚫 Komu nástroj není určen

- **Laické veřejnosti** bez znalosti kontextu trestního řízení.
- **Jako jediný důkazní prostředek** – výstupy jsou jen pomocné, interpretace vždy na člověku.
- **K automatizovanému rozhodování** – nástroj nerozhoduje o vině ani nevině, neříká „lže/nepravda“.

---

## ⚙️ Jak to funguje

1. **Uživatel vyplní baseline** – známá fakta, očekávanou časovou osu, osoby, vztahy, klíčová slova (místa, důkazy, motivy).
2. **Přidá výpovědi** – každou s rolí (svědek, obviněný, poškozený) a textem.
3. **Nástroj automaticky:**
   - rozdělí text na věty,
   - detekuje 12 typů jazykových signálů (každý má svou váhu),
   - porovná výpověď s baseline (čas, role, místa, důkazy, motivy),
   - vypočítá **permutační skóre** pro každou výpověď i pro jednotlivé segmenty.
4. **Výsledky se zobrazí:**
   - barevně zvýrazněný text s legendou,
   - tabulka jazykových signálů,
   - **kognitivní mapa případu** – souhrnná tabulka s přehledem skóre a počtu signálů,
   - možnost filtrovat podle kategorií (časové odchylky, místa, důkazy, motivy, jazykové signály).

Vše běží offline, data zůstávají pouze v prohlížeči (localStorage). Žádný server, žádný cloud.

---

## 🏠 Co je repo dům

**Repo dům** je způsob distribuce, který ti dává **plné vlastnictví nástroje**.

- Nekupuješ předplatné, ale **jednorázovou licenci**.
- Dostaneš ZIP s kompletním repozitářem – HTML soubory, dokumentaci, pracovní listy.
- Vše si uložíš k sobě na disk, můžeš používat offline, upravovat, tisknout.
- Žádné závislosti na internetu, žádné riziko, že ti někdo nástroj vypne nebo zdraží.

Více o filozofii repo domu najdeš v samostatném článku [ZDE](#) (odkaz doplníš).

---

## 🚀 Rychlý start

1. Stáhni si ZIP s kompletním nástrojem (po zakoupení licence).
2. Rozbal ho do libovolné složky.
3. Otevři soubor `index.html` v moderním prohlížeči (Chrome, Edge, Firefox).
4. Podle potřeby si prostuduj:

   - [Uživatelský manuál](./doma/manual.html)
   - [Etický kodex](./doma/eticky-kodex.html)
   - [Argumenty pro justici](./doma/argumenty.html)
   - [Licenční podmínky](./doma/licence.html)
   - [zpětná vazba](./doma/zpetna_vazba.html)
   - [modelové scénáře](./doma/modelove_scenare.html)
---

- [**Forézní mapování** - funkční nástroj](./doma/forezni_analyzator.html)

---

## 📚 Dokumentace a podmínky

- [Uživatelský manuál – podrobný návod](./doma/manual.html)
- [Etický kodex uživatele](./doma/eticky-kodex.html)
- [Argumenty pro justici – proč je nástroj bezpečný a užitečný](./doma/argumenty.html)
- [Licenční podmínky](./doma/licence.html)

---

## 📬 Kontakt a podpora

- **Objednávky, dotazy, individuální úpravy:** [chcesmys@gmail.com](mailto:chcesmys@gmail.com)
- **Metoda „repo dům“ a další projekty:** [Chceš myš? – slovník mezer](https://artmisanovak-prog.github.io/chces_MYS_slovnik_mezer/)

---

© 2026 Michaela Nováková  
Forezní aplikace metody „Chceš myš?“. Verze 2.0.
