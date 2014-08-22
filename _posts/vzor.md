---
layout: post
title: "Životopis"
quote: Životopis Jakuba Michálka
image: /media/2014-07-18-zivotopis/cover.jpg
video: false
---


**Mgr. Bc. Jakub Michálek** (* 6. února 1989 Louny) je právník zaměřující se na svobodný přístup k informacím a autorské právo. Pracuje v pražské advokátní kanceláři. V Pirátské straně zastává funkci člena kontrolní komise.

Vzdělání
--------

| Rok  | Druh studia | Škola |
| ----- | ------------ | --------------- |
| 2011–nyní | Nav. mgr. – teoretická fyzika | Matematicko-fyzikální fakulta UK v Praze |
| 2008–2013 | **Mgr.** – právo a právní věda    | Právnická fakulta UK v Praze |
| 2008–2011 | **Bc.** – obecná fyzika           | Matematicko-fyzikální fakulta UK v Praze |
| 2001–2008 | středoškolské vzdělání         | Gymnázium Jana Keplera |
| 2006–2007 | stipendium v zahraničí  | Cranbrook Kingswood Upper School, Michigan, USA |
| 2004 | stipendium v zahraničí | Oundle School, Peterborough, UK |



V České pirátské straně například připravoval spuštění webu Piráti.cz, navrhl zřízení registru lobbistických kontaktů a veřejného účetnictví. Vedle toho se věnuje právním otázkám.

Například ve sporu Jakub Michálek versus Ministerstvo financí uznal Nejvyšší správní soud, že podání prostřednictvím datové schránky nemusí být elektronicky podepsáno.1)
Dále byl spoluautorem návrhu na zrušení čl. 2 amnestie, který podala skupina 30 senátorů Senátu Parlamentu České republiky, a kvůli neoprávněnému odpírání informací o přípravě amnestie podal žalobu na prezidenta Václava Klause.
Spolupracoval s Oldřichem Kužílkem na návrhu novely zákona o svobodném přístupu k informacím pro senátora Libora Michálka.
Ve volném čase se věnuje činnosti v akademické samosprávě na Univerzitě Karlově, kde je členem Ediční komise AS UK. Baví ho česká opera a vážná hudba obecně, fyzikální problémy, ústavní právo a pěší výlety.

E-mail: jakub.michalek@pirati.cz


#Thinny 2.1, codename "[Cosette](http://lesmiserables.wikia.com/wiki/Cosette)"

Cosette is the main character of the french novel _Les Misérables_, published in 1862 by _Victor Hugo_.

{% include image.html url="/media/2014-02-26-hello-cosette/cosette.jpg" width="100%" description="Amanda Seyfried as Cosette on the 2012 movie." %}

This new version of Thinny comes with mobile support and some bugfixes.

## Usage

### Main variables

The global variables are set on the `_config.yml` file.

To start, you need to change at least the variable `url` on the file.

#### Social links

To add a social link you just need to add the following code inside the variable `social`:

```
  - icon:	[the genericon name for the social network]
    url:	[the url to follow]
    desc:	[a small description for the link (e.g. "Follow me on twitter")]
```

#### Menu

To add a menu item you just need to add the following code inside the variable `menu`:

```
  - title:	[title of the menu item]
    url:	[the url to follow]
```

#### Others

You'll find a lot of other variables inside the file, e.g.:

- the site `title`, `description`, `icon` and default `cover` image.
- text of the `copyright` message.
- the number of posts per page (`paginate`).
- the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).


### Default YAML tags

- `layout:`<i>`post, page`</i> `or `<i>`fullscreen`</i>: defines the layout of the page.
- `title: [string]`: title of the post.
- `quote: [string]`: a small description of the post to be shown above the title.
- `dark:`<i>`true`</i> `or `<i>`false`</i>: use black font (instead of white) for the header (default value is false).
- `image: [url] or `<i>`false`</i>: a cover image for the post (default value is _false_).
- `video:`<i>`true`</i> `or `<i>`false`</i>: add a cover video for the post (default value is _false_).
- `video_mp4: [url]`: the URL for the mp4 video.
- `video_webm: [url]`: the URL for the webm video.
- `video_ogv: [url]`: the URL for the ogv video.

## Versions

Here is a `<table>` with all Thinny's versions:
<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Codename</th>
      <th>Platform</th>
      <th>Release date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[0.3](https://github.com/camporez/Thinny/releases/tag/v0.3-alexandra)</td>
      <td>[Alexandra](http://nikita2010.wikia.com/wiki/Alexandra_Udinov)</td>
      <td>Ghost 0.3.x</td>
      <td>November 2013</td>
    </tr>
    <tr>
      <td>[2.0](https://github.com/camporez/Thinny/releases/tag/v2.0-bianca)</td>
      <td>[Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm)</td>
      <td>Jekyll</td>
      <td>January 2014</td>
    </tr>
    <tr>
      <td>[2.1](https://github.com/camporez/Thinny/releases/tag/v2.1-cosette)</td>
      <td>[Cosette](http://lesmiserables.wikia.com/wiki/Cosette)</td>
      <td>Jekyll</td>
      <td>March 2014</td>
    </tr>
    <tr>
      <td>2.2</td>
      <td>[Dolores](http://en.wikipedia.org/wiki/Dolores_Haze)</td>
      <td>Jekyll</td>
      <td><i>Soon (see the [issues list](https://github.com/camporez/camporez.github.io/issues?milestone=3))</i></td>
    </tr>
  </tbody>
</table>

## Download

> Thinny 2.1 is already [available for download on GitHub](https://github.com/camporez/Thinny/releases).

-----
Want to see something else added or report a bug? [Open an issue](https://github.com/camporez/camporez.github.io/issues/new).
