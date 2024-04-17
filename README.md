# Repozitár `formular-resources`

Tento repozitár obsahuje **šablóny a ďalšie nastavenia**, ktoré sa využívajú v aplikácii [Formular](https://github.com/oznamovatelia/formular).

Repozitáre sú rozdelené nasledovne:

* [zdrojový kód aplikácie](https://github.com/oznamovatelia/formular)
* [konfigurovateľné časti aplikácie](https://github.com/oznamovatelia/formular-resources) (texty, HTML šablóna, CSS štýly, Word šablóna) -- tento repozitár nie je použiteľná samostatne, pretože obsahu len konfigurovateľné časti aplikácie

V repozitári so zdrojovým kódom aplikácie sa aktualizujú konfigurovateľné časti pomocou funkcionality `git submodule` (bližšie detaily sú v dokumentácii aplikácie). Ak chcete prispôsobiť adresár `resources` (napr. nadefinovať vlastné CSS štýly, upraviť hlášky, vložiť vlastné logo a podobne), môžete si vytvoriť vlastný klon (kópiu, "fork") repozitára a v aplikácii zmeniť URL pre submodul tak, aby aplikácia používala vašu upravenú verziu.

Vďaka oddeleniu kódu aplikácie a jej konfigurovateľných častí tak môžete prevádzkovať na serveri **vlastnú verziu šablón a zároveň najnovší zdrojový kód**. Po aktualizáciách kódu aplikácie sa preto výrazne zjednoduší vaša práca pri spájaní aktualizovanej verzie kódu a vašich úprav šablón.

Dokumentáciu nájdete v hlavnom repozitári: https://github.com/oznamovatelia/formular

---

Kontakt: [Úrad na ochranu oznamovateľov](https://www.oznamovatelia.sk/). Softvér je zverejnený pod otvorenou licenciou [EUPL](LICENSE.txt).
