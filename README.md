# Maths Wiki
![](https://github.com/pranshugaba/maths-wiki/workflows/ci/badge.svg)

This repository contains the source of the [Maths Wiki][mainsite] site. 

[mainsite]: https://maths.wiki

Maths Wiki aims to be a fun and exciting resource for learning Maths and Computer Science.  

There is currently some content on the following topics:
- [Combinatorics](https://maths.wiki/combinatorics/)
- [Algebra](https://maths.wiki/algebra/)

More topics will be added in the future as and when the content is written.
- Graph theory
- Probability
- Topology
- Number theory
- Linear Algebra

> This project is a work in progress and is in very early stages of development. Pages might have errors, be incomplete or missing.  [Contributions are welcome!](https://maths.wiki/about/how-to-contribute/)

## Contributing
All content is written in Markdown files and is human-readable using a text editor such as Vim or VSCode. 

There is a special syntax used for examples, theorems, and figures. You can find the reference for the syntax on the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) website. You can also refer to the [markdown source](https://raw.githubusercontent.com/pranshugaba/maths-wiki/master/docs/combinatorics/elementary-methods/pigeonhole-principle.md
) that renders the [pigeonhole principle](https://maths.wiki/combinatorics/elementary-methods/pigeonhole-principle/) page. 

You can edit the markdown files and submit the changes. When it is pushed, it will update on the website. 

Markdown renderers will not properly render the markdown files because the special syntax used in theorems and maths equations. 

Editing markdown files without a preview is fine for small changes such as fixing typos. 
However, if you want to make significant additions / changes, it is recommended you install the MkDocs server so you can preview your content the way will be rendered.


## Installing
The website is built using [MkDocs](https://mkdocs.org) with the [Material for MkDocs theme](https://squidfunk.github.io/mkdocs-material/). 

You would require a recent version of [Python 3](https://www.python.org/) and Pip. 

Install MkDocs and the Material theme using `pip`:
```
mkdocs mkdocs-material
```

Install these plugins with `pip` as well. These are required to build the website:

```
mkdocs-minify-plugin mkdocs-awesome-pages-plugin mkdocs-macros-plugin mkdocs-git-revision-date-localized-plugin mkdocs-redirects
```

Fork this repository on GitHub and clone it. 

``` sh
git clone https://github.com/{YOUR-USERNAME}/maths-wiki
cd maths-wiki
```

## Running the live preview

In the root of the cloned repository, run this to get a live preview running:
``` sh
mkdocs serve
```
If all went well, then MkDocs will let you know that 
```
INFO - Browser Connected: http://127.0.0.1:8000/
```
You should be able to access the website in your browser at that address. 
The site will autoreload each time you edit a file, and you will be able to see your content rendered beautifully. 

When you are done with your changes, create a pull request to submit your changes to this repository. 
