# How to contribute

The book is composed by three main parts:

* **Texts,** in .md format;


* **Visualizations,** in Adobe Illustrator CC 2017 format;
* **Layout,** combining texts and visualization in Adobe InDesign CC 2017 format.

The three parts can be modified in different way.

## Edit texts

Texts are in `.md` format, a popular markdown format commonly used on GitHub. For example, this introduction is written using this format.

It is basically a text file with few special charachters that define the appaerence of text. If you want to learn more, visit this page: https://guides.github.com/features/mastering-markdown/

You can modify it using any text editor, however we strongly recommend to use [Typora](https://typora.io/) which allows you to see the results of your edits.

Texts of the book are divided in six files:

* **chapter-00** contains the inside cover text, introduction, and visual conventions;
* **chapter-01** to **chapter-05** are the files containing texts of related chapters;
* **chapter-06** contains the conclusions, the term glossary, the tools glossary, the list of contributors and the acknowledgements.

### Conventions used in markdown

In the six files we are using the following convention to mark different parts of the text. It's important to keep its usage consistent since we will use this encoding to define the related visual styles in Adobe InDesign. 

- Chapter titles are in H1 (`#`)
- Recipe titles are in H2 (`##`)
- 'Before starting', 'Serving suggestions' and step titles are in H3 (`###`)
- Visualizations titles are in H4 (`####`)
- Bold (`**`) is used to put enphasis on part of the texts.
- Italic (`*`) is used to highlight publication names, names of Facebook pages, and relevant concepts.
- Code + Bold (``**`) is used to indicate tools that are part of the Tools Glossary.
- Code + Italic (``*`) is used to indicate concepts that are part of the Concepts Glossary.

## Edit Visualization

Visualizations are created using [Adobe Illustrator CC 2017](http://www.adobe.com/products/illustrator.html). If you want to modify them, please use the same version to avoid file corruption.

Visualizations are named with the following code:

`Chapter number`-`Step number`-`Visualization letter`

(e.g. 4-2-a.ai)

We don't have a standard code for layers, but in all the visualizations you should keep the guides in the last layer, and the legend in the first one. All the parts related to visualizations (labels, axes, glyphs, etc) can be on a single layer or on multiple one.

Visualizations containing a high number of images (for example visualization 4.3.c) come usually in two files:

* the first one named `X_X_X_working_version.ai`. This file contains all the images as linked files. It must be saved **without** the "Create PDF Compatible Files" option enabled. This helps us to avoid huge files.
* A second one with the standard name (e.g. 4-2-a.ai). This is the file that actually is imported in the InDesign book (see next section, Edit Layout). In this file **all the images are flattened in a single image** in order to make a smaller file. In this case, file must be saved with the "Create PDF Compatible Files" option **enabled**.

## Edit Layout

The overall layout of the book is in [Adobe InDesign CC 2017](http://www.adobe.com/products/indesign.html).

The layout is composed by a book file named `A Field Guide to Fake News.indb`.

It contains the liks to the six sections composing the book.

Before opening the file, check that all the needed fonts are installed on your computer (you can find them in the folder named `Document fonts`).

When you open the InDesign files, all the images will be automatically updated.

Texts, however, won't be automatically updated. While we are working on a more convenient solution, at the moment you have to updated them manually (copying and pasting from the `.md` files).

