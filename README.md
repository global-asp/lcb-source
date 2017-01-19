# Source stories from the Little Cree Books collection in Markdown format

This repository makes available the source texts of stories from [Little Cree Books](http://littlecreebooks.com/) in Markdown format. The stories are written in Plains Cree, Swampy Cree, and English.

The collection is significant because it is, as far as we are aware, the first and only collection of open-licensed stories in an Indigenous Canadian language. It thus represents an incredibly valuable and lasting contribution to human knowledge whose preservation will not be threatened by the restrictions copyright.

All of the source texts have been extracted from pdfs available on the [Little Cree Books](http://littlecreebooks.com/) website. The markdown files in this repo provide data for many other projects, as well as making possible the creation of bilingual storybooks in many languages.

## Structure

Each story in the repository is tagged with a two- or three-letter code that represents the language it is written in (e.g. `crk` for Plains Cree). A list of available languages and their codes is [below](#languages).

Each story has also been assigned a four digit number for ease of identification. There is a full list of the stories by number [below](#stories).

In each folder in the repository you will find a series of files containing various versions of the text of the story in Markdown format, as well as a `README` file with information about the story. There are separate files for each available language and orthography (i.e., syllabics or romanization for `crk` and `csw`, and English for `en`).

The orthography of each file is indicated by the special three-letter codes `cas` and `sro` (for _Canadian Aboriginal Syllabics_ and _Standard Roman Orthography_ respectively) at the end of the filename. For example, the Plains Cree version of the story #0002 _Little Bear's Day_ is available in two different files in the story folder:

* `0002_little-bears-day_cas.md` (Canadian Aboriginal Syllabics)
* `0002_little-bears-day_sro.md` (Standard Roman Orthography)

## Format

The extracted source text of all stories has been provided here in Markdown format. See [here](https://github.com/global-asp/global-asp#source-format) for specific details about the format used.

A sequence of two hashes `##` on a separate line indicates a page break.

The last section of each story file contains attribution and license information.

Editing of the story content has been kept to a minimum and for the most part the stories are presented exactly as they were written. Corrections other than obvious errors of orthography or traces of the conversion process should be directed to the Little Cree Books website directly.

## Languages

The Little Cree Books stories are currently available in 3 different languages and two different orthographies. This repository attempts to provide the source text for all of these stories in machine- and human-readable Markdown format.

Below is a key to the languages covered by this repository and their [ISO 639-1](http://en.wikipedia.org/wiki/ISO_639-1) or [ISO 639-3](http://en.wikipedia.org/wiki/ISO_639-3) codes.

ISO code | Language Name
-------- | -------------
`crk` | Plains Cree
`csw` | Swampy Cree
`en` | English

## Orthography

The texts of each story are available in both of the two orthographies for writing Cree, namely syllabics and romanization. As described above, the orthography of each file is indicated in the filename by one of the following codes:

Code | Orthography
---- | -----------
`cas` | Canadian Aboriginal Syllabics
`sro` | Standard Roman Orthography

The original source pdfs provided by Little Cree Books are not always available in syllabics, however all of the stories included here are available in both syllabics and SRO. The SRO orthography of the original stories has been converted into syllabics using a [custom made transliteration tool](https://github.com/dohliam/cree-transliteration) designed for this purpose. Please file an issue if you find any errors in the syllabics conversion.

If you would like to use the transliteration tool to convert between syllabics and SRO, you can find it [here](https://dohliam.github.io/transliteration/cree/).

## Stories

ID | Level | Syllabics | Standard Roman Orthography (SRO) | English | Languages
-- | ----- | --------- | -------------------------------- | ------- | ---------
0001 | n/a | ᐯᔭᐠ ᐁᐦᐃᐢᐸᔨᐠ ᐅᐦᒋ ᑳᐸᐹᒥᐱᐦᐋᐟ ᑭᐦᐁᐤ | [peyak ehispayik ohci kâpapâmipihât kihew](http://littlecreebooks.com/wp-content/uploads/2014/02/Flying-Eagle-book-SRO.pdf) | [Flying Eagle](http://littlecreebooks.com/wp-content/uploads/2014/02/Flying-Eagle.pdf) | Plains Cree, English
0002 | Level 1 | [ᒪᐢᑯᓯᐢ ᐅᑮᓯᑳᒼ](http://littlecreebooks.com/wp-content/uploads/2013/02/Little-Bears-Day-maskosis-ok%C3%AEsik%C3%A2m-syllabics.pdf) | [maskosis okîsikâm](http://littlecreebooks.com/wp-content/uploads/2013/02/Little-Bears-Day-maskosis-ok%C3%AEsik%C3%A2w-SRO.pdf) | [Little Bear's Day](http://littlecreebooks.com/wp-content/uploads/2013/02/Little-Bears-Day-maskosis-ok%C3%AEsik%C3%A2m-press-quality.pdf) | Plains Cree, English
0003 | n/a | ᒪᐢᑯᓯᐢ ᓂᐢᑕᒼ ᑳᑕᑯᐦᑌᐟ ᐆᑌᓈᐦᐠ | [maskosis nistam kâtakohtet ôtenâhk](http://littlecreebooks.com/wp-content/uploads/2013/06/New-in-Town-SRO.pdf) | [New in Town](http://littlecreebooks.com/wp-content/uploads/2013/06/New-in-Town-book-final.pdf) | Plains Cree, English
0004 | Level 2 | ᐊᐢᑭᐤ ᒣᐢᑯᒋᐸᔪᐏᓇ | [askiw meskocipayowina](http://littlecreebooks.com/wp-content/uploads/2013/01/Grade-1-The-Seasons-Kitten.pdf) | [The Seasons](http://littlecreebooks.com/wp-content/uploads/2013/01/Grade-1-The-Seasons-Kitten.pdf) | Plains Cree, English
0005 | Level 2 | [ᓅᑯᒼ ᒫᑫᓯᐤ](http://littlecreebooks.com/wp-content/uploads/2014/04/Grandmother-Fox-n-dialect.pdf) | [nōkom mākēsiw](http://littlecreebooks.com/wp-content/uploads/2014/04/Grandmother-Fox-n-dialect.pdf) | [Grandmother Fox](http://littlecreebooks.com/wp-content/uploads/2014/04/Grandmother-Fox-n-dialect.pdf) | Swampy Cree, English
0006 | Level 2 | [ᐊᐱᐢᒋᒫᑫᓰᓯᐢ](http://littlecreebooks.com/wp-content/uploads/2014/04/Little-Fox-n-dialect.pdf) | [apiscimākēsīsis](http://littlecreebooks.com/wp-content/uploads/2014/04/Little-Fox-n-dialect.pdf) | [Little Fox](http://littlecreebooks.com/wp-content/uploads/2014/04/Little-Fox-n-dialect.pdf) | Swampy Cree, English

## About Little Cree Books

> The [Little Cree Books](http://littlecreebooks.com/) above are the first in what we hope will become a large collection of online books designed for early Cree readers. Please check out the [About the Project](http://littlecreebooks.com/about-the-project/) section of this website to learn more about how we hope to develop this collection. The books are currently only available in the Plains Cree dialect, but we hope to offer them in a variety of other dialects as soon as we can. We hope that educators and parents will make liberal use of these resources. Please display them on your classroom SMARTboards, print and/or photocopy them for your students/children, encourage children to read them online, or use them in other creative ways. We simply ask that users do not sell the books. Creative Commons copyright licensing [CC BY-NC-SA](http://creativecommons.org/licenses/by-nc-sa/3.0/) applies to all of the books, unless otherwise noted. Click [here](http://foter.com/blog/files//2012/11/Foter.com_infographic_CC.jpg) for more information on Creative Commons licensing.

## Levels

The Little Cree Books are leveled reading resources developed for early Cree readers. They are designed using Alberta Education’s curricular guidelines.

* __Level 1__: Kindergarten
* __Level 2__: Grade 1
* __Level 3__: Grade 2
* __Level 4__: Grade 3
* __Level 5__: Grade 4
* __Level 6__: Grade 5
* __Level 7__: Grade 6

## Links

* [nehiyawasinahikanisa](http://littlecreebooks.com/) (Little Cree Books) where you can download the original PDFs of these stories
* [LCB Imagebank](https://github.com/global-asp/lcb-imagebank) - A repository containing all the freely-licensed images that accompany these texts
* [Global LCB](https://github.com/global-asp/global-lcb) - A project to translate the source texts into as many world languages as possible

## License

All stories in this repository have been released under a [CC BY-NC-SA](http://creativecommons.org/licenses/by-nc-sa/3.0/) license, allowing them to be shared and modified freely for non-commercial purposes.
