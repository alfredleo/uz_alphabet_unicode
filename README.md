# uz_alphabet_unicode
Uzbek language string manipulation tests. Unicode support. Uzbek Latin and Cyrillic alphabet examples. 

## Information about uzbek language

* [Uza.uz project link]
* [Gazeta.uz new changes]
* [Uzbek alphabet unicode from Wikipedia]
* [Unicode uzbek link]
* [Conversion from cyrillic to latin]

**Changes supported by the committee.**

| Cyrillic | Latin | Latin-2019 |
| ------ | ------ | ------ |
| Ў ў | O‘ o‘ | Ŏ ŏ |
| Ғ ғ | G‘ g‘ | Ğ ğ |
| Ч ч | Ch ch | Ç ç |
| Ш ш | Sh sh | Ş ş |


**Full table of transliteration by years.**

| Table |  |  |  | |  |
| ------ | ------ | ------ | ------ | ------| ------ |
| Arabic | Latin | Cyrillic | Latin | Latin | |
| 1923-1930 | 1934-1940 | 1940- | 1995- | 2019- | IPA
| ئه ,ه | A a, Ə ə | А а | A a | A a | [a], [æ] |
| ﺏ | B ʙ | Б б | B b | B b | [b] |
| ﺩ | D d | Д д | D d | D d | [d] |
| ئي | E e | Е е, Э э | E e | E e | [е] |
| ﻑ | F f | Ф ф | F f | F f | [f] |
| گ | G g | Г г | G g | G g | [g] |
| ﻫ | H h | Ҳ ҳ | H h | H h | [h] |
| ی | I i | И и | I i | I i | [ɪ] |
| ﺝ ,ژ | Ç ç, Ƶ ƶ | Ж ж | J j |  J j | [ʤ], [ʒ]|
| ﻙ | K k | К к | K k | K k | [k] |
| ﻝ | L l | Л л | L l | L l | [l] |
| ﻡ | M m | М м | M m | M m | [m] |
| ن | N n | Н н | N n | N n | [n] |
| ئا, ئو | A a, O o | О о | O o | O o | [ɑ] |
| پ | P p | П п | P p | P p | [p] |
| ﻕ | Q q | Қ қ | Q q | Q q | [q] |
| ﺭ | R r | Р р | R r | R r | [r] |
| س | S s | С с | S s | S s | [s] |
| ﺕ | T t | Т т | T t | T t | [t] |
| ئۇ | U u | У у | U u | U u | [u] |
| ۉ | V v | В в | V v | V v | [v], [w]|
| ﺥ | X x | Х х | X x | X x | [χ] |
| ی | J j | Й й | Y y | Y y | [j] |
| ز | Z z | З з | Z z | Z z | [z] |
| ئو | O o | Ў ў | Oʻ oʻ | Ŏ ŏ | [o] |
| ﻍ | Ƣ ƣ | Ғ ғ | Gʻ gʻ | Ğ ğ | [ɣ] |
| ﺵ | Ş ş | Ш ш | Sh sh | Ş ş | [ʃ] |
| چ | C c | Ч ч | Ch ch | Ç ç | [ʧ] |
| ڭ | Ꞑ ꞑ | Нг нг | ng | ng | [ŋ] |
| ء ,ﺋ | ʼ | Ъ ъ | ʼ | ʼ | [ʔ] |

> Хулоса сифатида, умумий меҳнатимиз маҳсули бўлган – 28 та ҳарф, битта ҳарфий бирикма ва битта белгидан иборат, жами 30 бирликдан ташкил топган алифбо лойиҳасини эътиборингизга ҳавола қиламиз.

> Ушбу алифбодаги янгиланаётган тўрт ҳарф бизни шу пайтгача қийнаб келаётган муаммолардан халос этади. Ŏŏ Ğğ ҳарфлари O‘o‘ G‘g‘ ҳарфларининг айни пайтдаги ёзма шаклига яқин бўлгани боис ва Çç Şş ҳарфлари халқимизга яхши таниш бўлгани учун ёшу қари томонидан тез ўзлашади – ҳеч кимга қийинчилик, ноқулайлик туғдирмайди.

> Алифбо лойиҳаси расман қабул қилингандан сўнг бу ҳарфлар компьютер клавиатурасидаги қулай тугмаларга жойлаштирилади. Масалан, Çç ҳарфини ўзбек тилида ишлатилмайдиган – Сс ҳарфи ўрнига, Şş ҳарфини – Ww ҳарфи тугмачасига, Ŏŏ ва Ğğ ҳарфларини эса бирорта лотин ҳарфи ё тиниш белгиси банд қилмаган, кирилча Х, Ъ ҳарфлари турган тугмачаларга бириктириш мумкин.


![Проект обновленного узбекского алфавита](images/new_changes.jpg?raw=true "Проект обновленного узбекского алфавита")

We need to somehow distinguish uzbek latin and uzbek cyrillic. [Uzbek language codes]
- uz	Uzbek
- uz-UZ-Cyrl	Uzbek (Cyrillic) - Uzbekistan
- uz-UZ-Latn	Uzbek (Latin) - Uzbekistan

I propose to use `uz` for current latin, and `uz-UZ-Cyrl` as cyrillic version.

[Uzbek alphabet unicode from Wikipedia]: https://en.wikipedia.org/wiki/Uzbek_alphabet
[Unicode uzbek link]: https://www.unicode.org/udhr/n/notes_uzn_latn.html
[Gazeta.uz new changes]: https://www.gazeta.uz/ru/2018/11/06/alphabet/
[Uza.uz project link]: http://www.uza.uz/oz/society/lotin-yezuviga-asoslangan-zbek-alifbosi-a-ida-ishchi-guru-ni-06-11-2018?m=y&ELEMENT_CODE=lotin-yezuviga-asoslangan-zbek-alifbosi-a-ida-ishchi-guru-ni-06-11-2018&SECTION_CODE=society
[Conversion from cyrillic to latin]: https://www.lexilogos.com/keyboard/uzbek_conversion.htm
[Uzbek language codes]: https://docs.sdl.com/LiveContent/content/en-US/SDL_MediaManager_241/concept_A9F20DF9433C46FF8FED8FA11A29FAA0