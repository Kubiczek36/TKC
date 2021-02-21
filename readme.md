# Projekt dalekohledu pro předmět TKC

Dalekohled se bode skládat z objektivu, ostřícího členu a okuláru s určením pro pozemní pozorování. Jako převracecí mechanismus bude použito zrcátko.

[Stránky Meopty](https://eshop.meopta.cz/spektivy/) s inspirací.

## Rozvržení

Konstrukce je inspirována spektivem [Meopta MeoStar S2](https://eshop.meopta.cz/spektivy-meostar-s2/spektiv-meostar-s2-82-hd-sikmy/) tento spektiv má ohniskovou vzdálenost objektivu 439 mm.

![rozvrzeni dalekohledu](imgs/rozvrzeni.jpeg)

Jako objektiv bude sloužit achromatický dublet. Například firma Edmund Optics [nabízí](https://www.edmundoptics.com/c/achromatic-lenses/652/#29374=29374_s%3ANS4wMCAtIDUuOTk1&29374=29374_s%3ANC4wMCAtIDQuOTk1&27560=27560_s%3AVklTIDAmZGVnOyAoNDI1LTY3NW5tKQ2&27560=27560_s%3AVklTLU5JUiAoNDAwLTEwMDBubSk1&27560=27560_s%3ATWdGPHN1Yj4yPC9zdWI-ICg0MDAtNzAwbm0p0&27560=27560_s%3ATWdGPHN1Yj4yPC9zdWI-ICg0MDAtNzAwbm0p0&27560=27560_s%3AVklTIDAmZGVnOyAoNDI1LTY3NW5tKQ2&27560=27560_s%3AVklTLU5JUiAoNDAwLTEwMDBubSk1&27560=27560_s%3AVVYtVklTICgzNDUtNzAwbm0p0&27614=27614_d%3A%5B59.18%20TO%2089.47%5D) takové dublety, které vyhovují průměrem ohniskem. Další výhodou je knihovna dílů v programu Zemax Optics Studio.

Jako okulár se jeví vhodné použít Kellnerův nebo Širokoúhlý okulár [[1](#lit)].<!-- Odkaz fuguje! --> Schéma okulárů lze vidět na obrázcích [[1,2](#lit)].

![BW okulary](imgs/bw_okulary_schemata.jpg) 
![Mikroskopové okuláry FH](imgs/fh_dalekohledove_ok.jpeg)

(c-d) Širokoúhlé okuláry.

![Mikroskopové okuláry FH](imgs/fh_mikroskopove_okulary.jpeg)

(c) Kellnerův okulár.

Pokud bude cílem dosáhnout zvětšení zhruba 20x, pak očekávané ohnisková délka okuláru je 20 mm. Pro zvětšení 30x je zapotřebí 13,3 mm.

> Zorné pole 3°?

## Výběr komponent

### Objektiv

__Možnosti__

[Vyhledávání v Edmundu s výsledky pro objektiv](https://www.edmundoptics.com/c/achromatic-lenses/652/#29374=29374_s%3ANS4wMCAtIDUuOTk1&29374=29374_s%3ANC4wMCAtIDQuOTk1&27560=27560_s%3AVklTIDAmZGVnOyAoNDI1LTY3NW5tKQ2&27560=27560_s%3AVklTLU5JUiAoNDAwLTEwMDBubSk1&27560=27560_s%3ATWdGPHN1Yj4yPC9zdWI-ICg0MDAtNzAwbm0p0&27560=27560_s%3ATWdGPHN1Yj4yPC9zdWI-ICg0MDAtNzAwbm0p0&27560=27560_s%3AVklTIDAmZGVnOyAoNDI1LTY3NW5tKQ2&27560=27560_s%3AVklTLU5JUiAoNDAwLTEwMDBubSk1&27560=27560_s%3AVVYtVklTICgzNDUtNzAwbm0p0&27614=27614_d%3A%5B59.18%20TO%2089.47%5D). 

- [kandidát na objektiv](https://www.edmundoptics.com/p/75mm-dia-x-300mm-fl-vis-nir-coated-achromatic-lens/30852/)
- [náhradník na objektiv](https://www.edmundoptics.com/p/635mm-dia-x-3549mm-fl-achromatic-lens/2017/)

### Okulár

Pro Kellnerovu konstrukci okuláru

__První čočka:__
 - [Thorlabs best Form](https://www.thorlabs.com/thorproduct.cfm?partnumber=LBF254-040-A) 50 €
 - [Thorlabs aspheric](https://www.thorlabs.com/thorproduct.cfm?partnumber=AL2550G-A) 290 €

__Druhá čočka:__
 - [Thorlabs achromatický dublet](https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=120) f' = 19 mm prum. 12,75 mm (zv. 30x)
 - [Thorlabs achromatický dublet](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC080-016-A) f' = 16 mm prum. 12,75 mm (zv. 35x)

Dále je v nabídce dublet s ohniskem 10 mm následné zv. 50 x.

> __Možný plán:__ navrhnout vícero okulárů s různými zvětšeními. Prvotním cílem bude zvětšení 20-30x

----
__staré__

- [kandidát na okulár](https://www.edmundoptics.com/p/25mm-dia-x-40mm-fl-mgfsub2sub-coated-achromatic-doublet-lens/2285/)

> * [edmund](https://www.edmundoptics.com/c/achromatic-lenses/652/#27560=27560_s%3ATWdGPHN1Yj4yPC9zdWI-ICg0MDAtNzAwbm0p0&27560=27560_s%3AVklTIDAmZGVnOyAoNDI1LTY3NW5tKQ2&27560=27560_s%3AVklTLU5JUiAoNDAwLTEwMDBubSk1&27560=27560_s%3AVVYtVklTICgzNDUtNzAwbm0p0&27614=27614_d%3A%5B89.04%20TO%20140.00%5D)
> * [nejlepší kandidát od Edmundu](https://www.edmundoptics.com/p/90mm-dia-x-8499mm-fl-achromatic-lens-mtd-/11255/) za něj přidat [toto](https://www.edmundoptics.com/p/635mm-dia-x-3549mm-fl-achromatic-lens/2017/) pro zkrácení, případně si pomoct [pozitivním meniskem](https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=130)
> * [čočka f_1](https://www.edmundoptics.com/p/25mm-dia-x-25mm-fl-mgfsub2sub-coated-achromatic-doublet-lens/20105/) prum 25 mm ohnisko 25

## Literatura <a name="lit"></a>

[1] Fuka Josef, Havelka Bedřich: _Optika a atomová fyzika_. SPN Praha 1961.

[2] Born Max, Wolf Emil: _Principles of optics_. Seventh anniversary ed, Cambridge University Press 2019.
