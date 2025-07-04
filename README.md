# Čeština pro Sid Meier's Colonization

- autor: Michal Breškovec (Old Bear)
- e-mail: michal@breskovec.cz
- web: https://mujkoutek.cz/
- Lightning adresa (pokud byste chtěli poděkovat za překlad ;-)): mbreskovec@bitlifi.com
- Licence překladu: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.cs)

Překlad vznikal v letech 1997 a 1998, drobnou korekturou prošel koncem roku 2004.

Nyní v roce 2025 vznikla verze překladu 2.0, kdy došlo ke kompletnímu přepisu překladu a byla přidána verze s diakritikou.

Pokud najdete chybu, nebo překlep, neváhejte mě prosím kontaktovat.

## Instalace překladu
Nejprve si zvolte, zda chcete překlad **s diakritikou** nebo **bez diakritiky**.

Možná se ptáte, proč zvolit verzi bez diakritiky. Jde o to, že fonty použité v Colonization jsou poměrně malé a přidání diakritických znamének má určitý dopad na čitelnost textu, zvláště pokud hrajete třeba v DOSBoxu na velkém monitoru (pokud byste hráli na starém počítači s CRT monitorem, jako já ;-), vypadají texty mnohem lépe). Takže pokud zjistíte, že je pro vás čitelnost textu s diakritikou přliš obtížná, zvolte verzi bez diakritiky.

### Překlad s diaktritikou
Zkopírujte obsah složky "**diakritika**" do složky s hrou a přepište tak následující soubory.

- Pokud chcete proveďte nejdříve zálohu těchto souborů, ale naleznete je i zde, ve složce "**english**":

    AUTOEXEC.TXT  
    CLOSING.TXT  
    CONFIG.TXT  
    DEBUG.TXT  
    FONT-NP.FF  
    FONTINTR.FF  
    FONTKING.FF  
    FONTSMAL.FF  
    FONTTINY.FF  
    GAME.TXT  
    LABELS.TXT  
    MEMORY.TXT  
    MEMORY2.TXT  
    MENU.TXT  
    NAMES.TXT  
    OPENING.TXT  
    PEDIA.TXT  
    WOODCUT.TXT  


### Překlad bez diakritiky
Zkopírujte obsah složky "**bezdiakritiky**" do složky s hrou a přepište tak následující soubory.

- Pokud chcete proveďte nejdříve zálohu těchto souborů, ale naleznete je i zde, ve složce "**english**":

    AUTOEXEC.TXT  
    CLOSING.TXT  
    CONFIG.TXT  
    DEBUG.TXT  
    GAME.TXT  
    LABELS.TXT  
    MEMORY.TXT  
    MEMORY2.TXT  
    MENU.TXT  
    NAMES.TXT  
    OPENING.TXT  
    PEDIA.TXT  
    WOODCUT.TXT  

### Změna překladu s diakritikou za bez diakritiky a obráceně
Jednoduše soubory ve složce s hrou opět přepište soubory s požadovanou verzí překladu.

## Odinstalace překladu
Přepište češtinu soubory ze zálohy, pokud jste si ji vytvořili, nebo přepiště soubory ve složce s hrou obsahem složky "**english**".

## Bonus
Jako bonus zde naleznete **anglický manuál** ke hře ("*Sid Meier's Colonization - manual.pdf*") a čísla časopisů **Excalibur** ("*Excalibur 035 (11-1994) - Str. 30.pdf*") a **Score** ("*Score 011 (11-1994) - Str. 21.pdf*"), které obsahují recenzi na Sid Meier's Colonization.

## Changelog

- Verze 2.0 (07.2025) - Kompletní revize a přepis překladu a verze s diakritikou.
- Verze 1.1 (xx.2004) - Drobné korektury.
- Verze 1.0 (xx.1998) - První verze překladu vzniklá během let 1997 a 1998.

## Seznam složek a souborů

- **bezdiakritiky** - Překlad bez diakritiky (nepotřebuje upravené fonty).
- **diakritika** - Překlad s diakritikou (obsahuje upravené fonty).
- **english** - Originální soubory v angličtině (obsahuje původní fonty).
    - **Excalibur 035 (11-1994) - Str. 30.pdf** - Časopis Excalibur, číslo 35 z 5. listopadu 1994, recenze na Colonization je na straně 30.
    - **Score 011 (11-1994) - Str. 21.pdf** - Časopis Score, číslo 11 z listopadu 1994, recenze na Colonization je na straně 21.
- **recenze** - Obsahuje PDF časopisů Excalibur a Score s recenzí na Colonization.
- **tools** - Nástroje a zdroje použité při překladu.
    - **cz_fonty** - Upravené fonty s českými znaky.
    - **fonty-kodovaci-tabulka.ods** - Tabulka ASCII znaků přiřazených českým fontům (formát LibreOffice Calc).
    - **fonty-zdroj.zip** - Rozbalené upravené a originální fonty.
    - **MADSPack.1.1.0.zip** - Program pro prohlížení a export grafických formátů používaných v MicroProse.
    - **mpskit-opraveny.zip** - Nástroj (napsaný v Pythonu) pro Export / Import fontů a dalších grafických formátů používaných v MicroProse (opravená verze).
- **utf8** - Překlad s diakritikou v UTF-8 kódování (musí být konvertován na ASCII podle přiložené kódovací tabulky).
- **Sid Meier's Colonization - manual.pdf** - Manuál ke hře Sid Meier's Colonization (v angličtině).

## Překlad

### Nástroje
- [MADSPack Viewer](https://github.com/TheRealAyCe/MADSPackViewer) - Prohlížení a export grafických formátů používaných v MicroProse.
- [mpskit](https://github.com/institution/mpskit) - Nástroj (napsaný v Pythonu) pro Export / Import fontů a dalších grafických formátů používaných v MicroProse - použito pro úpravu fontů (program z GitHubu musel být opraven, aby fungoval, opravená verze přiložena).

### Fonty

Fonty lze upravit pomocí nástroje **mpskit**. Nástroj **mpskit** umí soubor s fontem (***.FF**) rozbalit tak, že každý znak je reprezentován obrázkem v **PNG** formátu. Obrázky lze následně upravit libovolným grafickým editorem (třeba [GIMP]((https://www.gimp.org/)) a po uprávě se tyto obrázky pomocí **mpskit** opět zabalí do **FF** souboru.

**POZOR**: Výška fontu musí zůstat zachována, ale šířku lze modifikovat.

#### Formát názvu obrázku s fontem
Aby vše fungovalo správně, musí mít název obrázku s fontem správný název. Obrázek je pojmenován následovně, viz příklad níže:

**FONT-NP.FF.017.png**

- **FONT-NP.FF** - Název soubory s fontem.
- **017** - Číslo znaku v ASCII kódování (v tomto případě namapované "**č**").
- **.png** - Přípona souboru ve formátu PNG.

Český font tedy **musí mít v názvu číslo ASCII znaku, na který je namapován** - viz "**Konverze diakritiky do ASCII**" níže.

#### Rozbalení fontu
```
./mpskit ff unpack /cesta_ke_slozce_s_fontem/JMENO_FONTU.FF
```

#### Sbalení fontu
```
./mpskit ff pack /cesta_ke_slozce_s_robalenym_fontem/JMENO_FONTU.FF
```

### Konverze diakritiky do ASCII
Sid Meier's Colonization, jako hra pro DOS, dokáže zobrazit jen **základní ASCII znaky**, tedy 128 znaků. Znaky s českou diakritikou je tedy potřeba **namapovat** na nepoužité znaky z těch 128, ze základní ASCII tabulky.

Tabulka "*fonty-kodovaci-tabulka.ods*" obsahuje použité namapování českých znaků na ASCII.

Znaky s diakritikou ve zdrojovém překladu, s kódováním třeba v UTF-8, je následně potřeba zkonvertovat do těchto namapovaných ASCII znaků. Protože se obvykle jedná o netisknutelní znaky, je potřeba použít jejich ASCII kódy.

Například pomocí textového editoru [Vim](https://www.vim.org/) je možné udělat to takto, v "*Insert*" módu stisknout ```Ctrl+V```, napsat číslo ASCII kódu, třeba "**17**" pro "**č**" a stiknout ```Enter```.

#### Nahrazení všech znaků v celém textu lze takto

Ujistěte se, že nemáte aktivované ignorování velikosti písma, aby nedošlo nahrazení velkých písmen s diakritikou malými písmeny a obráceně:

```
:set noignorecase
```

Proveďte nahrazení požadovaného znaku, v tomto případě "**č**" kódem "**17**":

V "*příkazovém*" módu napište: ```%s/č/17Enter/g```

```
:%s/č/^Q/g
```

**Poznámka**: Dejte si pozor v souboru "**PEDIA.TXT**", u **školy**, **střední školy** a **univerzity** je překvapivě použita sekvence znaků ```^ů```, pro odsazení textu, takže pokud toto "**ů**" přepíšete, je potřeba to opravit do původního stavu.
