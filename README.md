# Lentotähti nettisivut

## Miten sisältöä luodaan

 - `_data` kansion navigation.yml konfiguroi sivun yläosan linkit.
 - `_pages` kansiossa on ylätason sivut. esim. `/hinnasto/`
 - `_posts` kansio on spessu kansio. Yksi ylätason sivuista voi olla "blogi" jonka sisältö tulee tästä kansiosta. Tiedostot nimetään `YYYY-MM-DD-name-of-post.md` formaatissa. Categories tiedoston alussa lisäytyy urliin.
 - `assets/images` kansioon voi laittaa kuvat.
 - `_hinnasto` kansio on spessu kansio myös. Se on "Collection", eli `_config.yml` tiedostossa löytyy seuraavanlainen konfiguraatio:

```yaml
# Collections
collections:
  hinnasto:
    output: true
    permalink: /:collection/:path/
```
ja
```yaml
defaults:
  # ..tässä on kaikkea muuta ensin ja sitten
  # _hinnasto
  - scope:
      path: ""
      type: hinnasto
    values:
      layout: single
      author_profile: false
      share: true
```
joka luo `/hinnasto/tiedoston-nimi-_hinnasto-kansiossa/` sivustot.

## Miten editoida sisältöä

Sivujen sisältö tehdään [Markdown](https://www.markdownguide.org/basic-syntax/) kielellä. Jekyll framework luo niistä html:n

[Täällä](https://mmistakes.github.io/minimal-mistakes/year-archive/) on esimerkkejä mitä kaikkea voi helposti tehdä ja [täällä](https://github.com/mmistakes/minimal-mistakes/tree/master/docs) miten ne on tehty.

All rights reserved