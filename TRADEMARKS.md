# Trademarks

**Hao-shuo-de™, Jiandanhua™ and Miao-long™ are trademarks of Kirill Novik.** The ™ means the names are claimed.
Once a registration is granted, ™ becomes ® for that name in that country, by one line in `haoshuode/src/content/brands.js` (in the Hao-shuo-de submodule).

## The names, in every spelling

Each name is claimed in every spelling a reader might meet:

- with or without hyphens or spaces between its parts, in any mix (Hao-shuo-de, Haoshuode, Hao shuo de, Hao-shuode);
- in any letter case (HAO-SHUO-DE, hao-shuo-de, HaoShuoDe);
- in pinyin with or without tone marks (Hǎo-shuō-de, Hao-shuo-de);
- in simplified and traditional Chinese characters;
- in Cyrillic.

| Name | Main form | Characters | Cyrillic | Also claimed |
| --- | --- | --- | --- | --- |
| Hao-shuo-de™ | Hao-shuo-de, Hǎo-shuō-de | 好说的, 好說的 | Хао-шо-да | Haoshuode, HaoShuoDe, Hao Shuo De, Хаошода, Хао-шо-дэ, Хао-шуо-дэ |
| Jiandanhua™ | Jiandanhua, Jiǎndānhuà | 简单话, 簡單話 | Цзяньданьхуа | JianDanHua, Jian-dan-hua, Jian Dan Hua, Jiǎn-dān-huà |
| Miao-long™ | Miao-long, Miāo-lóng | 喵龙, 喵龍 | Мяолун | Miaolong, MiaoLong, Miao Long, Meow-long, Meowlong, Мяу-лун |

The full generated list (every join and every case) is on the book's legal page (`#/legal`,
`src/components/Legal.jsx`) and comes from `variants()` in `haoshuode/src/content/brands.js` (the Hao-shuo-de
submodule). The names and the look of the book's characters (Miao-miao the cat, Kuai-kuai the dragon and the others)
are claimed the same way.

## What you may do without asking

The languages are free (see [LICENSE](LICENSE)). You may use the names to say what language something is in or what
you study, accurately and without suggesting that the owner made or approved it:

- "I study Hao-shuo-de", "a story written in Hao-shuo-de", "my notes on Jiandanhua";
- a review, an article, a comparison or a research paper that names the languages.

## What needs written permission

- Using a name, or a name that looks or sounds like it, as the name or part of the name of a course, school, book,
  app, website, domain, social-media account, channel, test, certificate or product.
- Calling anything "official", "certified", "approved" or "Miao-long".
- Using the logos or the characters.

For a licence (schools included), contact the owner through https://github.com/kino6052.

## For the code

Components call `brand()` from `haoshuode/src/content/brands.js` (the Hao-shuo-de submodule), and `index.html`
writes `{{brand:jiandanhua:toned}}`, which the brand plugin writes out. A Hao-shuo-de sentence keeps the plain name in
its text, and `Hsd` (through `Line`) shows it with its ™.
