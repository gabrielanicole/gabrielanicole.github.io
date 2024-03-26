---
title: "Teaching"
description: "description of teaching activities in Chile and France "
publishDate: "22 Feb 2023"
updatedDate: 22 Jan 2024
tags: []
---


## Traitement Automatique de Langage Naturel - Finance 

cours de 4 TP (12heqTD pour le semestre 9 de Ensimag, filière Ingénierie pour la finance (IF)) de Traitement automatique du langage naturel (TAL) pour la fouille de texte de l'axe de Apprentissage pour la finance.  Dans ce cours, j'enseigne d'abord les bases techniques lors d'un TP d'introduction à la manipulation de données textuelles écrites en français, suivi de la mise en pratique d'un système de traduction automatique neuronal (entraînement, traduction/inférence et évaluation), ainsi que l'analyse de données textuelles avec des représentations de plongement de mots (BERT) et la classification d'entités nommées (Hidden Markov Models).
Dans le cadre de ce cours, j'ai dû mettre à jour le matériel et corriger chaque rendu de travail.

**Material:** 
- TP Intro : [Colab](www.colab.com)
- TP NMT : [Colab]
- TP BERT : [Colab]
- TP HMM : [Colab]


## Explicabilité TAN

4heqTD de CM dans le cadre du cours d'Introduction à la traduction automatique (M1 TSM semestre 8, UFR SoCLE), cours créé à partir de mon travail post-doctoral sur l'explicabilité de la traduction automatique. J'ai été responsable de la création de matériel pédagogique et du développement de démonstrations en ligne pour que les étudiants comprennent les différentes méthodes d'explicabilité pertinentes pour la traduction automatique neuronal. 

**Material:**
- Slides : [MAKENMTVIS](slides)
- Demos:
  - [Topk & Beam Search](https://huggingface.co/spaces/gabrielanicole/MNV-beam_search)
  - [Attention visualization](https://huggingface.co/spaces/gabrielanicole/makenmtviz)
  - [Attribution](https://huggingface.co/spaces/gabrielanicole/mnv_attr)
- [Guidelines for demos][https://docs.google.com/presentation/d/1rjLsc1deC2wKk6kdjaV17o_TnoHxbRX-kPLn1264zw0/edit?usp=sharing]

## Medical Text Mining

Le cours en ligne (sur UNESS.fr) de Medical Text Mining fait partie du parcours du Master Artificial Intelligence for One Health (AI4OH) de l'Institut Multidisciplinaire d'Intelligence Artificielle (MIAI). Dans ce cours de master suivi en distanciel, je fais partie de l'équipe ayant conçu le cours et enseigné trois TP (3heqTP) en appliquant la recherche d'information au domaine médical. J'ai créé les support en format de notebook python exécutable d'une durée 3h pour chaque TP, j'ai du répondre aux questions des étudiants dans un forum et organiser une séance en visio de question réponse avec les étudiants pour chaque TP. J'étais également responsable du CM (3heqTD) sur la Recherche d'Information Sémantique appliquée aux données médicales, ce CM est dispensé sous la forme de capsule video. 


## Automates

J'ai enseigné le cours sur les automates à états finis et les langages réguliers. À partir des notions mathématiques et logiques appliquées aux automates, en passant par la définition des automates déterministes, non déterministes et avec des transitions epsilon, incluant les opérations associées ; le cours se termine par l'introduction aux expressions régulières et non régulières en étudiant le théorème de Kleene et le lemme d'itération. J'ai dispensé un total de 54 heures équivalent TD réparties en 36 séances de TD, comprenant 2 groupes de L3 en Informatique et Mathématiques de la Licence Science et Technologies (DLST), pour un total de 59 étudiants. Pour ce cours, j'ai également assuré l'évaluation continue des étudiants.


## Réseaux et télécommunications

j'ai réalisé des cours TP sur les réseaux et les télécommunications au niveau M2de l'IUT1, où nous avons commencé par la conception et la mise en œuvre de réseaux locaux, en appliquant diffèrents protocoles de communication (UDP, TCP/IP) ; jusqu'à la gestion des pare-feux, des serveurs DNS, entre autres.


## Bases de données

J'ai enseigné depuis la phase de conception jusqu'à la mise en œuvre, la consultation et l'administration du système de base de données PostgreSQL. Le cours comprend également un projet final que j'ai conçu pour qu'il soit plus proche possible d'une situation réelle dans le travail d'un administrateur de bases de données. J'ai enseignée cette cours part trois ans, en sa version anglais et français, comprenant le TP, TD et CM. J'ai mis a jour le support de CM et le projet final de TP.  

## Projet - Prog6

J'ai encadré un groupe de cinq étudiants de L3 IM2AG pour l'adaptation d'un jeu de société sous forme de jeu numérique programmé en Java en utilisant le modèle-vue-contrôleur et une interface graphique. L'encadrement se déroulait chaque semaine avec une dédication de 2 heures.



### This is a H3 Heading

#### This is a H4 Heading

##### This is a H5 Heading

###### This is a H6 Heading

## Horizontal Rules

---

---

---

## Emphasis

**This is bold text**

_This is italic text_

~~Strikethrough~~

## Quotes

"Double quotes" and 'single quotes'

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...

## References

An example containing a clickable reference[^1] with a link to the source.

Second example containing a reference[^2] with a link to the source.

[^1]: Reference first footnote with a return to content link.
[^2]: Second reference with a link.

If you check out this example in `src/content/post/markdown-elements/index.md`, you'll notice that the references and the heading "Footnotes" are added to the bottom of the page via the [remark-rehype](https://github.com/remarkjs/remark-rehype#options) plugin.

## Lists

Unordered

- Create a list by starting a line with `+`, `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    - Ac tristique libero volutpat at
    - Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
- Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

4. You can use sequential numbers...
5. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

Block code "fences"

```
Sample text here...
```

Syntax highlighting

```js
var foo = function (bar) {
	return bar++;
};

console.log(foo(5));
```

### Expressive code examples

Adding a title

```js title="file.js"
console.log("Title example");
```

A bash terminal

```bash
echo "A base terminal example"
```

Highlighting code lines

```js title="line-markers.js" del={2} ins={3-4} {6}
function demo() {
	console.log("this line is marked as deleted");
	// This line and the next one are marked as inserted
	console.log("this is the second inserted line");

	return "this line uses the neutral default marker type";
}
```

[Expressive Code](https://expressive-code.com/) can do a ton more than shown here, and includes a lot of [customisation](https://expressive-code.com/reference/configuration/).

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

## Images

Image in the same folder: `src/content/post/markdown-elements/logo.png`

![Astro theme cactus logo](./logo.png)

Image in the aliased assets folder: `src/assets/about-astro.png`

![A cartoon cactus looking at the Astro.build logo](@/assets/about-astro.png)

## Links

[Content from markdown-it](https://markdown-it.github.io/)
